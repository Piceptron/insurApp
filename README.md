# Micro Insurance app

## What is it?
This is a micro insurance app that allows user to keep track of their assets, and recommends micro insurance products that best fit for the assets they own.

## How to use it? 
To begin, user upload images of their assets via camera button through navigation or home page, it will take a photo of the asset and sent to AWS for OCR and object recogniztion such that user doesn't need to hand enter most of the attributes themself. 

Then an interface is presented to the user to confirm and add additional attributes if needed, once user click on the button submmit, the asset entry will be recorded in our SQL database in AWS and our prediction model will re-evauate the best insurance product that fit for that user.

At last, user will be redirect to home page where they can see their recorded assets and recommended insurances based on their assets using our prediction model.

This app is created during Hack the Six 2019 Toronto.
