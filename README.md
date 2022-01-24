# Voter Fraud misinformation Reduces Confidence in Electoral Integrity

This project is a replication for: [The Effects of Unsubstantiated Claims of Voter Fraud on Confidence in Elections](https://www.cambridge.org/core/journals/journal-of-experimental-political-science/article/effects-of-unsubstantiated-claims-of-voter-fraud-on-confidence-in-elections/9B4CE6DF2F573955071948B9F649DF7A). The data for replication are available on [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/530JGJ).  

The replication is structured as follows, 

# Abstract 
This project is a replication for "[The Effects of Unsubstantiated Claims of Voter Fraud on Confidence in Elections](https://www.cambridge.org/core/journals/journal-of-experimental-political-science/article/effects-of-unsubstantiated-claims-of-voter-fraud-on-confidence-in-elections/9B4CE6DF2F573955071948B9F649DF7A)". Through a survey experiment with a sample of 4,283 U.S. respondents, @berlinski2021effects find that voter fraud misinformation reduces public confidence in eletoral integrity. I performed Ordinary Least-squares regression regression analyses to replicate their research, and my results show consistency with their findings. However, I also find that voter fraud misinformation increases public confidence in elections if they identify as Democrat, suggesting a potential "backfire effect" among partisans when they are contantly exposed to counter-belief fact-checked evidence.   

# Introduction
Illegal election interference and targeted disinformation campaigns on voter fraud have raised concerns among many about the potential for political actors and foreign powers to sabotage the integrity and trustworthiness of democratic institutions. By conducting a survey experiment with 4,283 U.S. adults following the 2018 US elections, they find that exposure to misinformation regarding voter fraud reduces confidence in election results. In addition, corrective effects on unfounded voter-fraud allegations are limited, suggesting that fact-checking is not a powerful tool to rectify misconceptions as researchers hypothesized. 

I this paper, I sought out to replicate @berlinski2021effects's work published in 2021. The main goal of this replication is twofold: (1) To re-examine the experimental results in order to testify if exposure to unfounded voter-fraud claims reduces people's confidence in the 2018 elections; (2) To explore other potential variables to explain how misinformation regarding voter fraud reshapes political attitudes and behaviors. The rest of this paper is structured as follows: In the Method section, I re-examined the survey design and treatment conditions; In the Results section, I specified the linear regression model and presented the results generated by the model; In the Discussion section, I discussed conclusions and findings generated by the replication, focusing on the validity and reliability of the research approach. 

# Method
I this replication, I used OLS to fit the data. In this section, I specified the model and re-examined the relationships between exposure to voter fraud misinformation and party identification. 

# Results 
The results of the regression models show a statistically significant relationship between public trust in elections and misinformation about voter fraud claims. "Low dose" and "High dose" of voter fraud messaging both reduce confidence in electoral integrity (p<0.01). Interestingly, in the "Correction" treatment, where respondents received both "low dose" claims and corrections for such claims, their trust in elections still decreased (p<0.05). This suggests that the effects of fact-checking maybe limited after exposure  to voter fraud misinformation. In the model that contains the interaction term of party identification, the results are similar. Messaging dose and partisanship are still negatively correlated to confidence in elections. The interaction term "party" also effectively predicts the relationship between the dependent and independent variables. The effect of high dose voter fraud misinformation increases by 0.25 for every unit increase if the respondent identifies as Democrats (p<0.001). In addition, the effect of low dose voter fraud misinformation and corrections increases by 0.19 for every unit increase if the respondent identifies as Democrats (p<0.005).

# Discussion  
In the Discussion section, I confirmed that my results are generally consistent with the original study conducted by @berlinski2021effects: Exposure to voter fraud misinformation reduces people's confidence in elections. However, it is also noted that fact-checks do not reduce misconceptions of voter fraud, this worrying finding suggests the limited effects of fact-checking. 

In the model including the interaction term, we can observe the interaction effects between party identification and doses of exposure to allegations of voter. For the high dose treatment condition, exposure to misinformation about voter fraud increases confidence in elections if one identifies as Democrats. However, the same effect was not observed for the Republicans. This finding seems to contradict our prior assumption because it implies that the more misinformation Democrats receive, the more likely they gain trust in elections. The theory of "Backfire Effect" may be a framework to explore for an explanation for such observations. Accordingly, the backfire effect theory suggests that people reinforce their prior beliefs when they are constantly expose to misinformation. 
