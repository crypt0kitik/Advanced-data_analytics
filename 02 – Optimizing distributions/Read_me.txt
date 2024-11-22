Every folder has a separate report with screenshots 
in order to provide you with the same view that 
I have and in order to avoid crushing

Classification datased - bank
01 - Sampling technique (oversampling) - ADASYN    
02 - Data synthetization (SMOTE)
02 - Data synthetization (CTGAN)  
03 - Noise Management (ClusterCentroids) + Log.reg model for comparison of metrics
04 - Overlap Management (Tomek Links) + Log.reg model for comparison of metrics (amazing results)
05 - Outlier Management (Isolation Forest) + Log.reg model for comparison of metrics
05 - Outlier Management (Elliptic Envelope) + Log.reg model for comparison of metrics

Regression dataset - movies
01 - Sampling technique (oversampling):
    Data Augmentation with Noise 
    & Round the Ratings to Match Existing Values
02 - Data synthetization (CTGAN)  
02 - Data synthetization (SDV)  --- working on it

--- not done yet:
03 - Noise Management (MAD)
03 - Noise Management (RANSAC)
04 - Overlap Management (Autoencoders)
05 - Outlier Management (IQR)
05 - Outlier Management (IQR + Isolation Forest)
05 - Outlier Management (z-score)

Other datasets for experiments
01 - Sampling technique (undersampling)
01 - Hybrid Resampling (Undersampling + Oversampling)   
--- not done yet:
02 - Data synthetization (TabFairGAN) 
02 - Data synthetization (GMMs) 