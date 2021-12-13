# CN_PracticalExam

```
Name: Esha Singh
Exam roll no: 20020570013 
Ramanujan College, DU
B.Sc(H) Computer Science

13 December 2021 | Semester: 3

```
Practical 1: 
Simulate Cyclic Redundancy Check (CRC) error detection algorithm for noisy channel.

CRC (Cyclic Redundancy Check) is a checksum algorithm to detect inconsistency of data, e.g. bit errors during data transmission. A checksum, calculated by CRC, is attached to the data to help the receiver to detect such errors.
CRC is based on division. The actual input data is interpreted as one long binary bit stream (divident) which is divided by another fixed binary number (divisor). The remainder of this division is the checksum value.

Practical 2:
Simulate and implement selective repeat sliding window protocol.

Selective repeat protocol, also called Selective Repeat ARQ (Automatic Repeat reQuest), is a data link layer protocol that uses sliding window method for reliable delivery of data frames.
In the selective repeat, the sender sends several frames specified by a window size even without the need to wait for individual acknowledgement from the receiver as in Go-Back-N ARQ. In selective repeat protocol, the retransmitted frame is received out of sequence.

STEPS:-

1) In SR protocol, sender window size is always same as receiver window size.

2) SR protocol uses independent acknowledgements only.

3) SR protocol does not accept the corrupted frames but does not silently discard them.

4) SR protocol accepts the out of order frames.

5) SR protocol requires sorting at the receiver’s side.

6) SR protocol requires searching at the sender’s side.
