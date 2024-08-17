# Day 1: Variables, Data Types, and Operators

## **1. Variables**

Variables are used to store data that can be referenced and manipulated in a program. In JavaScript, variables can be declared using three keywords: var, let, and const.

### **Types of Variable Declarations:**

- **`var`:**

  - Function-scoped or globally-scoped (not block-scoped).
  - Can be re-declared and updated.
  - Hoisted to the top of their scope but initialized with undefined.

- **`let`:**

  - Block-scoped (only accessible within the block they are declared).
  - Can be updated but not re-declared within the same scope.
  - Not initialized until the line of declaration is executed.

- ** `const`: **
  - Block-scoped.
  - Cannot be updated or re-declared (must be initialized at the time of declaration).
  - Useful for constants or variables that shouldn’t be reassigned.

## 2. **Data Types**

JavaScript is a dynamically typed language, meaning variables can hold different data types, which are determined at runtime. The main data types are:

- `String`: Represents textual data.
- Example: "Hello, World!"
- `Number`: Represents both integer and floating-point numbers.
  - Example: 42, 3.14
- `Boolean`: Represents logical values: true or false.
  Example: true
- `Null`: Represents the intentional absence of any object value.
  - Example: null
- `Undefined`: Indicates that a variable has been declared but not yet assigned a value.
  - Example: undefined
- `Symbol (ES6)`: Represents a unique and immutable identifier.
  - Example: Symbol('description')
- `BigInt (ES11)`: Represents integers with arbitrary precision.
  - Example: 9007199254740991n

3. Non-Primitive Data Types:

- `Object`: Collection of properties (key-value pairs).
  - Example: { name: "Alice", age: 30 }
- `Array`: Ordered collection of values.
  - Example: [1, 2, 3, 4]

* `Function`: Block of code designed to perform a specific task.
  - Example:
  ```js
  function greet() {
    console.log("Hello, World!");
  }
  ```

## **3.Operators**

Operators are used to perform operations on variables and values. JavaScript provides a variety of operators.

**Arithmetic Operators:**

- `+`(Addition): Adds two values.
- `-` (Subtraction): Subtracts one value from another.
- `*` (Multiplication): Multiplies two values.
- `/` (Division): Divides one value by another.
- `%` (Modulus): Returns the remainder of a division.
- `++` (Increment): Increases a value by 1.
- `--` (Decrement): Decreases a value by 1.

**Comparison Operators:**

- `==` (Equal to): Compares two values for equality (loose equality, type conversion).
- `===` (Strict equal to): Compares two values for equality without type conversion.
- `!=` (Not equal to): Compares two values for inequality.
- `!==` (Strict not equal to): Compares two values for inequality without type conversion.
- `>` (Greater than), `<`(Less than)
- `>=` (Greater than or equal to), `<=` (Less than or equal to)

**Logical Operators:**

- && (AND): Returns true if both operands are true.
- || (OR): Returns true if at least one operand is true.
- ! (NOT): Inverts the truthiness of a value.
