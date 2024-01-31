CC ON Bottom 4 Green = SWITCH(TRUE(),
'Metrics Table'[Metrics YTD Bottom]>=[Metrics Target Bottom] && 'Metrics Table'[Metrics YTD Bottom]<[Metrics Target Bottom Positive],6,
'Metrics Table'[Metrics YTD Bottom]<[Metrics Target Bottom],5,
'Metrics Table'[Metrics YTD Bottom]>[Metrics Target Bottom],4)
