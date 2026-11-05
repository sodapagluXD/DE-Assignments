# Assignment 1

AI-Assisted Boolean Expression Simplifier — use GenAI to reduce a 4–6
variable expression (SOP/POS, K-map/algebraic), then implement and
verify the simplified circuit in a simulator


Prompt : Simplify the 4-variable Boolean expression $F(A,B,C,D) = \Sigma m(0, 2, 8, 10, 12, 14)$ using a Karnaugh map and provide the minimized SOP expression

Discussion : The GenAI successfully minimized a 6-term SOP expression down to a 3-gate circuit ($B'D' + AD'$), drastically reducing hardware cost and propagation delay. The Logisim output exactly matched the AI's predicted logic table across all 16 states, requiring no manual structural corrections