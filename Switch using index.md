Master YTD Switch = var selection = SELECTEDVALUE('Metric Master'[Index])
var master = 
SWITCH(TRUE(),
selection= 1, [QSE YTD],
selection = 2, [Quality YTD],
selection = 3, [Safety YTD],
selection = 4, [Environment YTD], BLANK())
return
master/100
