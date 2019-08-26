# Automated Micro Insurance app

## What is it?
This is a micro insurance app that allows user to keep track of their assets, and recommends micro insurance products that best fit for the assets they own. This app is created during Hack the Six 2019 Toronto.

## How to use it? 
To begin, user upload images of their assets via camera button through navigation or home page, it will take a photo of the asset and sent to AWS for OCR and object recogniztion such that user doesn't need to hand enter most of the attributes themself. 

Then an interface is presented to the user to confirm and add additional attributes if needed, once user click on the button submmit, the asset entry will be recorded in our SQL database in AWS and our prediction model will re-evauate the best insurance product that fit for that user.

At last, user will be redirect to home page where they can see their recorded assets and recommended insurances based on their assets using our prediction model.

## Technology Stack
This app utilizes Jetpack navigation, retrofit2 and okhttp3.

## App architecture
The app is architect with the mindset of single activity and multi fragments using Jetpack navigation. I was going to use MVP but given the 1.5 days development time constraint of the Hackathon it's not feasible. 

## Roles
I worked on most of the app, camera flow, submit flow, home flow, error case flows, app navigation architecture, network layers and app designs. 

@jcserv worked on profile page and login integration with firebase (login branch).

