# pandas-challenge
# December 21, 2020
# Ryan Brown

This pandas-challenge repository is used to analyze a csv file of purchase data for video games
both qualitatively and quantitively. There are three main files that are used:

1. purchase_data.csv - This is the data that will be analyzed and is located here: pandas-challenge->
HeroesOfPymoli -> Resources -> purchase_data.csv

This file is the data that will be used. It contains the purchasing information by user (SN), each item they
purchased, the amount they purchased their item for, demographic information on the buyer, and more. There is 779 
unique purchases with data in this csv file. This file will be pulled into jupyter notebook using the file below.

2. HeroesOfPymoli_main - This is the script that uses python language in jupyter notebook that is run
to analyze the data. It is located here: pandas-challenge-> HeroesOfPymoli -> HeroesOfPymoli_main

This jupyter notebook file contains the entire analysis for this repository. It is all coded using python and 
specifically uses pandas data frames for the majority of the analysis. This file pulls in the data from 
"purchase_data.csv" discussed above. The goals of this analysis are to provide insight on the following information:

	a.) Player counts
	b.) Purchasing analysis: Showing the number items sold, average prices, purchases counts, and total revenue
	c.) Gender demographics and purchasing analysis by gender
	d.) Age demographics and purchasing analysis by age
	e.) Top spenders
	f.) Most popular items
	g.) Most profitable items

3. Heros Of Pymoli Analysis - This is a word document that was used to describe three trends found in the data
and offer possible applications to the company from which the data came from. This is located here: 
pandas-challenge-> HeroesOfPymoli -> Heros Of Pymoli Analysis

This word document was created after the analysis using the jupyter notebook described above. This document provides
a quantitive and qualitative assessment pulling from the data frames created in the jupyter notebook. The document
describes three major trends found and the possible implications on the marketing efforts of the company. The major
trends include the following:
	a.) Gender
	b.) Age
	c.) Most profitable Items


In order to get the most out of this repo, I suggest that one begins to dig into the files within the repository in order
of how they are listed within this readme. Beginning with looking at the raw CSV to familiarize yourself with the data, then
dig into the jupyter notebook coding, and finally reading the analysis word document as a discussion.

