# Linearity-in-R
Ramsey Test Linearity Assumption in R Studio 
#Linearity
install.packages("lmtest")
library(lmtest)

resettest (lm(Y1~X1, data_Linearity))
resettest (lm(Y2~X1, data_Linearity))
resettest (lm(Y1~X2, data_Linearity))
resettest (lm(Y2~X2, data_Linearity))
resettest (lm(Y2~Y1, data_Linearity))


