# driver-state-monitor_aberrant-eyes
DSM 1 functions by simultaneously processing eye-behaviour data through three separate analyses to detect non-mutually exclusive sub-states of driver distraction, drowsiness, and/or cognitive overload. DSM 1 consequentially triggers and raises a general elevated detection of off-nominal driver eyes based on the presence of any of these compromised driver states.

DSM 1 is provided as a stand-alone simulink module (MATLAB R2014b 32-bit) = AberrantEyes6.slx
note: the first "Extract Eye Data MATLAB Function" block was designed for the Smart Eye DR120 eye tracker but could be modified to work with your own UDP eye tracker output as needed

An example of integration is provided with PreScan driving simulation = W6_cs.mdl/Audi_A8_1
