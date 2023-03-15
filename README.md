# BoomBikes Demand Analysis and Prediction
> Bicycle-sharing system, bike share program,[1] public bicycle scheme,[2] or public bike share (PBS) scheme,[3] is a shared transport service in which bicycles are made available for shared use to individuals on a short-term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" and return it at another dock belonging to the same system. Docks are special bike racks that lock the bike, and only release it by computer control. The user enters payment information, and the computer unlocks a bike. The user returns the bike by placing it in the dock, which locks it in place. Other systems are dockless.


## Table of Contents
* [Problem Statement](#problem-statement)
* [General Info](#general-information)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement

### Business Understanding

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

### Business Goal:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

### Business Risk:

- No or less demand and high supply
- High demand and no or less supply

### Requirement:

- Which variable are significant in predicting the demand for shared bikes
- How well those variabe describe the bike demands 

## General Information
- Steps for crreating a linear regression model :
<ol>
    <li>Data Visualization</li>
      <ol>
        <li>Perform EDA to understand various variables.</li>
        <li>Check the correlation between the variables.</li>
      </ol>
    <li>Data Preparation</li>
      <ol>
        <li>Create dummy variables for all the categorical features.</li>
        <li>Divide the data to train & Test.</li>
        <li>Perform Scaling.</li>
        <li>Divide data into dependent & Independent variables.</li>
      </ol>
    <li>Data Modelling & Evaluation</li>
      <ol>
        <li>Create Linear Regression model using mixed approach (RFE & VIF/p-value).</li>
        <li>Check the various assumptions.</li>
        <li>Check the Adjusted R-Square for both train & Test data.</li>
        <li>Report the final model.</li>
      </ol>
</ol>
- Data Set : day.csv 
