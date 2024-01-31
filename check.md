Master Month Switch = var selection = SELECTEDVALUE('Metric Master'[Index])
var master = 
SWITCH(TRUE(),
selection= 1, [QSE Month],
selection = 2, [Quality Month],
selection = 3, [Safety Month],
selection = 4, [Environment Month], BLANK())
return
master/100
