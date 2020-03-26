---
title: "How Can Participants Make More Efficient Decisions in Peer-to-Peer Sharing Economy?"
subtitle: "SYS6014 - Decision Tool Project: Refined Concept Note, Includng Initial Formal Model"
author: "Ian Liu"
date: "2/05/2020"
output: pdf_document
---



## Project Introduction & Description

As the concept of sharing economy has been globally proved to be efficient, a relatively new economic model has been invented and introduced, which is to use time as a tradable currency, to allow one participant with specific skills to trade hours of work with another participant with different skills. During the entire transaction, although physical money is replaced by working hours, both parties of the transaction still has achieved their objection of exchanging services or needs. This new type of economic model is call time-banking.

For example, Jack will be out of town over the weekend for a conference and needs someone reliable and trustable to take care of his child. Maria, Jack’s neighbor, is a professional registered nurse at the local children’s hospital and has free time over the weekend. However, due to the nature of work, Maria must be on night shifts 4 times a week, so she hardly finds a proper time window to mow her lawn. In fact, Jack is getting a 2-day break from work when he returns back from the conference, and he can mow the lawn at Maria’s property as a return, in exchange of Maria’s time for taking care of his child over the weekend. 

There actually have been a few successful platforms developed that help the participants of time banking to look for potential partners. However, things just become more complicated as the number of participants is getting larger, which means that each participant must make a decision when multiple matches have become available for them to confront. Let’s get back to Jack and Maria’s case. What if there are multiple help requests that Maria could accept for the weekend? What if there are multiple babysitters available in the neighbor that Jack gets to choose? Here comes a decision-making problem.

## The Decision Problem

In this project, the decision-maker is someone who has published a request on a peer-to-peer time-banking platform and has received multiple offers. As the time window is closing, this person confronts a situation where they must make a final decision as soon as possible, and they wish the platform system could help them to select the best match.

The set of options is hard to define due to the complexity and diversity of each participant's profile. And the system would calculate a weighted expectation value for each participant based on the available information provided in their profile.

The stakes of the decision vary depending on the nature of each decision. However, we wish to find the best match, or the final decision with the highest expectation value, for participants to choose. Poorer decisions will definitely cause issues such as inequality and resentment. Since the physical money does not get involved in the transaction, it's pretty hard for people to intuitively evaluate work with working hours. However, it is definitely not going to work out if Maria babysits Jack's child for the entire weekend, but Jack only mows Maria's lawn for 5 minutes.

## The Predictive Tool

1. What information does your chosen predictive tool provide?
\newline 
The predictive tool chooses the best match for a user by letting them fill out a survey-like form that contains necessary information/questions to make a decision, then the algorithm locates the option with the highest weighted score, based on Bayesian decision theory.
\newline 

2. How will the decision maker use the information generated by this tool to make better decisions?
\newline 
When a user is publishing a request on the platform, they must agree to exchange services with time hours, but not the traditional money in the future. Having said that, they would need to provide all the skill sets, requirements and demands when they set up their profiles. And the algorithm will match them based on the information that they've provided in their profiles.

## Other Related Questions

1. In what units are payoffs measured?
\newline
Payoffs are measured by timing hours, details will be provided in the future write-ups.
\newline 
2. Programming language?
\newline
In order to prevent reinventing the wheel, I'd choose to use Python or R to complete this project.
\newline
3. The rest of the questions are going to be very helpful for me to complete this project However, unfortunately, I don't have answers for them yet.
\newline
What are the uncertain state variables that influence the value of payoffs?
\newline
What is the range of possible values of these variables?
\newline	
What analytic technique(s) will you use to estimate the values of these uncertain state variables?
\newline
What data will you use in this estimation? Are you sure you can gain access to these data?