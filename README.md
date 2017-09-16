R code sentiment analysis on Amazon Book Reviews. Algorithms used: Naive-Bayes, SVM
# Sentiment Analysis for Amazon Book Reviews

This project is a tool for training and creating a model for determining the sentiment of a book review. 
Trained with a dataset of 10K book reiviews.
Used 2 different algorithms for comparison: Support Vector Machine, Naive-Bayes
Overall goal: Given a sample book review predict the overall rating (1-5 stars) that someone would rate the book and output accuracy of model.

Contributors: Edward Ni, Cian O'Callaghan, Kush Agarwal

#####
# Requirements

	-> Install R:
		For Linux: https://cran.r-project.org/bin/linux/
		For Mac OS X: https://cran.r-project.org/bin/macosx/
		For Windows: https://cran.r-project.org/bin/windows/

#####




#####
# Required Software:

	-> Install RStudio:
		For Ubuntu 12.04+ (64-bit): https://download1.rstudio.org/rstudio-1.0.143-amd64.deb
		For MacOS X 10.6+: https://download1.rstudio.org/RStudio-1.0.143.dmg
		For Windows Vista/7/8/10: https://download1.rstudio.org/RStudio-1.0.143.exe
#####





#####
# Folder Contents:
	SentAnalysis.r
	reviewsDataset.json
	README.txt
#####

	
#####
# How To Execute
	
	-> Highlight everything and run. (should output SVM graph and accuracy, then Naive Bayes graph and accuracy, and then Wordcloud.  Final results printed at the end)
	
	**Please note** : if you get an error about setting the correct working directory, here is how you can fix it:
	In RStudio, in the menu bar all the way on top click Session -> Set Working Directory -> Choose Directory.  A browsing dialog box opens up - choose the folder "group2files" from the flash drive or wherever it has been extracted.  This should clear the error.
#####
