
trainingTickets <- readRDS("/cloud/project/exercises/training-tickets.rds")
View(trainingTickets)

> # Load necessary libraries
> library(dplyr)
Error in library(dplyr) : there is no package called ‘dplyr’

trainingTickets$Sold_on <- as.POSIXct(trainingTickets$`Sold on`, format = "%m/%d/%Y %I:%M:%S %p")

trainingTickets$Sold_on <- as.POSIXct(trainingTickets$`Sold on`, format = "%m/%d/%Y - %H:%M")
first_signup <- min(trainingTickets$Sold_on, na.rm = TRUE) 

trainingTickets$Hours_from_first_signup <- as.numeric(difftime(trainingTickets$Sold_on, first_signup, units = "hours"))

hist(trainingTickets$Hours_from_first_signup, 
+      main = "Histogram of Hours from First Signup", 
+      xlab = "Hours from First Signup", 
+      ylab = "Frequency", 
+      col = "blue", 
+      breaks = 10)

alternatively

ggplot(trainingTickets, aes(x = Hours_from_first_signup)) +
+     geom_histogram(binwidth = 1, fill = "blue", color = "black") +
+     labs(title = "Histogram of Hours from First Signup",
+          x = "Hours from First Signup",
+          y = "Frequency") +
+     theme_minimal()