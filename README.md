This is the source code of SEDLA, which includes the Online AE and W-EWC methods. The AdaFNN model in the code is derived from the paper "Deep Learning for Functional Data Analysis with Adaptive Basis Layers" by Junwen Yao et al., and its open-source code is available at: https://github.com/jwyyy/AdaFNN.

The real-world datasets used by SEDLA are described as follows:

（1）Retina: This dataset consists of 336 samples and 255 observations, divided into 5 tasks with 55 observations per task. The independent variable is RE1, and the response variable is LE1. It is available at: https://physionet.org/content/perg-ioba-dataset/1.0.0/csv/#files-panel.

（2）Weather: This dataset consists of 248 samples and 240 observations, divided into 6 tasks with 40 observations per task. The independent variable is temperature in Celsius, and the response variable is wind speed in mph. It is available at: https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository.

（3）Tuberculosis: This dataset consists of 70 samples and 5,400 observations, divided into 6 tasks with 800 observations per task. The independent variable is the TB incidence rate, and the response variable is the mortality rate. It is available at: https://www.kaggle.com/datasets/ankushpanday1/tuberculosis-tb-predictiontop-75-countries/data.

（4）Flight: This dataset consists of 7,600 samples and 3,600 observations, divided into 6 tasks with 600 observations per task. The independent variable is departure delay (DEP DELAY), and the response variable is arrival delay (ARR DELAY). It is available at: https://www.kaggle.com/datasets/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018.
