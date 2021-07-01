# Payment Procedure Automated Using Robotics Process Automation

Simple payment procedure using RPA state machines

## Introduction

A simple payment procedure has been automated using UIpath robotics process automation, utilizing state machine.

There are three (3) options of layout for automation – Sequence, Flowchart and State Machine.

State machine is a finite number of pre-defined states and transitions between these states. Two activities specific to state machine are State and Final State.

### About State Machine

PRO(S)
* Transitions between states offer flexibility;
* Accommodates complex processes that cannot be captured by simple loops and If statements;
* It is easier to cover all the possible cases/transitions with state machines

CON(S)
* Longer development time due to their complexity.

## Simple Payment Procedure

### Activities
* Get Initial Balance 
* Get Payment Value
  * Valid payment input but not enough balance – Deny payment (new state)
  * Valid payment input and enough balance – Make payment (new state)
* Final State 

### Main Layout

The main layout shows the complete project comprising of 3 states and 1 final state. Each feeding input and transition values to the next accordingly.

![image](https://user-images.githubusercontent.com/78843321/123934955-af51fe80-d98b-11eb-8986-30d034f6d168.png)

### Get Initial Balance

![image](https://user-images.githubusercontent.com/78843321/123935225-ecb68c00-d98b-11eb-9da3-6a9957961197.png)

### Get Payment Value

![image](https://user-images.githubusercontent.com/78843321/123935814-7a927700-d98c-11eb-87a3-44bc34e92bd5.png)

### Deny/Make Payment

![image](https://user-images.githubusercontent.com/78843321/123940455-1aea9a80-d991-11eb-8e61-254dadd8a0cc.png)


## Run Project/Results

![image](https://user-images.githubusercontent.com/78843321/123940390-0c9c7e80-d991-11eb-8bd0-8f07d546b077.png)







