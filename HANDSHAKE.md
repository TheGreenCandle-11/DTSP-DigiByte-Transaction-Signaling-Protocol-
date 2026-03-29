# DTSP Handshake Protocol v1.0

## Purpose

The handshake establishes synchronization between sender and receiver before message transmission.

---

## Control Codes

| Signal | Amount |
|--------|--------|
| start  | 0.00022611 |
| accept | 0.00022631 |
| end    | 0.00022621 |

---

## Rules

- Sender initiates with (start)
- Receiver responds with (accept)
- Absence of response = rejection
- Sender transmits message
- Sender terminates with (end)

---

## Example Flow

Sender:
0.00022611 (start)

Receiver:
0.00022631 (accept)

Sender:
Message sequence...

Sender:
0.00022621 (end)
