## Last Week's Accomplishments

> This last week I have implemented a basic algorithm for a demo during the presentation.  
I have also added more tests to the project to ensure the demo runs smoothly.
Afterwards, I went back to OpenCircuits proper in order to fix a bug with the Demux.
The outputs were not updating, and the output count would not change from 4.
To fix the first issue, I forced all the outputs to 0 before activating the correct port.
The second issue was more challenging.  The setOutputs method was not being called at all,
so I called it in the setInputs method. This fixed the changing, but it was still
limited to 8 outputs, when the limit should be 256. After more class diving, I learned
where the outputs get "clamped" and raised the limit.

## This Week's Plan

> This week's plan is to prepare for the presentation next week. 
This includes making and modifying the slides, preparing what to say and when, and 
and mentally preparing for speaking in front of an audience.

## Anything Blocking?

>  There is currently nothing blocking development yet.  At least nothing foreseen. 


## Notes

