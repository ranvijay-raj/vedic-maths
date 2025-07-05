# 📀 वेदिक गणित पुस्तकालय (Vedic Math Library)

A utility library for performing basic mathematical operations in the [Vedic Programming Language](https://vedic-lang.github.io/), written entirely in Sanskrit-style syntax.

This library provides functions for incrementing, decrementing, checking primes, calculating interest, finding factors, and more — making it useful for both educational and practical Vedic programming.

---

## 📁 Functions Included

| Function Name                   | Description                                               |
| ------------------------------- | --------------------------------------------------------- |
| `एकाधिकेन(अंक)`                 | Increases the given number by 1.                          |
| `एकन्यूनेन(अंक)`                | Decreases the given number by 1.                          |
| `संख्या_युग्म(अंक)`             | Checks whether the number is even.                        |
| `संख्या_अयुग्म(अंक)`            | Checks whether the number is odd.                         |
| `संख्या_भाग(dividend, divisor)` | Divides one number by another.                            |
| `मिश्रधन(मूलधन, दर, समय)`       | Calculates simple interest amount.                        |
| `घातक(आधार, घातांक)`            | Raises base to the given power (exponentiation).          |
| `परस्परम(संख्या)`               | Returns the reciprocal of a number.                       |
| `गुणक(संख्या)`                  | Returns all the factors of a number in a list.            |
| `अभाज्य_संख्या(संख्या)`         | Returns `सत्य` if the number is prime, otherwise `असत्य`. |

---

## 🧪 Usage

### 📅 1. Save the Library

Save the library file as `vedic-math.ved` in your project folder.

---

### 📒 2. Import in Your `.ved` Code

Use the following command to import the library:

```ved
अवहन "./vedic-math.ved";
```

---
## 📘 Available Functions

| Function Name                   | Description                                   |
| ------------------------------- | --------------------------------------------- |
| एकाधिकेन(अंक)                   | Increases a number by one                     |
| एकन्यूनेन(अंक)                  | Decreases a number by one                     |
| संख्या\_युग्म(अंक)              | Returns true if even                          |
| संख्या\_अयुग्म(अंक)             | Returns true if odd                           |
| मिश्रधन(म,द,स)                  | Calculates simple interest total amount       |
| संख्या\_भाग(अंश, हर)            | Simple division                               |
| संख्या\_भाग\_तक(अंश, हर, स्थान) | Division till `k` decimal places              |
| परस्परम(संख्या)                 | Reciprocal (1/x)                              |
| घातक(आधार, घात)                 | Power function (base^exponent)                |
| गुणक(संख्या)                    | Factors of the number                         |
| अभाज्य\_संख्या(संख्या)          | Checks for prime number                       |
| अधःस्थमान(संख्या)               | Floor (lower integer)                         |
| अधिकतमं\_पूर्णसंख्या(संख्या)    | Ceil (upper integer)                          |
| परिगणना(संख्या)                 | Rounds off to nearest integer                 |
| परिगणना\_दशांश(संख्या, स्थान)   | Rounds off to given decimal places            |
| वर्गमूल(x)                      | Calculates square root                        |
| कृमि(संख्या)                    | Factorial                                     |
| डिग्री\_से\_रैडियन(डिग्री)      | Converts degrees to radians                   |
| साइन(डिग्री)                    | Calculates sine using Taylor series & table   |
| कोसाइन(डिग्री)                  | Calculates cosine using Taylor series & table |
| टेन(डिग्री)                     | tan(θ) = sin(θ) / cos(θ)                      |
| कोट(डिग्री)                     | cot(θ) = cos(θ) / sin(θ)                      |
| सेक(डिग्री)                     | sec(θ) = 1 / cos(θ)                           |
| कोसेक(डिग्री)                   | cosec(θ) = 1 / sin(θ)                         |

---

## 🧪 Examples

```vedic
वद(संख्या_भाग(10, 2));        # Output: 5
वद(एकाधिकेन(4));              # Output: 5
वद(अभाज्य_संख्या(7));         # Output: सत्य (true)
वद(परिगणना_दशांश(3.14159, 2)); # Output: 3.14
वद(साइन(30));                 # Output: 0.5
वद(कोट(45));                  # Output: 1
```

---

## 🧠 Notes

* All trigonometric functions are degree-based.
* For some common angles (like 30°, 45°, 60°), preset values are returned to ensure accuracy.
* If you pass 0 as denominator, an error message is shown and `0` is returned.
* Default precision for division and rounding is 2 decimal places.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Author & Contribution

Created to expand the ecosystem of the Vedic Programming Language.

Feel free to fork, improve, and contribute new formulas to this open-source library.
