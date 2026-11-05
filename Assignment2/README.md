# Assignment 2

Natural Language to Logic Circuit Generator — convert an English
description of a logical situation into a Boolean expression and gate-level
design using GenAI, then simulate and verify

# Prompt  : 
Convert this English description into a Boolean expression and logic gate design: A secure vault opens (Output Y) only if the Master Key (A) is inserted AND either the Manager PIN (B) is correct OR the Biometric scan (C) is successful

# Discussion : 
The AI accurately mapped the natural language constraints of the secure vault scenario directly to the Boolean expression Y = (B + C) without logical errors. The linguistic operators "AND" and "either/OR" were correctly translated to a two-level gate architecture utilizing one OR gate and one AND gate.During simulation, the circuit output strictly matched the AI-generated truth table, fulfilling the verification requirement. The hardware successfully demonstrated that the system remains locked (0) if the Master Key (A) is absent, regardless of the other inputs. The output only registered HIGH (1) when input A was active concurrently with either input B or input C. No manual corrections were necessary for the AI's proposed hardware realization, proving the reliability of the generated logic. This confirms the efficacy of using generative models for rapid prototyping of combinational logic directly from plain-English functional requirements. 
