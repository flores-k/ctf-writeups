# CTF Writeup

**Platform:** CyLab Security Academy

**Category:** Cryptography

**Difficulty:** Easy

**Date:** November 1, 2026

---

## Challenge Description

> Can you convert the number 42 (base 10) to binary (base 2)?

**Files/Target:**

- N/A

---

## Recon

I know it's cryptography because there are familiar words such as "convert", "binary", and "base". It also says that the challenge can be solved with CyberChef

---

## Tools Used

- CyberChef - To convert base 10 to base 2

---

## Solution

1. I read the challenge description and it asked what number 42 (base 10) is in base 2
2. I copied the given base 10 and went to CyberChef
3. I imported "To Base" as recipe and changed the radix to 2
4. Then, pasted the copied base 10 in input field
5. Viola! I got the flag

```bash
# N/A
```

---

## Flag

```
academy{101010}
```

---
## Takeaways

- I learned how to use CyberChef to convert base 10 to base 2

---

## References

- N/A