# BMI Calculator using Python

This repository consists of a simple yet efficient BMI calculator scripted using Python.

## Table of content

- [Repo Guide](#repo-guide)
- [Summary](#summary)
    - [About BMI](#about-bmi)
    - [About the calculator](#about-the-calculator)
- [Running the calculator](#running-the-calculator)
- [Resources](#resources)

## Repo Guide

This repo is small and crisp. All the files are available in **Calc** folder of the repo. Fiel details are listed below:

| File name | Description |
| --- | --- |
| metric.py | Python script defining the BMI calculations and more in **metric unit system**. |
| imperial.py | Python script defining BMI calculation and more in **imperial unit system**. |
| bmi.py | Final and executable python script. |

## Summary

### About BMI

Body mass index (BMI) is a value derived from the mass and height of a person. The BMI is defined as the body mass divided by the square of the body height, and is expressed in units of kg/m², resulting from mass in kilograms and height in metres. BMI is a good gauge of your risk for diseases that can occur with more body fat.

#### BMI Chart

| BMI Level | Category | Health Risk |
| --- | --- | --- |
| Below **18.5** | Underweight | Low |
| **18.5 to 24.9** | Normal | Average |
| **25 to 29.9** | Overweight | Mildly increased |
| **30 to 34.9** | Obese class I | Moderate |
| **35 to 39.9** | Obese class II | Severe |
| **40** and above | Obese class III | Very Severe |

### About the calculator

Salient features of this calculator:

1. Easy to use.
2. Computes BMI in both, **Metric** as well as **Imperial** unit system.
3. Provide **health risk data** depending on your BMI.
4. Provides **approximate weight to be lost** in order to attain a **normal BMI**.

## Running the calculator

1. To run this calculator, you need to have **Python** installed on your device. If you don't have python installed on your device, visit [python.org](https://www.python.org), click on **downloads** and download the latest version of python.

2. Downlaod zip file of this repository to your device and unzip the file and copy the unzipped folder to a suitable position on your device.

3. Now, open **Command Prompt (CMD)/Terminal/Power Shell** , navigate to the unzipped folder and run `python bmi.py` or `python3 bmi.py`. 

4. If you recieve following error: *No such file or directory*, run `cd calc` and then run `python bmi.py` or `python3 bmi.py`.

## Resources

1. **Python:** [python.org](https://www.python.org)
2. **BMI:** [Learn more about BMI.](https://www.who.int/data/gho/data/themes/topics/topic-details/GHO/body-mass-index)