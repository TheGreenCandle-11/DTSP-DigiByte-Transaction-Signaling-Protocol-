# DigiByte Transaction Signaling Protocol (DTSP)

DTSP is a lightweight signaling protocol that encodes messages using DigiByte transaction amounts.

It enables communication using standard transactions without metadata or scripting.

---

## How It Works

Each transaction amount represents a character.

A sequence of transactions forms a message.

---

## Example

H = 0.00022666  
E = 0.00022663  

---

## Documentation

- Specification → SPEC.md  
- Handshake → HANDSHAKE.md  
- Examples → EXAMPLES.md  

---

## Properties

- Deterministic encoding
- No OP_RETURN required
- Compatible with standard wallets
- Fully on-chain signaling

---

## Limitations

- Requires precise transaction amounts
- Susceptible to wallet rounding
- Not private (fully transparent)
- Fee overhead per character

---

## Status

Draft v1.0

---

## License

MIT
