# GB_GMM

# Cumulative absolute velocity (CAV) prediction model based on Gradient Boosting algorithm

Gradient Boosting algorithm is implemented to predict the geomean Cumulative Absolute Velocity (CAV) of two horizontal components. A Turkiye based regional ground motion model is obtained using The New Turkish Strong Motion Database (N-TSMD).

This folder includes the source codes of the SDEE paper (KTP23) : Kuran, F., Tanırcan, G., Pashaei, E. (2023) “Performance evaluation of machine learning techniques in predicting cumulative absolute velocity”, Soil Dynamics and Earthquake Engineering. 174, 108175. https://doi.org/10.1016/j.soildyn.2023.108175.

Note: The software for this paper (KTP23) is now available. You can reach it by clicking the link: https://ktp23-turkiyespecificgmmforcav.streamlit.app/. CAVs can be obtained by defining Mw, Vs30, Rjb, and SoF estimator parameters without using any program or library.

# Steps to be applied
- Install Python 3.9 on Anaconda
- Get required dependencies
- Download gb_gmm in your main working directory
- Unzip the "gb_gmm.zip" file in your main working directory
- Arrange your input files: "file_one.xlsx" for 3.5≤Mw≤5.4 and "file_two.xlsx" for 5.5≤Mw≤7.6

# Required dependencies (PYTHON packages)
- scikit-learn
- scipy
- pandas
- numpy
- pickle
