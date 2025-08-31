# R-for-ChemE
R for ChemE is a crash course on the use of R for data analysis, focusing on a Chemical Engineering backgroud. The purpose of this course is not to have an advanced understanding of programming, statistics or chemometrics, but rather to provide the tools needed for you to plan your experiments and perform simple analysis on your data.


# Course structure
The course is divided into 3 parts:
1.	**The R language (sections 1-3)**
   
    This section is concerned with basic uses of R. You will learn how do load and save data, perform basic and semi-advanced calculations, and plot your data.
3.	**Statistics and chemometrics (sections 4-6)**
   
    In this section you will learn how and when to use key tools such as ANOVA, Tukey HSD and how to perform dimensionality reduction, multivariate modeling (both regression and classification) and how to improve your model quality using pre-processing and variable selection
5.	**Design of experiments (sections 7-?)**
   
    In this section we will cover the key methods for experimental design, from basics such as factorial designs, to optimization with RSM and optimal designs for modeling.


Each section comes with several RMD files, which you can open in RStudio or other IDE of your choice, a video lecture and several exercises for you to solve.

In the .Rmd files, you can read through all the topics covered in that section, as well as running example code by pressing the green button shown below:

<img width="699" height="258" alt="image" src="https://github.com/user-attachments/assets/360668b2-e3f5-4451-bdea-3aec5ab7fcd2" />


The solutions to the exercises will be posted a week after the exercise is posted. If you have any questions, feel free to contact me.

At the end of each part you will have the option to work in a small project to nail down what you learned by applying it to a real world scenario.

# Course Sections

## Section 1 – basics of R
Basic use of R:
   - Load packages from CRAN and GitHub
   - Help system
   - Load and store data from common file formats
   - Assigning variables
   - Comments
    
Data structures:
  -	Types and uses of data structures
  -	Generating data structures
  -	Indexing, nesting and dimensions 
  -	Named lists and matrices

Operators and expressions:
  -	Basic arithmetics
  -	Matrix operations
  -	Common mathematical operators

## Section 2 – control structures
Logic structures:
  -	Logical objects and operators
  -	If/else statements
  -	Logical indexing

Loop structures:
  -	For, while and repeat loops
  -	Loop breaks
  -	R-specific loop functions

Recursive functions:
  -	Writing custom functions
  -	Arguments, default values and documentation
  -	Principles of recursive iteration
  -	Avoiding infinite loops

## Section 3 – plots
Plot types:
  -	Line/point plots
  -	Histograms and boxplots

Plot parameters:
  -	The par() function
  -	Setting plot margins, axis, titles, colors, etc.
  -	Multiple plots
  -	Saving plots


Advanced plotting:
  -	Adding labels and text
  -	Drawing boxes, arrows and segments
  -	Advanced axis customization
  -	Heatmaps and images
  -	3D plots

## Section 4 – practical statistics
Data frames:
  -	Generating data frames
  -	Indexing and dimensions
  -	Plotting data frames

Basic statistics:
  -	Means, standard deviation and quantiles
  -	Normality tests, Q-Q plots and kurtosis
  -	Outlier tests

Group differences:
  -	ANOVA and t-tests
  -	Tukey HSD

Regression:
  -	Linear models
  -	Non-linear models
  -	Comparing performance of regression models: R2, AIC and BIC

## Section 5 – introduction to spectrometry

The features of spectra:
  -	Peaks
  -	Noise, signal-to-noise ratio and Fourier transforms
  -	Baseline drift and shift, non-linear baselines
  -	Spikes and miscellaneous artifacts

Visualizing spectra:
  -	Line plots
  -	Scalograms
  -	Principal component analysis (PCA)

Preprocessing spectra:
  -	Baseline correction (MSC and ALS)
  -	Noise correction (Savitzki-Golay filters, moving averages, Fourier filters and wavelet denoising)
  -	Normalization and scaling (Lp-, maximum- and peak-normalization, SNV, Pareto and Poisson scaling)

## Section 6 – multivariate regression and classification
Projection on latent structures:
  -	How PLS, PCA and MLR differ
  -	Interval PLS
  -	Comparing model performance

Classification and clustering:
  -	Supervised classification: SIMCA, PLS-DA, SVM
  -	Unsupervised classification: k-means clustering, FCM
  -	Comparing model performance (misclassification rate, sensitivity and specificity)

- Variable selection:
  -	Importance of variable selection
  -	Common variable selection methods (Jack-knife, VIP, selectivity ratio)



