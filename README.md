# LRM Remediation Evaluation

This is the project for the advanced software security module.

## What does it do?

This LRM application takes risk scenarios and countermeasures to the threats and vulnerabilities in the scenario, and uses a Large Reasoning Model to reason and suggest appropriate countermeasures to a risk scenario.

## How to use it?

All the app is developed in a Jypter environmnet. Seperate instructions for running the app are also provided in `workflow.ipynb`.

### Loading the data

To load the data into the app you need 2 files `Scenarios.xlsx` and `Remediations.xlsx` present in the `./data/` directory. 
You can also specify a third file, `scen.txt` that contains the user risk scenarios to be analyzed.