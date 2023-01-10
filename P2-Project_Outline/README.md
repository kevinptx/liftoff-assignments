# Project Outline

For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description

[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview

The app will be a doctor/provider portal with login that allows doctors to view information about patients. I will include a prescriptions, doctor notes, diagnosis, and patient details. Diagnosis needs to be present and optionally can have prescriptions. A doctor should have many patients so this is a ManyToOne relationship. A Doctor should be OneToMany as one doctor has many patients. I will have single login page where the doctor provides info.

I will pull drug info from the following API which I have already tested and successfully fetched from: https://open.fda.gov/apis/try-the-api/

### Features

Doctor (User) should be able to login
Doctor should be able to view patients with any associated patient data
Doctor should be able to select from a list of common drugs. For the drug selected, the doctor should be able to see basic drug details such as adverse reactions, dosage, description, etc...

### Technologies

I have confirmed access to the following API that I will utilize for drug information:
https://open.fda.gov/apis/drug/drugsfda/how-to-use-the-endpoint/
The backend will be in Java with SpringBoot and Hibernate
The frontend will utilize angular Angular, Vanilla Javascript and/or Thymeleaf templates
Vanilla CSS or Bootstrap

### What I'll Have to Learn

I know the basic technologies that are needed for this app. If I want to implement a calendar feature for patient appointments, I may need to learn how to implement a calendar selector in the front end using bootstrap that is tied to a Date object in Java on the back end.

### Project Tracker

https://trello.com/b/GqhUbVdb/liftoff-2023
