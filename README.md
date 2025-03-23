# MicroTime

## How
This is a new way of expressing time that can represent very long periods of time.

It's very simple:
1. Measure the number of milliseconds since January 1, 2000 (UTC)
2. Convert to binary

## Versions

### MicroTime 48 - [Demo](https://kamu.jp/microtime/48/)
- MicroTime 48 is the first MicroTime notation.
- It represents MicroTime with 48 digits.
- It can be used up to about the year 8.9 Million.

### MicroTime 64 - ...
- MicroTime 64 is the second MicroTime notation.
- It represents MicroTime with 64 digits.
- It can be used up to about the year 584.5 Billion.

### MicroTime XX - ...
At the time of creating MicroTime, 48 bits was more than enough, and we believe that 64 bits is very reliable.

However, the "UNIX epoch", which was the standard at the time, was originally 32 bits, and was a notation method that would soon run out of space.

If you run out of digits in MicroTime, please see below:
- Feel free to also use MicroTime 96 or MicroTime 128.
- However, make sure that the number part is the "number of digits in binary form".
