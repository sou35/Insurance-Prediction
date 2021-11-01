# Insurance-Prediction

Data contain information of the people and based on this how much insurance company charge to insure them.
Objective is to predict the insurance charges for the new people based on the information we will get from them.

![Alt Text](https://c.tenor.com/QXbsUHXuIp8AAAAM/democracyrising-our-time-now-for-our-health.gif)

Column names :

Age: age of policyholder

Sex: gender of policy holder (female=0, male=1)

BMI: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of        body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 25 

Children: number of children / dependents of policyholder 

Smokers: smoking state of policyholder (non-smoke=0;smoker=1)

Region: the residential area of policyholder in the US (northeast=0, northwest=1, southeast=2, southwest=3) 

Charges: individual medical costs billed by health insurance
## Prerequisites

You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.

## Project Structure

This project has four major parts :

1.Medical Cost insurance.ipy: This contains code fot our Machine Learning model to predict the insurance charges absed on training data in 'insurance.csv' file.

2.app.py - This contains Flask APIs that receives policyholder details through GUI or API calls, computes the precited value based on our model and returns it.

3.templates - This folder contains the HTML template to allow user to enter policyholder detail and displays the predicted the insurance charge.

4.static - This folder contains the CSS to allow the designer to define the way a web page is formatted, for example there are CSS commands for the colour and size of text, the positions of images and the width of text blocks.

## Model-Flask-Deployment

Running the project

  a. Run app.py using below command to start Flask API
```
python app.py
```
 By default, flask will run on port 5000.

 b. Navigate to URL http://localhost:5000

 Enter valid numerical values in all 6 input boxes and hit Predict.

 If everything goes well, you should be able to see the predcited insurance charge vaule on the HTML page!

