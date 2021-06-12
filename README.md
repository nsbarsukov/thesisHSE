# Elections in UK Parliament in 2015 and 2017: Reasons for Voting Despite Citizens Preferences 
The empirical part of thesis (bachelor degree, Higher School of Economics).

# Research proposal

The main goal of this study is to prevent the scientific community from defining any contradiction between ideological affiliation and actual voting of citizens as a strategic voting. Within the scope of this paper, such contradiction is a complex system of interaction between external and internal factors (including mentioned explanation) with different levels of significance. The article answers the question as follows: which factors have more influence on the decision to vote despite the preferences on the example of UK elections in parliament in 2015 and 2017. The main empirical method is a logistic regression. The author uses post- and pre-Brexit period to take the possible impact of an external factor into account before suggesting an optimal statistical model, which is capable to detect the mentioned type of contradictions with a high level of precision.


## Introduction
### Background
The results of every election, especially in democratic countries, are valuable source of information for politicians and scientists which can reveal any change in voters’ thoughts that lead to the reconstruction of the whole party system. M. Pedersen (1979) conducted his research on the basis of this assumption. He was the first who described the calculation mechanism of electoral volatility index (afterward, that index was named after him). Pederson (1979) wrote that electoral volatility is a «net change within the electoral party system resulting from individual vote transfers» (p. 3). Pedersen index is widely used in the research environment and became the most reliable indicator of the party system’s change in every country.
Why does volatility get in the spotlight among researchers? Low volatility is the indicator of stability of voters' preferences. K. Bertoa (2017), has noted the high significance of volatility as indicator of a weakness of democracy, hence wrote: «Volatility measures matter not only for studies of the survival of new democracies but also for research examining the health and development of longstanding democracies which have witnessed the growth of new, anti-establishment parties and experienced “earthquake” elections» (p. 143). Therefore, it is expected that in stable democracies there will be a low value of volatility at least for several decades, and the reverse process can be interpreted as a crisis of the regime. Consequently, if we take the case of Great Britain (which, according to Polity IV, is a mature democracy for at least 50 years (“Authority Trends”, n.d.) and is one of the most economically developed countries in the world), the low level of volatility or the closest value to it should only reinforce the abovementioned reasoning.
As noted by Svante Ersson, there are small discrepancies in the calculations of the electoral volatility index by various researchers. However, there is no doubt that the UK is the leader of the lowest volatility indicator since the Second World War (6.28%) (Ersson, 2012). If one looks at the wider chronological frame (1918-2017), then Casal Bértoa (2016) still notes that Britain’s electoral volatility does not exceed 10% on average, which classifies the country in the category of low volatility (as instance, countries from high volatility category have at least 4 times more percentage of electoral volatility than the UK does).
However, if we take the results of the polls conducted by the «British Election Study» (the analytical center for the study of electoral behavior in the UK), right before the early parliamentary elections in 2017, we will find empirical observation (which forms a relevance of this paper) that does not fully stand in compliance with the general picture - more than 20% of respondents (representative sample) voted for other parties, with which they did not identify themselves (British Election Study, n.d.) with. And if we exclude those citizens who have no position on these issues or simply do not want to participate in the elections from the sample, then use extrapolation, we will find that every 4th British voter, who had a strictly formed ideological party affiliation, has voted contrary to their preferences in the parliamentary elections in 2017. This fact contradicts the abovementioned arguments about the low volatility of voters in the UK. In spite of having almost constant political preferences, voters violate it, thus this state of things creates an unresolved scientific puzzle.
### Problem Statement
The research question is structured as follows: "What is the reason for citizens' voting despite its preferences in the UK parliamentary elections in 2015 and 2017?"
The purpose of the study is to find several other factors that can explain the conflict of non-coincidence of party affiliation and actual voting.
### Professional Significance
This issue has been already raised earlier in the literature: researchers have observed the effects, described earlier in Introduction, on the other data and bearing in mind other chronological frameworks. However, a common feature that unites many authors, who have discussed the problem of “insincere” (despite their ideological preferences) voting, is that they have took the effect of strategic voting for granted (Lanoue & Bowler, 1992; Spirling & McLean, 2007; Abramson et al, 2010; Riera, 2016). The scientific relevance of this work lies precisely in the fact, that not any discrepancy between the party affiliation of the voter and his/ her true vote is interpreted as a strategic vote but must henceforth be “separated” from other explanatory phenomena first. This paper assumes that a vote, contrary to one’s preferences, not only can be a strategically pragmatic (anticipating the expected election results), but also value-rational (based on a hierarchy of political values).

