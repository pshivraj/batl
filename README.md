# batl (Bio-Acoustic Transfer Learning)

This repository is a work of research group from UW and affiliates to analyze acoustic data from broadband hydrophones to study whales using signal processing and using Machine learning/Deep learning techniques to build classifiers
[.](https://github.com/robfatland/ops)


If you happen to be a whale biologist interested in analyzing a large volume of hydroacoustic data what you'd like to have is
an automated classifier that can do the tedious work of picking out segments from a year-long recording that are likely to
feature the vocalizations of the whale species you are interested in. Building such a classifier is the initial goal of **batl**.



## Motivation

We see six hydrophones operating for five years at 40 kilohertz producing 70TB of data. Imagine a marine biologist would like
to identify intervals where Humpback whale calls are present. Where do they look? One approach uses the OrcaNav tool which has 
the data reduced on several time scales. However that system is currently not in wide availability; so the idea is to move towards
a solution that uses Orca Nav as a resource, plus other elements. 

