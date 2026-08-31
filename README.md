**Topic: FSM**

Design a Mealy sequence detector that detects the bit pattern:
1011

**Inputs **: 
clk
reset
din

**Output**
detect

**Expected behavior**
detect = 1 for one clock cycle whenever the sequence 1011 is detected.
Otherwise, detect = 0.
Overlapping sequences must be supported.

**Example:**

din:     1 0 1 1 0 1 1

detect:  0 0 0 1 0 0 1
