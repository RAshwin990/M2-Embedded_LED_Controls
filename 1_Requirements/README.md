# Requirements

## Introduction
   LED controlling is a simple project in Embedded C progamming. There are several ways to control a LED circuit. You can control one using relays. You can use transistors. Or you can use components like an inverter, a 555 Timer or a microcontroller. Here a swtich is used to blink the two LED using ATmega328 microcontroller.

## Objective
   The main objective is to control the led using ATmega328 and a switch is used to control two LED's.

## Components used
1. ATmega328   
2. Two LED 
3. Switch
4. Resistor

## Software used
1. SimulIDe
2. Visual Studie Code

## Research
   Atmega328 is an Atmel microcontroller, which is used in Arduino UNO board and such. It has 28 pins in total. It has 3 Ports which are named as Port B, Port C and Port D. Port C is an analogue Port and it has six pins in total. So, in simple words, ATmega328 has 6 analogue pins. Port B and Port D are digital ports and have 7 pins each. So, in total ATmega328 has 14 digital pins. It also supports Serial Communications, we can perform serial communication via Pin 2(RX) and Pin 3(TX). It also supports SPI Protocol.

<img width="457" alt="Screenshot 2021-12-01 at 8 24 00 PM" src="https://user-images.githubusercontent.com/94396238/144258251-fbeb07e4-0d7f-4378-ab41-bc5fb1c4a8f7.png">


## Features
    1. It can turn off the LED's when switch is in off state.
    2. It can turn on the LED's when switch is in on state.

## 4W's and 1 H's
   ### Why
    1. To blink two LED's using a switch with ATmega328.
    2. To understand basic concepts of ATmega328.
   ### Where
    1. It can be used in many places.
    2. It can be used for understanding purposes in schools and colleges.
   ### Who
    1. It can be used by students to learn about ATmega328.
    2. It can be used by anyone who are new to embedded programming language.
   ### When
    1. People are trying to learn an embedded programming language.
    2. It can be implemented anywhere where there is a need to control LEDs via software.
   ### How
    1. By using software to exceute the program.
    2. By uploading the program to ATmega328.

## SWOT Analysis
   ### Strengths
    1. Simple to understand and implement.
    2. Cost effective.
   ### Weakness
    1. Very simple concept that is useful only for learning purposes.
   ### Opportunities
    1. This program can be made more complex by adding more components and features.
   ### Threats
    1. Advanced programs that are simple enough for beginners are already available.

## High Level Requirements
| Id    	| Description     	| Status      	|
|-------	|-----------------	|-------------	|
| HLR_1 	| Microcontroller 	| Implemented 	|
| HlR_2 	| Swtich          	| Implemented 	|
| HLR_3 	| Two LED         	| Implemented 	|
| HLR_4 	| Software        	| Implemented 	|

## Low Level Requirements
| Id    	| Description              	| Status      	|
|-------	|--------------------------	|-------------	|
| LLR_1 	| ATmega328                	| Implemented 	|
| LLR_2 	| Swtich                   	| Implemented 	|
| LLR_3 	| Two LED                  	| Implemented 	|
| LLR_4 	| Visual studio & SimulIDE 	| Implemented 	|
