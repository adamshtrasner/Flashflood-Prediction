# Flash Floods Forecasting with Deep Learning

Floods have consistently posed challenges globally, both in terms of human safety and economic impacts. The issue becomes even more pressing when we consider the quick and
unpredictable nature of flash floods, which are particularly prominent in regions like Israel.
Traditionally, our approach to tackle this problem has revolved around process-based models.  However, the multifaceted intricacies of hydrological processes sometimes limit the
precision of these models.

Recently, there’s been a shift in the academic community towards exploring machine
learning for hydrological predictions. Machine learning, given its data-driven nature, holds
the potential to identify patterns and make predictions that might be less intuitive for traditional models. Despite the promise it holds, the practical application of machine learning in
flood forecasting remains relatively uncharted. This is especially true for flash floods, which
due to their rapid onset following rainstorms, demand a more instantaneous and precise prediction mechanism.

As part of our final project in computer and data science Bsc, and with the guidance of proffessor Efrat Morin from the Hebrew University of Jerusalem, we tackled this problem with the use of LSTM and GRU neural networks for predicting the flow rate L time steps forward at 5 hydrological stations of interest in Israel, where L is a chosen time lead.
The full details and all the results are specified in the report (report.pdf).

Code folder explanation:

* preprocess.ipynb - preprocessing of the flow rate data.
* ayalon.ipynb, bet_lehem.ipynb, gaaton_ben_ami.ipynb, qishon.ipynb, soreq.ipynb - the main code for each of the 5 station (training and testing of the models).
* functions.ipynb - a notebook that includes all of the functions used for the main code.

IMS folder explanation:

This file includes rainfall data for 4 of the 5 chosen stations (one of them does not include rainfalldata), from 2018 to 2021.
