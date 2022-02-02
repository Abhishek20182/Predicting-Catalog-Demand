<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>

<h3 align="center"><a href = "https://www.udacity.com/course/predictive-analytics-for-business-nanodegree--nd008t"> Udacity Predictive Analytics for Business</a></h3>
<h4 align="center">Project II: Predicting Catalog Demand</h4>


## Table of Contents
- [Project Overview](#project_overview)
- [Project Details](#detail)
- [Results](#results)
- [Licensing, Authors, and Acknowledgements](#licensing)


## Project Overview <a name="project_overview"></a>
In this project, you will analyze a business problem in the mail-order catalog business. You're tasked with predicting how much money your company can expect to earn from sending out a catalog to new customers. This task will involve building the model and applying the results in order to provide a recommendation to management.

### How do I Complete this Project?
This project uses skills learned throughout our "Problem Solving with Advanced Analytics” course. To complete this project:
- Go through the course.
- Apply the skills learned in the course to solve the business problem given in the project details section.
- Use our guidelines and rubric to help build your project.
- When you're ready, submit it to us for review using the submission template found in the supporting materials section.

Note: Depending on your experience, you may not need to take the whole course to complete this project.

### Skills Required

In order to complete this project, you must be able to:
- Build a linear regression model and apply the results to a business problem.


## Project Details<a name="detail"></a>

### The Business Problem

You recently started working for a company that manufactures and sells high-end home goods. Last year the company sent out its first print catalog, and is preparing to send out this year's catalog in the coming months. The company has 250 new customers from their mailing list that they want to send the catalog to.

Your manager has been asked to determine how much profit the company can expect from sending a catalog to these customers. You, the business analyst, are assigned to help your manager run the numbers. While fairly knowledgeable about data analysis, your manager is not very familiar with predictive models.

You’ve been asked to predict the expected profit from these 250 new customers. Management does not want to send the catalog out to these new customers unless the expected profit contribution exceeds $10,000.

### Details
- The costs of printing and distributing is $6.50 per catalog.
- The average gross margin (price - cost) on all products sold through the catalog is 50%.
- Make sure to multiply your revenue by the gross margin first before you subtract out the $6.50 cost when calculating your profit.

Write a short report with your recommendations outlining your reasons why the company should go with your recommendations to your manager.

### Steps to Success

#### Step 1: Business and Data Understanding

Your project should include:

- A description of the key business decisions that need to be made.
Note: Clean data is provided for this project, so you can skip the data preparation step of the Problem Solving Framework.

#### Step 2: Analysis, Modeling, and Validation

- Build a linear regression model, then use it to predict sales for the 250 customers. We encourage you to use Alteryx to build the best linear model with your data.

Note: For students using software other than Alteryx, if you decide to use Customer Segment as one of your predictor variables, please set the base case to Credit Card Only.
However, feel free to use any tool you’d like. You should create your linear regression model and come up with a linear regression equation.
Once you have your linear regression equation, you should use your linear regression equation to predict sales for the individual people in your mailing list.

#### Step 3: Writeup
- Once you have your predicted or expected profit, write a brief report with your recommendation to whether the company should send the catalog or not.

Hint: We want to calculate the expected revenue from these 250 people in order to get expected profit. This means we need to multiply the probability that a person will buy our catalog as well. For example, if a customer were to buy from us, we predict this customer will buy $450 worth of products. At a 30% chance that this person will actually buy from us, we can expect revenue to be $450 x 30% = $135.

## Results: <a name="results"></a>
All the results(including graphs) are in the <a href="https://github.com/Abhishek20182/Predicting-Catalog-Demand/blob/main/Final_Predicting_Catalog_Demand.pdf">Final_Predicting_Catalog_Demand.pdf</a> File.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Udacity to providing this data. You can find the Licensing for the data and other descriptive information at Udacity Page.
