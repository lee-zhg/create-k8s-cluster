# Getting Started with Machine Learning for the Developer
### Industrializing Data Science and Machine Learning_

Machine Learning, and Data Science have been hot topics for the past 10 years, but what does it mean to the *developer*?
- Where does one get started?
- How do you transform data into insights?
- What does a Machine Learning model look like?
- How do you share the insights of a model with the world?

## Objective
Over the course of the next 3 - 4 hours you will work through 3 examples to bring your practical knowledge of machine learning and its applications up to todays best practices.

## Target Audience
- Developers that are too busy and need to use and apply best practices around Machine Learning today.
- Developers that want to have complete code examples to showcase understanding of Machine Learning, and how to integrate insights into applications.

## Contacts
- [David Carew](mailto:carew@us.ibm.com) - IBM Developer Advocate
- [Derek Teay](mailto:Derek.Teay@ibm.com) - IBM Developer Advocate
- [Matt Langbehn](mailto:mlangbe@us.ibm.com) - IBM Developer Advocate


## Outcomes
- Understand the process of deploying  Machine Learning models with continuous monitoring
- Understand the process  of implementing Hyperparameter optimization of Deep Learning models
- Understand the process of automatically identifying bias in Machine Learning models
- Links to relevant developer resources

## Requirements
* [IBM Cloud Account](https://cloud.ibm.com)


## Links
* [IBM Developer](https://developer.ibm.com)
* [Watson Studio Overview](https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/overview-ws.html?audience=wdp&context=wdp&linkInPage=true)
* [Watson Machine Learning Python SDK](https://wml-api-pyclient.mybluemix.net/)
* [Watson Studio Video Learning Center](https://www.youtube.com/playlist?list=PLzpeuWUENMK3u3j_hffhNZX3-Jkht3N6V)

## Estimated Time to Complete
**3-4 Hours**

# Presentation
Overview of the Machine Learning and Deep Learning landscape
### [Introduction to Machine Learning and Data Science for the Developer](docs/ml-workshop.pdf)

# Labs
- [Lab 0](#apply-a-promotional-code) - _Apply a Promotional Code_
- [Lab 1](#Lab-1) - _Apply continuous learning to a Machine Learning model_
- [Lab 2](#Lab-2) - _Hyperparameter optimization of Deep Learning models_
- [Lab 3](#Lab-3) - _Automatic bias detection in Machine Learning models_


## Apply a Promotional Code
In **Lab 1** you will be using an instance of IBM Db2 Data Warehouse service which  requires a promo code applied to your IBM Cloud account enabling you to create an instance without entering any credit card information.  

**1. Request Promo Code**

**Goto:** [https://developer.ibm.com/callforcode/featurecode](https://developer.ibm.com/callforcode/featurecode)

> Confirmation Code: `CFCday19`

After requesting and saving the promo code from above, login to [IBM Cloud](https://cloud.ibm.com), select `Manage` from the top menu bar, then `Account`.  Within the account page select the `Account Settings` option and scroll down to enter your feature code retrieved above.

![Use Feature Code](docs/images/use-feature-code.gif)


----

## Lab 1
### _Apply continuous learning to a Machine Learning model_

You’re a busy developer or  a data scientist and want the fastest path delivering data insights to users, but this requires deep expertise in many technology domains. This end-to-end use-case driven lab walks you through the technologies used to:

- Acquire data
- Build a predictive machine learning model
- Make predictions
- Host the model on IBM Cloud for consumption
- Automatically update and redeploy the model as needed as new data becomes available
- Integrate the model with your web application


**Tools Used**
- Watson Machine Learning _[(docs)](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/ml-overview.html)_
- Watson Studio _[(docs)](https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/welcome-main.html?audience=wdp)_
- Apache Spark Environments [(docs)](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/environments-parent.html?audience=wdp)


**Get Started**

Click on the link below to see the instructions for the lab.


### [Lab 1](https://github.com/ibm-ai-education/continuous-learning-with-watson-ml) - Apply continuous learning to a  Machine Learning model


## Lab 2
### _Hyperparameter optimization of Deep Learning models_
You're familiar with data science and Machine Learning, have built models before, but are trying to understand how to make sense of a large feature space. Deep learning with hyperparameter optimization is an effective method for speeding up the convergence of the model to the most optimal solution.

This lab begins by introducing you to Deep Learning through a Jupyter notebook environment using the Keras framework. The lab in **Part 2** builds on the Jupyter Notebook environment by defining and submitting experiments as Python code for training multiple models in parallel.

**By the end of these labs you should be able to:**

- Build a Deep Learning model in a Jupyter Notebook using Keras on timeseries data
- Deploy and consume the trained Deep Learning model as an API on the Watson Machine Learning Service
- Create and submit Deep Learning experiments in parallel for hyperparameter optimization
- Compare Deep Learning training runs for accuracy

**Tools Used**
- Jupyter Notebooks _[(docs)](https://jupyter-notebook.readthedocs.io/en/stable/)_
- Watson Machine Learning _[(docs)](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/ml-overview.html)_
- Watson Studio Deep Learning as a Service _[(docs)](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/ml_dlaas.html?audience=wdp)_
- Keras [(docs)](https://keras.io/)

**Get Started**

This lab is broken into two parts, **Part 1** focus on training a Recurrent Neural Network on Time Series data in a Jupyter Notebook. The dataset used contains only a single feature, but could easily be modified to include hundreds of features or a completely different timeseries dataset. **Part 2** packages up the code seen in Part 1 as a Python application, and configuration file and submits it to Watson's Deep Learning Service to perform hyperparameter optimization, training many versions of the same model with slightly different variations in parallel.

### [Lab 2 - Part 1](https://github.com/justinmccoy/timeseries-rnn-lab-part1) - Train a Recurrent Neural Network on a Jupyter Notebook in Python using Keras
### [Lab 2 - Part 2](https://github.com/justinmccoy/timeseries-rnn-lab-part2) - Perform Hyperparameter Optimization; train and host a Deep Learning model as a API web service

**Related Links**
- [AI Research @IBM](https://www.research.ibm.com/artificial-intelligence/)
- [Monitor Machine Learning Models with OpenScale](https://developer.ibm.com/patterns/monitor-custom-machine-learning-engine-with-ai-openscale/)
- [Refine your Deep Learning Model](https://developer.ibm.com/articles/image-recognition-challenge-with-tensorflow-and-keras-pt2/)


## Lab 3
### _Automatic bias detection in Machine Learning models_
The data science techniques often used in credit risk modeling, such as gradient boosted trees and neural networks, can generate highly accurate risk models, but at a cost. Such "black box" models generate opaque predictions that must somehow become transparent, to ensure regulatory approval such as Article 22 of the General Data Protection Regulation (GDPR), or the federal Fair Credit Reporting Act (FCRA) managed by the Consumer Financial Protection Bureau.

This lab will look at monitoring a deployed model's propensity for a favorable outcome ("No Risk") for one group (the Reference Group) over another (the Monitored Group) so a lender can determine if their deployed model in inadvertently introducing unexplainable bias into the  decision making process.


**Get Started**

Click on the link below to see the instructions for the lab.

### [Lab 3](https://cloud.ibm.com/docs/services/ai-openscale?topic=ai-openscale-gettingstarted#gs-setup) - Automatic bias detection in Machine Learning models



**Related Links**
- [Watson OpenScale](https://cloud.ibm.com/docs/services/ai-openscale?topic=ai-openscale-gettingstarted#gettingstarted)
