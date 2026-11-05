# Assignment 4

AI-Based Fault Detection in Digital Circuits — design a deliberately
faulty circuit (e.g., a Full Adder with an error), have GenAI diagnose the
fault from the truth table, then correct and re-verify

# Prompt: 

Here is a faulty truth table for a Full Adder. The Cout is correct, but the Sum column is outputs are: 0, 0, 1, 1, 1, 1, 0, 0 (for inputs 000 to 111). Diagnose the fault and provide the corrected logic.

# Discussion: 

The GenAI successfully diagnosed the hardware fault strictly by analyzing the input-output mapping of the truth table. It correctly identified the missing gate logic and proposed the standard 3-input XOR cascade for the Sum. The Logisim verification confirmed that the AI's suggested hardware correction fully restored normal Full Adder operation without further manual adjustments