# TWC Slack AI Integration App
*Name is still being workshopped*

## Vision

The main goal is an intuitive slack application with multiple commands that increases productivity. When opening a channel, the user would be able to enter a command in the forward slash format to initiate a task. 

One command would be `/action-items` in the chat bar, a modal would then pop up and the user could select how far back they want to analyze, 1-day, 1 week, etc. The goal is to make it different from the simple summarization slack has, and maybe have more customizability. Simple action items and a check next to them if complete or not would be ideal. 

Another Command would be `Sentiment Analysis` which someone could initiate to monitor the current health of the chat. It is currently undecided how the final flow would quite occur. Will start on an individual channel level. From there we could decide if we want to create some sort of dashboard that shows the health of each of each channel based purely off of chat messages. Once we have a POC, we will determine how viable a full implementation would be. 

The final implementation would be some sort of RSS feed analysis tie in. Every time an entry comes through the feed, a rating of how relevant said article is to what we are working on would populate. This would be useful in filtering out the bad articles from the good. 

A stretch goal would be to tie these queries into a TWC-specific LLM that is local and specifically trained on everything Troy Web. This would eliminate the confidentiality issue, and open up a multitude of larger applications. 

## Stack
- Javascript  
  *Largely decide as I go*

## Goals
- Implement `/action-items`  
- Get More familiar with llm querying and training.  
- Get more familiar with working with Slack API  
- Provide value from a productivity perspective  
- Beat the cookie cutter slack AI summarization!!  
- Gain experience in building llms (stretch)  

## Milestones 

**Milestones for September**  
- Finish Research and onboarding required to start project  

**Milestone for October**  
- RSS Implementation done  

**Milestone for November**  
- Have an dash that pops up in slack and some test queries set up for action-items command  

**Milestone for December**  
- Done with action items and started up sentiment analysis  
- Sentiment analysis POC and decision on viability  

## Potential Hurdles to Clear Up
- confidentiality of messages  
- would be running this through an LLM, leads to questions about what is OK and what is not to put through.  
- Turn off training on our queries?  

## Current Team Members (Name,email,credit-amount)
- Joe Fodera, foderj@rpi.edu, 4 credits (Project Lead)  
