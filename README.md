# Things We Need
- [x] Verbose/Quiet
- [x] Error/NoError
- [x] Server shutdown
- [x] Allow more than one transfer
- [x] Timeout

# Error 4 Cases
- [x] Invalid Opcode DATA
- [x] Invalid Opcode ACK
- [x] Invalid Opcode RRQ
- [x] Invalid Opcode WRQ
- [x] Invalid Block # ACK
- [x] Invalid Block # DATA
- [x] Check for First 0 in RRQ/WRQ
- [x] Invalid Filename in RRQ/WRQ
- [x] Check for Second 0 in RRQ/WRQ
- [x] Invalid mode in RRQ/WRQ


# Tests

<b> READ </b>
- [x] Empty file

Normal <br>
- [x] Single block
- [x] Double block
- [x] 512 bytes
- [x] 132,000 bytes

Duplicate <br>
- [x] RRQ
- [x] Single block, DATA
- [x] Single block, ACK
- [x] Double block, DATA, 1
- [x] Double block, ACK, 1

Delay <br>
- [x] RRQ
- [x] Single block, DATA
- [x] Single block, ACK
- [x] Double block, DATA, 1
- [x] Double block, ACK, 1

Lost <br>
- [x] RRQ
- [x] Single block, DATA
- [x] Single block, ACK
- [x] Double block, DATA, 1
- [x] Double block, ACK, 1

<hr>

<b> WRITE </b>
- [x] Empty file

Normal <br>
- [x] Single block
- [x] Double block
- [x] 512 bytes 
- [x] 132,000 bytes

Duplicate <br>
- [x] WRQ
- [x] Single block, DATA
- [x] Single block, ACK
- [x] Double block, DATA, 1
- [x] Double block, ACK, 1

Delay <br>
- [x] WRQ
- [x] Single block, DATA
- [x] Single block, ACK
- [x] Double block, DATA, 1
- [x] Double block, ACK, 1

Lost <br>
- [x] WRQ
- [x] Single block, DATA
- [x] Single block, ACK
- [x] Double block, DATA, 1
- [x] Double block, ACK, 1
