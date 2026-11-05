# Assignment 3

FSM Design for Traffic Light Controller using GenAI — use GenAI to
generate the state diagram/table/logic equations for a 3-light + pedestrianrequest FSM; implement with flip-flops and simulate

# Prompt:

Generate a state transition table and D flip-flop logic equations for a Moore FSM traffic light controller with 3 states (00=Green, 01=Yellow, 10=Red) and one pedestrian-request input (P). The light transitions from Green to Yellow if P=1; otherwise, it stays Green. Yellow and Red states transition automatically to the next state.

# Discussion:

The GenAI effectively minimized the scenario into a 3-state Moore machine and provided accurate D flip-flop excitation equations. The Logisim hardware implementation successfully replicated the intended traffic sequence, transitioning properly from Green to Yellow only when the pedestrian request was active. The AI-generated logic required no manual state-reduction corrections, fulfilling the sequential FSM design parameters.