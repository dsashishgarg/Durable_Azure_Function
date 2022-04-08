# Durable_Azure_Function
Durable_Azure_Function

# Create Virtual Network:
<!-- create commands -->
python3 -m venv <name_of_venv>
<!-- activate command -->
source <name_of_venv>/bin/activate
<!-- deactivate command -->
deactivate

<!-- Theory -->
A basic Durable Functions app contains three functions:
    1.) Client function - a regular Azure Function that starts an orchestrator function. This example uses an HTTP triggered function.
    2.) Orchestrator function - describes a workflow that orchestrates other functions.
    3.) Activity function - called by the orchestrator function, performs work, and optionally returns a value.

    
