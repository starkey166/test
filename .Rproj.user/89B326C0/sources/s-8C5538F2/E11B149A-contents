#Lesser Prairie Chicken Regression

lpc=read.csv("lpcdata.csv",h=T)
lpc<-read.csv("lpcdata.csv",h=T)
lpc
head(lpc)
tail(lpc)
names(lpc)
lengthvmass=lm(mass~winglength,data=lpc)
summary(lengthvmass)
plot(mass~winglength,data=lpc)
plot(mass~winglength,data=lpc, col="red",pch=19,
     xlab="Wing length (mm)", ylab="Mass (g)",main="LPC Wing length vs Mass")
abline(lengthvmass, col="blue")