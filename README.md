## Python cross-platform (passlib) sha512

Generate a sha512 password hash using passlib as produced by Linux crypt (C)

![genSHA512 (passlib)](https://github.com/nicholashoule/passlibSHA512/workflows/genSHA512%20(passlib)/badge.svg?branch=master)
[![Run on Repl.it](https://repl.it/badge/github/nicholashoule/passlibSHA512)](https://repl.it/github/nicholashoule/passlibSHA512)

##### Key derivation functions supported by crypt:

Ref: https://en.wikipedia.org/wiki/Crypt_(C)

| ID             | Schema            | Example                             |
|----------------|-------------------|-------------------------------------|
|  1             | MD5               | $1$etNnh7FA$OlM7eljE/B7F1J4XYNnk81  |
|  2, 2a, 2x, 2y | bcrypt            | $2a$10$VIhIOofSMqgdGlL4wzE//e.77dAQGqntF/1dT7bqCrVtquInWy2qi |
|  3             | NTHASH            | $3$$8846f7eaee8fb117ad06bdd830b7586c |
|  5             | SHA-256           | $5$9ks3nNEqv31FX.F$gdEoLFsCRsn/WRN3wxUnzfeZLoooVlzeF4WjLomTRFD |
|  6             | SHA-512           | $6$qoE2letU$wWPRl.PVczjzeMVgjiA8LLy2nOyZbf7Amj3qLIL978o18gb... |
| md5            | Solaris MD5       | $md5,rounds=5000$GUBv0xjJ$$mSwgIswdjlTY0YxV7HBVm0 |
| sha1           | PBKDF1 with SHA-1 | $sha1$40000$jtNX3nZ2$hBNaIXkt4wBI2o5rsi8KejSjNqIq |

##### python3:

Python 3.7+

##### Run the code:
https://repl.it/@NicholasHoule/passlibSHA512#genSHA512.py
