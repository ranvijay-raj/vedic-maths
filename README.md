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

### ▶️ 3. Call Any Function

```ved
वद(एकाधिकेन(9));              # Output: 10
वद(संख्या_युग्म(100));         # Output: सत्य
वद(घातक(2, 5));                # Output: 32
वद(गुणक(12));                  # Output: [1, 2, 3, 4, 6, 12]
वद(अभाज्य_संख्या(17));         # Output: सत्य
```

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Author & Contribution

Created to expand the ecosystem of the Vedic Programming Language.

Feel free to fork, improve, and contribute new formulas to this open-source library.
