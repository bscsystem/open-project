---
testspace:
before:
  name: aws:us-east-1:stage-app
  description: Lambda function sets application in idle state
  inputs:
    file: "@dataset.json"
---

# Startup 
This tests stages the application to be in state `idle`. Before starting show display
the following:

![states][state-machine.png "State machine"]

## Check Transitions
Verify that the image is correctly displayed based on following table:

Id1 | Id2
--- | ---
Aa  | Ba

- The `Aa` should be displayed first
- Check next step for **Id2**. Should display url. 

## Exploratory
Capture observations based state transitions. Include screen shots with comments.

