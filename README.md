# Lottery Odds Analysis

*This analysis was done as part of dataquest practice.*

The lottery is relatively inexpensive. In the US, the usual price people will pay for a lottery ticket is in the range of $2-$5, with the promise of a huge jackpot prize. Naturally, it is seen as a socially acceptable form of gambling. However, for a minority, this form of entertainment escalate into an addiction.

In this analysis, we will assume the role of data analyst medical institute that aims to prevent and treat gambling addictions. The institute wants to build a dedicated mobile app to help lottery addicts better estimate their chances of winning. The institute need us to create the logical core of the app and calculate probabilities to support the engineer when building the app.

We will focus on the 6/49 lottery and build functions that enable users to answer questions like:

    What is the probability of winning the big prize with a single ticket?
    What is the probability of winning the big prize if we play 40 different tickets (or any other number)?
    What is the probability of having at least five (or four, or three, or two) winning numbers on a single ticket?

We will also use historical data coming from the national 6/49 lottery game in Canada as a bonus. The data set has data for 3,665 drawings, dating from 1982 to 2018.

In the 6/49 lottery, six numbers are drawn from a set of 49 numbers that range from 1 to 49. The drawing is done without replacement, which means once a number is drawn, it's not put back in the set. Which means we will have to perform a lot of factorial and combinations calculations.