## Literature Review
In literature, several theoretical approaches, which can explain the discrepancy between the political orientation of the voter and the political orientation of the party/ candidate for which he/ she votes, can be found. 
Although this work does not aim to identify any vote contrary to the true preference as the strategic voting, it is also impossible to completely reject this theory, since it may turn out as the only correct answer. Strategic voting (or ‘tactical/insincere voting’) is a phenomenon when a voter, evaluating the preliminary results of elections, does not vote for his/ her most preferred party, expecting that party’s chances of success are minimal and his/ her vote can simply be “wasted”. Therefore, the citizen votes for one of the leaders of the election race (Franklin, Niemi & Whitten, 1994). The grounds for the birth and strengthening of this theory were prepared by the economist Kenneth Arrow with his "impossibility theorem" in 1951. In particular, the idea of streamlining by each voter (depending on their preferences, the idea of transitivity) of all candidates (Arrow, 2012) formed the basis for evidence of the inevitability of strategic voting in any electoral system by Allan Gibbard (1973): “any non-dictatorial voting scheme with at least three possible outcomes is subject to individual manipulation” (p. 587). However, besides the traditional understanding of strategic voting (when a voter is afraid of “wasting” his/ her vote), it is worth to mention another type of voting – an expressive voting: when a citizen votes not for the preferred party due to “giving a signal to its or other parties” (Franklin & Niemi & Whitten, 1994). This situation is not aimed at undermining the position of the leader (it is assumed that the voter has no doubt in the candidate’s victory), but merely shows with such a signal support in favor of the policy of some other party (so that the future winner takes this into account) (Franklin, Niemi & Whitten, 1994). The following theory, which has potential explanatory power, is “economic voting”: “voters punish or reward incumbent parties for their success in managing the economy” (Tavits, 2005, p. 286).
Finally, there is a block of literature related to the system of preferences of the electorate (‘belief system’). There is a controversy over how people vote with no correct answer. Some argue about the personalization of politics, when voters view all possible options for individual candidates and party leaders and then decide (Karvonen, 2010). It means that voters choose their political elite/representatives who will perform accordingly to the voters interests. The second approach is program-oriented (issue-based), which already asserts the primacy of ideology and views on specific political policies (candidates and parties' goal is not just to attract the attention of voters, but the parties and the candidates promote a program that can attract supporting electorate) (McAllister, 2016). The second approach will be taken as the basis for analyzing the phenomenon of party affiliation and actual voting. The idea is based on the fact of the significance of ideological views and preferences of the electorate regarding a particular policy, which leads to a greater involvement of the electorate in politics and the formation of a political participant represented by each voter (citizens choose not a candidate, who has a position on a particular issue, but they are looking for the candidate, who is as close as possible to his/ her convictions). P. Sabatier and C. Weible (2007) wrote about the three-step hierarchical structure of the worldview system. At the first stage, there are “deep core beliefs”, which «involve very general normative and ontological assumptions about human nature [...] the traditional left/right scales operate at the deep core level” (p. 194). The next stage is “policy core beliefs”, which “is applications of deep core beliefs that span an entire policy subsystem” (p. 194). The final stage is “secondary beliefs”, which covers even narrower issues than the previous stages. The violation of the hierarchy (when secondary beliefs become more significant than common basic ones) can be an explanation of why voters voted contrary to their preferences. This is especially interesting to trace in the presence of the so-called “internal shock' (Sabatier & Weible, 2007) — Brexit.
Based on the described theoretical framework and literature review, the following hypotheses are formed:

- H1: UK citizens voted against their preferences because their true preferences are small parties that have a small chance of success;
- H2: Citizens of Great Britain voted contrary to their preferences because they were confident of the victory of their party, but they wanted to give a signal about the need to consider the specific policies of the other party
- H3: UK citizens voted against their preferences to punish the ruling party for the ineffectiveness of economic policy implementation;
- H4: The voters of Great Britain voted contrary to their preferences because of the predominance of secondary beliefs over core ones after the consequences of an external shock.

## Methods
The research methodology is based on hypotheses, tested through quantitative methods via statistical approaches.
The data for the empirical part of the work will be gathered from the site of the «British Election Study», which published panel data from 2014 to 2018, divided into 14 waves (British Election Study, n.d.). Each wave is introduced by a survey of a representative sample of UK citizens (with a dimension of more than 30 thousand observations per each). In addition, there are observations with the same id (unique number), which means there are citizens participating in several waves of surveys simultaneously. The variables that are of the main interest within the context of this research are the ones concerning the ideological membership of the party and the actual vote. Other data consists of answers related to respondent satisfaction with the political and socio-economic factors in the country.
Any discrepancy in the values of the two variables allows each observation to be coded into a binary variable (where ‘1’ means the presence of discrepancy and ‘0’ means the absence of it). Based on the binary dependent variable, it is understood, that we are solving a classification problem, which means that a logistic regression is suitable. After selecting statistically significant variables, the quality of the resulting model will be assessed by predicting on a test sample and calculating statistical metrics (such as accuracy, precision, and recall). All computational processes and model building will be conducted by Python using the "Sсikit-Learn” package.


## Results Anticipated
In this paper, all UK parties’ program will be analyzed to find the most similar analog for each (party that is as close as possible to certain political party). If there is a statistical tendency to vote despite preferences for the most similar party, we will  consider that two first hypotheses are proven. Further, if such citizens neglect their party affiliation in favor of a similar larger party — we will narrow our options to the first one (pure strategic voting) and try to prove or reject it. Alternatively, if citizen’s preference is a huge party (with no doubt of success) but they vote for a smaller one — the research will conduct additional operations in order to check if there is an existence of a signal voting. One more expected result is a statistically significant correlation between citizens’ dissatisfaction about certain problem and proposed policy by the most preferred party. In this case, the study tests two last hypotheses (about economic ineffectiveness and the predominance of secondary beliefs over core ones).

## Conclusion
The final product of the research is a logistic regression model which is capable to predict new cases of citizens’ voting despite its preferences with high-performance metrics using test sample (data which has never been used before). Evaluation of the test sample helps to avoid machine learning problem of overfitting. High-performance scores – qualitative model. A qualitative statistical model is capable of giving the durable information about the importance of every used indicator. This knowledge helps to answer the main research question and find out the factors which are the most important when a citizen decides to vote contrary to his or her preferences.
