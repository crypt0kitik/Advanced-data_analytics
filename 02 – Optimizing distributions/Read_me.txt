Every folder has a separate report with screenshots 
in order to provide you with the same view that 
I have and in order to avoid crushing

Classification datased - bank
01 - Sampling technique (oversampling) - ADASYN    
02 - Data synthetization (SMOTE)
02 - Data synthetization (CTGAN)  
03 - Noise Management (ClusterCentroids) + Log.reg model for comparison
04 - Overlap Management (Tomek Links) + Log.reg model for comparison(amazing results)
05 - Outlier Management (Isolation Forest) + Log.reg model for comparison
05 - Outlier Management (Elliptic Envelope) + Log.reg model for comparison

Regression dataset - movies
01 - Sampling technique (oversampling):
    Data Augmentation with Noise 
    & Round the Ratings to Match Existing Values
02 - Data synthetization (CTGAN) 
02 - Data synthetization (SDV)  --- working on it (SDV modules does not work)
03 - Noise Management (MAD)
03 - Noise Management (RANSAC) + 2 regressions with RANSAC and without for comparison
04 - Overlap Management (Autoencoders)  + linear reg. model for comparison
05 - Outlier Management (IQR + Isolation Forest) 


05 - Outlier Management (z-score) -- working on it

Other datasets for experiments
01 - Sampling technique (undersampling)
01 - Hybrid Resampling (Undersampling + Oversampling)   
--- not done yet:
02 - Data synthetization (TabFairGAN) 
02 - Data synthetization (GMMs) 