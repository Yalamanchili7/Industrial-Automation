# Industrial-Automation
1.  Develop a Main Routine

Develop the Main Routine for your project using the provided project template as your foundation

2.  Develop a reset subroutine

Develop a reset subroutine that will systematically position the workstation to a predefined Home state.

Step 1 - Define individual steps that will choreograph the automation components to a predetermined position and ensure no unintended interaction between the automation components during the positioning movements.

Example list of steps to reset workstation:

Turn off all tower indicator lamps
Blink amber tower indicator to signal system resetting
Turn off vacuum
Retract box ejector
Retract vacuum head
Rotate vacuum head clockwise
Raise vacuum head
Position vacuum head at box magazine
Rotate vacuum head counterclockwise
Set Home flag
Turn off amber indicator & turn on green tower indicator to signal system ready
Step 2 – Develop a logic algorithm for each defined step in your reset routine.  In this case, an algorithm is simply a text-based procedure (written definition) for the logical solution for each step.

Step 3 – Develop ladder logic that will satisfy each individual logic algorithm defined for your reset routine.  Transition the logic developed in your algorithm to ladder logic.  This step can be completed on paper or starting a new project in Studio 5000.  If using Studio 5000, remember to open your template file and rename the project Lab 6.

Step 4 – Before “testing” your newly created logic, employ a strategy to force your logic to completely resolve one step before proceeding to the next.  This strategy will ensure no unintended interaction between automation components during the positioning movements.  One simple method of accomplishing this action is to employ a logical flag or “step” bit to condition the rung under investigation.

Step 5 – Consider employing a diagnostic methodology in your logic to allow you to operate your ladder logic one rung or step at a time.  Similar to using logical step bits, diagnostic “test” bits allow you to manipulate the logic scan in order to analyze each rung or step individually and make corrections as needed.  Once you are satisfied with your rung by rung diagnostic logic test, you can simply activate all test bits used in the routine to reactivate the normal logical scan sequence.  This will then allow you to analyze the entire logical sequence as a logical routine within your program.  Once you are satisfied with the logical sequence created, simply delete the test bits before deploying the routine for production.

Step 6 – One other consideration is to employ delay timers in your logic to smooth component movement and interactions. Integrating one quarter or one half second delays between component movements will give your logic a smooth, polished look when operating.

3.  Develop a production subroutine

Develop a production routine that will systematically control the workstation through a single production sequence.

Step 1 - Define individual steps that will constitute a production cycle. 

Example list of steps for the production subroutine:

Eject box & hold in position
Transfer box to conveyor steps
Verify box ejected
Lower vacuum head
Start vacuum
Extend vacuum head
Capture box
Raise vacuum head
Retract vacuum head
Rotate vacuum head CW
Transfer vacuum head to conveyor
Extend vacuum head
Disable vacuum – time delay done
Start conveyor
Stop conveyor when box passes exit prox
Step 2 – Develop a logic algorithm for your production routine.  In this case, an algorithm is simply a text-based procedure (written definition) for the logical sequence of steps that constitute a production cycle.

Step 3 – Develop ladder logic that will satisfy your logic algorithm.  Transition the logic developed in your algorithm to ladder logic.  This step can be completed on paper or editing your Lab6-Home project using Studio 5000.  If using Studio 5000, remember to open your Lab6-Home project file and rename the project Lab 7.

Step 4 – Before “testing” your newly created logic, employ a strategy to force your logic to completely resolve one step before proceeding to the next.  This strategy will ensure no unintended interaction between automation components during the positioning movements.  One simple method of accomplishing this action is to employ a logical flag or “step” bit to condition the rung under investigation.

Step 5 – Consider employing a diagnostic methodology in your logic to allow you to operate your ladder logic one rung or step at a time.  Similar to using logical step bits, diagnostic “test” bits allow you to manipulate the logic scan in order to analyze each rung or step individually and make corrections as needed.  Once you are satisfied with your rung by rung diagnostic logic test, you can simply activate all test bits used in the routine to reactivate the normal logical scan sequence.  This will then allow you to analyze the entire logical sequence as a logical routine within your program.  Once you are satisfied with the logical sequence created, simply delete the test bits before deploying the routine for production.

Step 6 – One other consideration is to employ delay timers in your logic to smooth component movement and interactions.  Integrating one quarter or one half second delays between component movements will give your logic a smooth, polished look when operating.
