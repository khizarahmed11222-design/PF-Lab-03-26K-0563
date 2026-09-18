# C MarkDown Documentation

## 1. Data Types

| Data Type | Size | Description |
| :--- | :--- | :--- |
| `int` | 4 bytes | Stores whole numbers (e.g., -5, 42). |
| `float` | 4 bytes | Stores numbers with decimals up to 6-7 digits. |
| `double` | 8 bytes | Stores numbers with decimals up to 15 digits (higher accuracy). |
| `char` | 1 byte | Stores a single character (e.g., 'A'). |
| `bool` | 1 byte | Stores `true` (1) or `false` (0). |
| `void` | 0 bytes | Means no value or no return type. |

---

## 2. Format Specifiers

| Format Specifier | Description |
| :--- | :--- |
| `%d` | Signed integer |
| `%u` | Unsigned integer |
| `%o` | Octal integer |
| `%x` | Hexadecimal integer (lowercase) |
| `%X` | Hexadecimal integer (uppercase) |
| `%f` | Floating-point number |
| `%e` | Exponential/Scientific notation |
| `%c` | Single character |
| `%s` | String (text) |
| `%ld` | Long integer |

---

## 3. Input/Output Functions

* **`scanf()`**: Reads input from the keyboard.
* **`printf()`**: Prints output on the screen.
* **`getchar()`**: Reads a single character.
* **`putchar()`**: Displays a single character.
* **`fgets()`**: Safely reads a line of text or string.
* **`puts()`**: Prints a string with a new line.

---

## 4. Escape Sequences

| Escape Sequence | Name | Description |
| :--- | :--- | :--- |
| `\n` | Newline | Moves to the next line. |
| `\t` | Tab | Adds a tab space. |
| `\\` | Backslash | Displays a backslash (`\`). |
| `\"` | Double Quote | Displays a double quote (`"`). |
| `\0` | Null Character | Marks the end of a string. |

---

## 5. Precision

Precision specifies the number of decimal places to show for floating-point numbers using `%.Nf` format (where `N` is the decimal count).

* `%.1f` — Displays 1 decimal place (e.g., `3.1`).
* `%.2f` — Displays 2 decimal places (e.g., `3.14`).
* `%.4f` — Displays 4 decimal places (e.g., `3.1416`).
