# PACE3850---SecuTech-Deliverable-
Notes for COMP3850

Overall objective:
"Objective: An "automatic" software protection/licensing/anti piracy tool, the method for this is by first having a premade program (A) that is bound to a hardware dongle (UniKey: https://esecutech.com/products/unikey/), into which another program's binary (B) is injected into. In this manner, (A) will run first, perform checks that it is allowed to run, then allow (B) to run."

Suggested process:
Pre everything: Read what the lecturer for Comp3850 wrote up (I don't have access to it, no idea what the exam would be on either????)
-Use templates given? Is there a marking rubric? What are the deadlines for submissions of things?
-I'd love to know these too cause I don't know what's going on, or what my own deadlines are, I only get emails, I don't have ilearn access

1. Understanding of task
-What is the objective asking for?
|-How does the existing Enveloper tool work in the UniKey SDK (as a working example)? What is it's usage flow?
|-What is program A?
||-What does it mean to be bound to a UniKey?
|-What is program B?

2. Identify team positions and roles
-Confirm mutual understanding of task
-Can everyone code?
|-What programming language do people like? What about IDE?
-Who wants to "project manage"
-When should there be meetings? Who should be part of these meetings?
-Who is comfortable with handling documentation?
-Who wants to make program A?
|-Who wants to set up dev environment
|-How to handle code sharing
|-How to handle document sharing/updates
|-Backups?
-What OS does people like? (assuming windows from when we met)

3. Break down of project
-Distribution of tasks
|-Documentation
|-Coding
|-Reporting
|-Testing
|-Research
||-3rd party repositories etc.

4. Feasibility and alternatives
-Documentation can also include "hypothetical" goals, user interface, options available to end user etc
|-These do not need to be implemented, just planned/thought of
-What issues are expected? Limitations of different approaches

5. Design and implementation
-Initial stage feasibility
|-Test 3rd party software
|-Research alternative methods to meet objective
-Implementation stage
|-Co-ordination between team members
|-Documentation and luxury item research
-Testing stage
|-Continuous or milestone based?
|-Documented or handled by coder?

6. Final notes
-Does not actually need to be finished
|-Comments and thoughts on what's next

For point 4 and 5 when checking feasibility or use of 3rd party githubs, please do further analysis of these, I literally spent 30 seconds glancing through them:
https://github.com/jdecorte-be/42-WoodyWoodpacker
Target platform: linux
Well documented: Yes
Achieves objective: Seems likely

https://github.com/JoelClingempeel/BinInject/tree/main
Target platform: linux? (Not sure)
Well documented: Moderately, code seems clean
Achieves objective: Seems likely

https://github.com/theevilbit/injection
Target platform: Windows (visual studio 2017, C++)
Well documented: Yes (almost overwhelming)
Achieves objective: Yes

https://github.com/rsmusllp/syringe
Target platform: Windows (Visual stido 2013, C)
Well documented: yes
Achieves objective: Seems likely

PLEASE USE A VM FOR TESTING THESE REPOSITORIES!!! I can not guarantee your safety if you run bare metal