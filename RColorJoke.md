## We are going to create a example of how R works with colors

x<-rnorm(100000, mean=1000, sd=10) ## 100000 samples of a normal with mean=1000, and standard desviation =10

plot(x, col=rainbow(100000))  ## We create a graphic with 100000 points in 100000 different colors that appear like if they were a rainbow

