# Anant-Portfolio
Project 1 - Zorus Tech


1.	Executive Summary
The internet is one of the biggest sources of information of websites with a variety of content. This content is often categorized and organized for consumption based on requirement. One such application is a custom classifier required by Zorus to provide flexibility to further develop Zorus’ product and to align with their current technology stack. A URL classification model was built that can accurately classify URLs.
The URL Classifier has the ability to classify URLs based on the website content data (text and images) and is aimed to help negotiate the existing provider eventually phasing out third party after the classifier gets mature enough. Apart from the basic data pre-processing, deadlinks were excluded as linkrot and a balanced dataset was created for analysis. URL classifier accurately classifies URLs with higher accuracy in predicting “Adult” category since this is a major concern for Zorus. 

2.	Problem Statement
The content classification engine provided by Zorus’ third party is a critical part of Zorus offering and is a major risk to its business model. MSPs struggle to provide cost effective and capable solutions. Since the margin of error (misclassification) in classifying URLs could hinder Zorus Product credibility, Zorus needs a URL classification model that can accurately classify given URLs into one of the 15 categories.

3.	Dataset Introduction
The dataset is related to website classification (DMOZ dataset). It has three columns which are ID, URL and Category. URL is the predictor variable and Category is the target variable. It has 1.5 million URLs with 15 different categories. The dataset is highly imbalanced. Few of the URLs are repeated with different categories. Many of the URLs were inaccessible.
