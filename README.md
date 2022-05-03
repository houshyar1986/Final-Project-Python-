# Final-Project-Python-

## Inroduction

Finance theory suggests that capital markets reflect all available information about firms in the firms' stock prices. Given this basic premise, one can study how a particular event changes a firm's prospects by quantifying the impact of the event on the firm's stock. Finance scholars have developed the event study methodology to perform this type of analysis - in its most common form, with a focus on stock returns, in less used forms, with a focus on trading volumes and volatilities.
Return event studies quantify an event's economic impact in so-called abnormal returns. Abnormal returns are calculated by deducting the returns that would have been realized if the analyzed event would not take place (normal returns) from the actual returns of the stocks. While the actual returns can be empirically observed, the normal returns need to be estimated. For this, the event study methodology makes use of expected return models, which are also common in other areas of Finance research. 

The market model is the most frequently used expected return model. It builds on the actual returns of a reference market and the correlation of the firm's stock with the reference market. Equation (1) describes the model formally. The abnormal return on a distinct day within the event window represents the difference between the actual stock return (Ri,t) on that day and the normal return, which is predicted based on two inputs; the typical relationship between the firm's stock and its reference index (expressed by the α and β parameters), and the actual reference market's return (Rm,t).
ARi,t=Ri,t−(αi+βiRm,t)(1)
Such an analysis performed for multiple events of the same event type (i.e., a sample study) may yield typical stock market response patterns, which have been at the center of prior academic research. Typical abnormal returns associated with a distinct point of time before or after the event day are defined as follows.

AAR=1N∑i=1NARi,t(2)

To measure the total impact of an event over a particular time period (termed the event window), one can add up individual abnormal returns to create a cumulative abnormal return. Equation (2) formally shows this practice. The most common event window found in studies is a three-day event window starting at t1=−1 and ending at t2=1.
CAR(t1,t2)=∑t=t1t2ARi,t(3)

## Significance Tests for Event Studies

The abnormal and cumulative abnormal returns from event studies are typically used in two ways. Either they are used as dependent variables in subsequent regression analysis or they are interpreted as such. 
This latter direct interpretation seeks to answer the question of whether the distribution of the abnormal returns is systematically different from predicted. In the relevant literature, the focus is almost always on the mean of the distribution of abnormal returns, and, specifically, one seeks to answer the question of whether this mean is different from zero (with statistical significance).
The answer about statistical significance is given by means of hypothesis testing, where the null hypothesis (H0) states that the mean of the abnormal returns within the event window is zero and the alternative hypothesis (H1) states the opposite. Formally, the testing framework reads as follows:
H0: μ=0
H1: μ≠0

## Why this topic?

1.	Apply different features of Python such as:
a.	Getting data from API
b.	Financial calculations
c.	Statistical calculations
d.	Returning charts, tables, and messages
