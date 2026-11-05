# Assignment 5

Digital Clock FSM Design with GenAI — use GenAI to derive FSM
states and flip-flop-based implementation for a 24-hour digital clock;
simulate and verify seconds/minutes/hours counting


# Prompt

Derive the FSM states and modular counter logic for a 24-hour digital clock using flip-flops.



# Discussion

The GenAI effectively segmented the complex 24-hour FSM into manageable cascaded Mod-60 and Mod-24 state machines. The Logisim hardware matched the AI's generated output, successfully incrementing the seconds, minutes, and hours accurately using asynchronous falling-edge J-K flip-flops. The specific Mod-24 global reset logic (combining $H_t = 2$ and $H_u = 4$) was correctly implemented, ensuring the clock rolls over from 23:59:59 to 00:00:00 without requiring manual logical corrections.


