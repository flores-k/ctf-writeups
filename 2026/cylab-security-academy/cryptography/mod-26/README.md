# CTF Writeup

**Platform:** CyLab Security Academy

**Category:** Cryptography

**Difficulty:** Easy

**Date:** October 22, 2026 

---

## Challenge Description

> Cryptography can be easy, do you know what ROT13 is?

**Files/Target:**

1. values.txt

---

## Recon

The challenge description explicitly says it's a cryptography challenge and it's ROT13. I have a CTF background so my first thought is to copy the contents of the given file and put it in CyberChef.

---

## Tools Used

1. wget - To download the file.
2. cat - To view the contents of the file.
3. CyberChef - To decrypt the ROT13.

---

## Solution

1. I read the challenge description and viewed the hints
2. I changed directory to downloads folder because I want to
3. I downloaded the given file using wget
4. I viewed the contents of values.txt using cat and copied it
5. I visited CyberChef, imported ROT13 as recipe, and pasted the content from values.txt in input field
6. I let CyberChef cook and voila! I have the flag

```bash
cd Downloads
```

```bash
wget https://challenge-files.cylabacademy.net/library/b4b7a760f3cbe1217f2bcfd5d245310af6ed136d50e2884ec79deb6e078b30ce/values.txt
```

```bash
cat values.txt
```

---

## Flag

```
academy{next_time_I'll_try_2_rounds_of_rot13_5c5f5b36}
```

---
## Takeaways

- I learned cd, wget, and cat commands. Also, I learned the process on solving cryptography challenges
- I want to improve my solving time while writing a write-up

---

## References

- No references