# PRODIGY_ST_01
The First Task.

# Calculator Test Cases

## Test Case 1: Add two positive integers

**Test Case ID**: TC001  
**Test Description**: Validate addition of two positive integers.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "5" in the first operand field.
2. Select the "+" operator.
3. Enter "3" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The result should be "8".

---

## Test Case 2: Add a positive integer and a negative integer

**Test Case ID**: TC002  
**Test Description**: Validate addition of a positive integer and a negative integer.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "7" in the first operand field.
2. Select the "+" operator.
3. Enter "-4" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The result should be "3".

---

## Test Case 3: Subtract two positive integers

**Test Case ID**: TC003  
**Test Description**: Validate subtraction of two positive integers.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "10" in the first operand field.
2. Select the "-" operator.
3. Enter "3" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The result should be "7".

---

## Test Case 4: Multiply two negative integers

**Test Case ID**: TC004  
**Test Description**: Validate multiplication of two negative integers.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "-6" in the first operand field.
2. Select the "*" operator.
3. Enter "-4" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The result should be "24".

---

## Test Case 5: Multiply a positive integer and a decimal number

**Test Case ID**: TC005  
**Test Description**: Validate multiplication of a positive integer and a decimal number.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "5" in the first operand field.
2. Select the "*" operator.
3. Enter "3.5" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The result should be "17.5".

---

## Test Case 6: Divide two positive integers

**Test Case ID**: TC006  
**Test Description**: Validate division of two positive integers.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "12" in the first operand field.
2. Select the "/" operator.
3. Enter "4" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The result should be "3".

---

## Test Case 7: Divide by zero

**Test Case ID**: TC007  
**Test Description**: Validate handling of division by zero.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "5" in the first operand field.
2. Select the "/" operator.
3. Enter "0" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The calculator should display an error message or "Infinity", depending on the implementation.

---

## Test Case 8: Add decimal numbers

**Test Case ID**: TC008  
**Test Description**: Validate addition of decimal numbers.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "2.5" in the first operand field.
2. Select the "+" operator.
3. Enter "3.4" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The result should be "5.9".

---

## Test Case 9: Invalid input (non-numeric character)

**Test Case ID**: TC009  
**Test Description**: Validate that non-numeric input is rejected.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "a" in the first operand field.
2. Select the "+" operator.
3. Enter "5" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The calculator should display an error message indicating invalid input.

---

## Test Case 10: Invalid input (multiple operators)

**Test Case ID**: TC010  
**Test Description**: Validate that multiple operators in sequence are rejected.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "5" in the first operand field.
2. Select the "+" operator.
3. Select the "-" operator immediately after.
4. Enter "3" in the second operand field.
5. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The calculator should display an error message indicating invalid input.

---

## Test Case 11: Mixed operations (BODMAS)

**Test Case ID**: TC011  
**Test Description**: Validate BODMAS (Bracket, Order, Division and Multiplication, Addition and Subtraction) rule compliance.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "2" in the first operand field.
2. Select the "+" operator.
3. Enter "3" in the second operand field.
4. Select the "*" operator.
5. Enter "4" in the third operand field.
6. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The result should be "14" (since multiplication is performed before addition).

---

## Test Case 12: Check large number calculation

**Test Case ID**: TC012  
**Test Description**: Validate the handling of large numbers for calculations.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "1000000000" in the first operand field.
2. Select the "+" operator.
3. Enter "999999999" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The result should be "1999999999".

---

## Test Case 13: Subtract decimal numbers

**Test Case ID**: TC013  
**Test Description**: Validate subtraction of decimal numbers.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "5.75" in the first operand field.
2. Select the "-" operator.
3. Enter "2.25" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The result should be "3.5".

---

## Test Case 14: Invalid input (empty input)

**Test Case ID**: TC014  
**Test Description**: Validate behavior when no input is provided.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Press "=" or the equivalent calculate button without entering any values.  
**Expected Results**:  
The calculator should display an error message indicating missing input.

---

## Test Case 15: Divide by zero (Invalid result handling)

**Test Case ID**: TC015  
**Test Description**: Validate handling of division by zero error with proper message.  
**Preconditions**: Calculator is open and ready to use.  
**Test Steps**:
1. Enter "5" in the first operand field.
2. Select the "/" operator.
3. Enter "0" in the second operand field.
4. Press "=" or the equivalent calculate button.  
**Expected Results**:  
The calculator should display an error message like "Cannot divide by zero" or similar.

---

