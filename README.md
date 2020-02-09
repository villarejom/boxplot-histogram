Freq <- c(0.6, 0.3, 0.4, 0.4, 0.2, 0.6, 0.3, 0.4, 0.9, 0.2)
Bloodp <- c(103,87,32,42,59,109,78,205,135,176)
First <- c("bad","bad","bad","bad", "good","good","good","good","NA","bad") 
Second <- c("low", "low", "high", "high", "low", "low", "high", "high", "high", "high")
Finaldecision  <- c("low", "high", "low", "high", "low", "high", "low", "high","high", "high")
data.frame(Freq, Bloodp, First, Second, Finaldecision) # create data frame
d <-data.frame(Freq, Bloodp, First, Second, Finaldecision) #assign d to data.frame
str (d) verify the structure of data.frame
hist(d$Freq)
> # Histogram with options
> hist(d$Freq,
+   breaks = 7,  # Suggest number of breaks
+   main   = "Histogram of Frequency",
+   ylab   = "Frequency",
+   xlab   = "Integer",
+   border = NA,  # No borders on bars
+   col    = "#CD0000"  # red3
boxplot(d$Freq)
boxplot(d$Bloodp)
Second <-c(0, 0, 1, 1, 0, 0, 1, 1, 1, 1) #manually enter values for Second ANd Final Decision so they will be recongized as numeric  High =1 Low =0
Finaldecision <- c(0,1,0,1,0,1,0,1,1,1)
hist (Second)
boxplot (Second)
hist (Finaldecision)
boxplot (Finaldecision)
