******************************************************************************************
***				About Volume Control				       ***
******************************************************************************************
Since Volume Control logic is implemented in PMOS following is volume agin:

	I/P-->LEVEL-->GAIN
	000-->HHH---->0.98
	001-->HHL---->0.85
	010-->HLH---->0.72
	011-->HLL---->0.59
	100-->LHH---->0.46
	101-->LHL---->0.33
	110-->LLH---->0.20
	111-->LLL---->0.07

The observed distortion in output signal is due to absence of Pre-Amplification stage.
The Noise in raw signal is not rejected and is amplified accordingly.This can be improved
on.
*****************************************EOF**********************************************