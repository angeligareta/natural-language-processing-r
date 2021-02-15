<h1 align="center">Natural Language Processing with R</h1>
<h4 align="center">Project for Intelligent Systems course of the EIT Digital data science master at <a href="https://www.upm.es/">UPM</a></h4>

<p align="center">
  <img alt="UPM" src="https://img.shields.io/badge/EIT%20Digital-UPM-blue?style=flat-square">
  <img alt="License" src="https://img.shields.io/github/license/angeligareta/natural-language-processing-r?style=flat-square" />
</p>

## Project summary
This project aims to give an overview about the basic steps to perform Natural Language Processing (NLP) with R programming language. 
In the [first part of the assignment](https://angeligareta.com/natural-language-processing-r/Homework1%20-%20Annotation.html), the aim is to process a corpus found in the [data folder](data/pos), use a POS tagger and manually check the results for
some sentences. From the results, I could conclude the main error is that the POS tagger did not take into account was the proper nouns in both singular and plural forms, such as America or Americans.
In the [second part](https://angeligareta.com/natural-language-processing-r/Homework2%20-%20Optimization.html], the goal is to optimize the previous naive POS tagger by adding custom patterns
to match certain POS tags, also to study the effect of patterns in terms of precision and recall.

## Implementation
The tasks were developed using R programming language, in the format of R markdown to explain every step.
