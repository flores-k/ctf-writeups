# CTF Writeup

**Platform:** CyLab Security Academy

**Category:** Cryptography

**Difficulty:** Easy

**Date:** November 2, 2026

---

## Challenge Description

> What does this bDNhcm5fdGgzX3IwcDM1 mean? I think it has something to do with bases.

**Files/Target:**

- N/A

---

## Recon

The challenge said it has something to do with bases. However, I do not know what base it is so I plan to identify which base it is.

---

## Tools Used

- CyberChef - To decode the unknown base

---

## Solution

1. I read the challenge description and it asked what bDNhcm5fdGgzX3IwcDM1 mean
2. I copied the given and went to CyberChef
3. I imported "Magic" as recipe to automatically detected the base and decode it
4. Then, pasted the given in input field
5. Viola! I got the flag

```bash
# N/A
```

---

## Flag

```
academy{l3arn_th3_r0p35}
```

---
## Takeaways

- I learned how to use "Magic" recipe of CyberChef. It was useful in cases where you don't know what base it is

---

## References

- N/A