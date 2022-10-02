---
title: "CSAM"
draft: true
---




#### An inspiring conversation with Mr. L

A scribbled note on the call with Mr. L, at CSAM, June 14th, 2019. Notes are mostly on my own thoughts and answers, but the questions from Mr. L are enlightening enough in their nature. 



**C**: How do you describe your specialty? How do you sell yourself?

**S**: With a mixed background in quantitative analysis and investment management, I've built up a good sense about exploring hidden characteristics, connections, and patterns of asset returns and risk profiles from standpoints of both an economist and a mathematician. I can provide a well-tailored portfolio construction solution with strict optimality under a specific customized demand from the client, including not only clearer factor exposure structure and better robustness, but also efficiency in various costs and frictions. The experience in research enables me to solve problems more efficiently, identify potential tradeoffs between accuracy and structural risks, as well as sophisticated analysis and intuitively straightforward underlying logic. 



**C**: With that being said, how's your understanding of the industry, the investment world, and the research methodology?

**S**: Many people have argued that as the data science, machine learning, and deep learning techniques are evolving rapidly, the market is getting very effective and complete so offering constant and consistent outperformance is almost impossible, and then it's hard to make money anymore. I partly disagree with that. Supported by the advanced tech, people are processing and digesting new information faster, almost instantly, yielding the fact that it's indeed very hard to explore a robust new alpha signal. However, there are still multiple sources of structural alpha from behaviour bias and policy structure. The underlying source of it is that investors in the market are actually solving different optimization problems, even if they don't have an explicit math form defined, with different risk tolerance, objective functions, and horizons. Hence, even when the total market seems to be very effective, as an investor one can still harvest opportunities from gaps between various solutions people pick. Once the focus is on the latter one, we can almost avoid the modeling risk of trying to predict the expected return, switch to modeling the covariance structure and reaching better optimality. Since some overall risks are born by the aggregate market and doing market timing is extremely difficult, structural alpha backed by ample diversification seems to be a better choice than a traditional alpha approach. 



**C**: Can I take what you said in the following way: there are two layers of business, one is getting gains in a zero-sum game, another is more like an insurance business where you basically taking some risks others won't take at a particular moment?

**S**: Exactly. In a microenvironment, the speed of processing information is very high now, so in the zero-sum game the chance to constantly win is small. However, people will not reach the optimal point in an infinite-horizon risk-adjusted return maximizing optimization problem, instead, they will pick a suboptimal solution simply because they have some bias in views on the future. Some are evaluating the properties of the factors inaccurately, or modeling the interactions in the wrong way, then they will end up having a wrong understanding of the true characteristics of their portfolios. This is ok since they may have different risk tolerance or different risk measures, and actually the true risk structure is invisible and impossible to capture completely, nobody can perfectly answer the question "what's a specific factor like size, quality, momentum?" all of the so-called factors is just a good-enough approximation of the return driver. What matters is the fact that we all have different solutions, as long as this exists, the market is profitable. 



**C**: I know you are very much in the smart beta side, but I'd like to challenge you a bit more about the alpha side, the zero-sum game part. Let's take weather forecast as an example, it's a hard problem for a long time, but people are making huge progress solving it, compared to making predictions in financial markets, which one do you think is harder?

**S**: Financial markets are way harder I think. Following a normal logic chain, to make predictions we need to understand the variables' nature of randomness, which is built upon the repeatability of experiments. For weather, it's reasonable to say a local weather status is the same as the weather conditions in many other places, and we have availability to a massive dataset of observations, carrying enough information for future, given the assumption of repeatability, which is reasonable in this context. However, for financial markets, every day is pretty much a new day, we are having a new set of information, the investors are having different views and actions, the dimensions of variables is too many for us to argue that what's happening tomorrow is comparable to some days in the past. From this standpoint, we are facing unmeasurable structural risks when we are making assumptions, though they can't help us to connect the next days with the past days and make the problem addressable. Having said that, there are still way too many parameters we need to describe the market condition are impossible to estimated. (Dice example) And last but not the least, an even more challenging problem is the availability of the data, we couldn't do repeat experiments, and we are limited by the length of the time period and the total number of observable variables. All of these make the problem very hard. The difficulty is mainly from the invalid information set. 



**C**: So you are basically arguing there are two obstacles: an inadequate state representation and a limited time period. However, I would argue that it's not necessary to incorporate time as part of the state representation. In financial markets, time and dates are not a reasonable unit of measurement like what's in physics, what's happening in a day might be comparable to what happened in a month. Basically the rate of processing information and making reactions can be very much different in different timestamps. 

**S**: I agree, but we need to make observations along the way, and we can pick a reasonably low time interval to get observations as long as they are legitimately different. From a perspective of sampling, equally spaced points are necessary, but considering what you've said, an additional variable indicating the nature of information awareness and the efficiency of reflecting updated info set in prices could be a good idea. However, this rate is almost impossible to obtain and we can only pick a proxy approximation for that, which is ok in a mathematical sense, but in practical applications, we will have more hyperparameters and the interaction of such with other analytical components might be tricky to explain. 









