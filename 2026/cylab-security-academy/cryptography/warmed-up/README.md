# CTF Writeup

**Platform:** CyLab Security Academy

**Category:** Cryptography

**Difficulty:** Easy

**Date:** October 22, 2026

---

## Challenge Description

> What is 0x3D (base 16) in decimal (base 10)?

**Files/Target:**

- No files/links provided

---

## Recon

The word "base 16" popped up and the challenge is related to CyberChef. Therefore, I concluded that it's cryptography challenge.

---

## Tools Used

- CyberChef - To convert base 16 to base 10

---

## Solution

1. I read the challenge description and it asked what 0x3D (base 16) is in base 10
2. I copied the given base 16 and went to CyberChef
3. I imported To Base as recipe and changed the radix to 10
4. Then, pasted the copied base 16 in input field
5. Viola! I got the flag

---

## Flag

```
academy{61}
```

---
## Takeaways

- I learned how to use CyberChef. Specifically, the coversion of base 16 to base 10

---

## References

- No references