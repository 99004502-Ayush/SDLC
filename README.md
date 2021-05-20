# High Level Test Plan
| TEST No. | Description |Input | Expected output | Actaual Output | Pass/Fail |
|----------|-------------|--------|--------|----------------|-----------|
|   T01    | Transmission of data from the source node to the destinantion node  | 11 |11 | ...... | Pass |

# Unit Level Test Plan
| TEST No. | Description | Input | Expected output | Actaual Output | Pass/Fail |
|----------|-------------|-------------|----------|--------------|-----------|
|   T01    | CRC         | 00100100 | 100100001  | ....... | Pass |
|   T02    | Odd Parity | 01001101 | 10011011 | ........ | Pass |
|   T03    | Even Parity/Vertical Redundancy Check | 01100111  | 11001111 | ....... | Pass |
|   T04    | Checksum |10101001 00111001 | 00011101 | ........| Pass|
|   T05    | Dijkstra’s algorithm  | SUCCESS | SUCCESS |......| Pass |


