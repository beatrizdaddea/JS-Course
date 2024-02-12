### JavaScript Primitive Data Types

Primitive values are immutable, meaning that once a primitive value is assigned to a variable, it cannot be changed directly. Any operation that appears to modify the primitive value is, in fact, creating a new value.

In addition to primitives, JavaScript has non-primitive data types (objects) such as objects, arrays, functions, and others. These are known as composite data types and differ from primitives in terms of mutability and behavior.

1. **String:**
   - Represents sequences of characters and is declared using single or double quotes.
     ```javascript
     let text = 'This is a string';
     ```

2. **Number:**
   - Represents integer or floating-point numbers.
     ```javascript
     let integerNumber = 42;
     let decimalNumber = 3.14;
     ```

3. **Boolean:**
   - Represents a logical value, either `true` or `false`.
     ```javascript
     let trueValue = true;
     let falseValue = false;
     ```

4. **Undefined:**
   - Represents a variable that has been declared but has not yet been assigned a value.
     ```javascript
     let undefinedValue;
     ```

5. **Null:**
   - Represents the intentional absence of any object or value.
   - At some point, you can deconfigure this variable
   - Return Object in typeof command
     ```javascript
     let nullValue = null;
     ```

6. **Symbol:**
   - Introduced in ECMAScript 6 (ES6), represents a unique identifier and is typically used to create object properties that do not clash with other properties.
     ```javascript
     let symbol = Symbol('description');
     ```

