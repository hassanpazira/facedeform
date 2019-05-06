# facedeform
Prediction of Facial Deformation in Head and Neck Rhabdomyosarcoma

facedeform is a publicly available R code that implements the method proposed in Pazira, Hol and Smeele (2019), 
developed to model the facial deformation prediction for Head and Neck Rhabdomyosarcoma patients. 
The core of the facedeform package consists of dglars algorithm implemented in Fortran 90 to efficiently compute
the differential geometrical least angle regression solution curve on high dimensional multivariate generalized 
linear models (GLMs). facedeform supports the sparse variable and model selections, the parameter estimation
and the prediction in particular for high-dimensional multivariate GLMs.
