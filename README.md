Freq <- c(0.6, 0.3, 0.4, 0.4, 0.2, 0.6, 0.3, 0.4, 0.9, 0.2)
Bloodp <- c(103,87,32,42,59,109,78,205,135,176)
First <- c("bad","bad","bad","bad", "good","good","good","good","NA","bad") 
Second <- c("low", "low", "high", "high", "low", "low", "high", "high", "high", "high")
Finaldecision  <- c("low", "high", "low", "high", "low", "high", "low", "high","high", "high")
data.frame(Freq, Bloodp, First, Second, Finaldecision) #create dataframe
