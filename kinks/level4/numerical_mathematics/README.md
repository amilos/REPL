[Go back to the main page](https://world-class.github.io/REPL/)

# Table of contents
- [Table of contents](#table-of-contents)
- [Numerical Mathematics - Reported problems](#numerical-mathematics---reported-problems)
  - [Week 1](#week-1)
    - [Video: 1.001 Introduction to number bases and modular arithmetic](#video-1001-introduction-to-number-bases-and-modular-arithmetic)
    - [Video: 1.101 Introduction to number bases](#video-1101-introduction-to-number-bases)
    - [Video: 1.107 Place value for fractional numbers: binary](#video-1107-place-value-for-fractional-numbers-binary)
    - [Practice quiz: 1.110 Rational and irrational numbers: decimal and binary](#practice-quiz-1110-rational-and-irrational-numbers-decimal-and-binary)
  - [Week 2](#week-2)
    - [Video: 1.401 Octal and hexadecimal (integer)](#video-1401-octal-and-hexadecimal-integer)
    - [Practice quiz: 1.404 Translate between decimal and hexadecimal or octal (fractional)](#practice-quiz-1404-translate-between-decimal-and-hexadecimal-or-octal-fractional)
    - [Video: 1.405 Special relationship between binary and hexadecimal, and binary and octal](#video-1405-special-relationship-between-binary-and-hexadecimal-and-binary-and-octal)
    - [Practice quiz: 1.406 Translate between binary and hexadecimal/octal](#practice-quiz-1406-translate-between-binary-and-hexadecimaloctal)
    - [Practice quiz: 1.602 Arithmetic in hexadecimal/octal](#practice-quiz-1602-arithmetic-in-hexadecimaloctal)
  - [Week 3](#week-3)
    - [Lesson 1.10: Video 1.1006 Mod, rem and division](#lesson-110-video-11006-mod-rem-and-division)
    - [Lesson 1.11: Video 1.1101 Encryption using modular arithmetic](#lesson-111-video-11101-encryption-using-modular-arithmetic)
  - [Week 4](#week-4)
    - [Lesson 2.1: Video 2.103 Defining sequences](#lesson-21-video-2103-defining-sequences)
    - [Lesson 2.2: Video 2.201 Arithmetic progressions](#lesson-22-video-2201-arithmetic-progressions)
  - [Week 6](#week-6)
    - [Lesson 3.1: Video 3.101 Cartesian coordinates](#lesson-31-video-3101-cartesian-coordinates)

# Numerical Mathematics - Reported problems
This page is about the [numerical mathematics module](../../../modules/level_4/numerical_mathematics/).

## Week 1
### Video: 1.001 Introduction to number bases and modular arithmetic
- At 11:16, `(255, 255, 255)` is **white**, not blue.

### Video: 1.101 Introduction to number bases
- At 11:34: Wrong. Each column is a power of 60, so it should be times `1`, times `60` and times `3600`.


### Video: 1.107 Place value for fractional numbers: binary
- At 0:37: The "fractional point" is called "radix point".

### Practice quiz: 1.110 Rational and irrational numbers: decimal and binary
- Answers should be given without spaces.
- When a repeating fractional part is present, the answer should be written as `i.rr...`, where `i` stands for **integer part**, `r` is the **repeating** fraction and one must include three dots at the end. Example:

    3.12121212121212

  is written as
  
    3.1212...

## Week 2
### Video: 1.401 Octal and hexadecimal (integer)
- In the quiz at 3:41, the place values are supposed to be entered as "1, 16, 256". The answer isn't accepted.
- In the quiz at 4:24, 65536 should be written as 2^(16), but the "6" isn't part of the exponent part.
- At 5:07, second letter in hexadecimal should be "B", not "D".
- At 6:01, the hexadecimal number `11F` should have an expansion starting with `1 × 16^2`, not `1 × 16 (base 2)` as displayed.
- In the quiz at 6:29, the third answer is 256, not 64. The last part is asking in the quiz for multiples in binary while the answer is given for hexadecimal.

### Practice quiz: 1.404 Translate between decimal and hexadecimal or octal (fractional)
- `3.44` in octal is `3 + 1/2 + 1/16`, not `3 + 1/2 + 1/32`.
- Options may present groupings of numbers. If a grouping is supposed to be of **3** digits for instance and you're presented with **4** digits, assume that the last digit should be in subscript (representing the number base, such as **2** for binary or **8** for octal) so that it makes sense when reading. In a grouping of 3 digits, `0002` should be interpreted as `000`, base `2`.

### Video: 1.405 Special relationship between binary and hexadecimal, and binary and octal
- At 7:38, this is wrong. `C` (base 16) = 12 (base 10) = 1100 (base 2), not 1101.
- At 11:24, The grouping of digits is wrong.

    1.001.111 1

  in binary should read

    1 001.111 1

  having only one radix point.

- At 11:37, it is said the answer is `11.71` (base 8). Wrong: It's `11.74` (base 8).

### Practice quiz: 1.406 Translate between binary and hexadecimal/octal
- Question 6: `73.06` (base 8) *is* `111011.00011` in binary.

### Practice quiz: 1.602 Arithmetic in hexadecimal/octal
- `6D * 60` in hexadecimal is `28E0`.
- `6C * 3B` in hexadecimal is `18E4`.

## Week 3
### Lesson 1.10: Video 1.1006 Mod, rem and division
- At 1:49, the expression isn't rendered properly (the congruence symbol doesn't appear). Subsequent expressions also present this issue.

### Lesson 1.11: Video 1.1101 Encryption using modular arithmetic
- The video contains many display errors that are fixed in a previously uploaded version. While not being flawless, it's much better. For now, the video can be downloaded [from this link](https://www.dropbox.com/s/w52vpsau7ly6tc6/1_1101_Encryption_using_modular_arithmetic.mp4?dl=1). If you want to add subtitles, you can [download them here](https://www.dropbox.com/s/5hso65rut3u337q/1_1101_subtitles-en.vtt?dl=1).
  - If you don't know how to add the subtitles to the video, try with [VLC media player](https://www.videolan.org/vlc/) (free): open the video (`1_1101_Encryption_using_modular_arithmetic.mp4`) and from VLC, click at the top on `Subtitle`, then on `Add Subtitle File...` and open the subtitles file (`1_1101_subtitles-en.vtt`). They will automatically be added and synced to the video.
- At 3:43, a banner appears in the background and has nothing to do with was it being taught.
- At 4:40 and 4:52, the congruence symbol is not rendered properly:
    
    C ≡ M^e (mod p)

- At 6:04, it should be `C^7 (mod 11)`, not `C^3 (mod 11)`.
- At 8:43, the equation appears in the background and can't be read. The equation is:

    ed = 3 × 7 is 21

- At 11:28, again the expression can't be read. The expression is:

    a^p ≡ a (mod p)


## Week 4
### Lesson 2.1: Video 2.103 Defining sequences
- Audio is out of sync from 15:19 onward: please refer to the transcript to better follow along.

### Lesson 2.2: Video 2.201 Arithmetic progressions
**Partially fixed**. The transcript and subtitles do not appear at this moment.

## Week 6
### Lesson 3.1: Video 3.101 Cartesian coordinates
- There is no sound. For now, you can download the video [from this link](https://www.dropbox.com/s/922gj1vefoedx0y/3_101_cartesian_coordinates.mp4?dl=1). You can get the subtitles [from this link](https://www.dropbox.com/s/arvg0fuu7867vnl/3_101_subtitles-en.vtt?dl=1).
  - If you don't know how to add the subtitles to the video, try with [VLC media player](https://www.videolan.org/vlc/) (free): open the video (`3_101_cartesian_coordinates.mp4`) and from VLC, click at the top on `Subtitle`, then on `Add Subtitle File...` and open the subtitles file (`3_101_subtitles-en.vtt`). They will automatically be added and synced to the video.
