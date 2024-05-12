Inputs: FastMALen(50), SlowMALen(200);

Vars: fastMA(0), slowMA(0), conditionForEntryLong(False);

fastMA = Average(Close, FastMALen);
slowMA = Average(Close, SlowMALen); 

// add more code