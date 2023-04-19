# Parameter-Optimization-of-SVM

Dataset Used : [Abalone](https://archive.ics.uci.edu/ml/datasets/abalone)


|                      |      | 
|----------------------|------|
| Number of Instances  | 4177 |   
| Number of Attributes | 8    |   

#### Dataset Description :

Predicting the age of abalone from physical measurements. The age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope -- a boring and time-consuming task. Other measurements, which are easier to obtain, are used to predict the age. Further information, such as weather patterns and location (hence food availability) may be required to solve the problem

### Parameter Optimisation of SVM
#### Kernels Used

- linear
* poly
+ rbf
- sigmoid

# Final Result

| Sample | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |  
|--------|---------------|-------------|---------|--------------|
| 1      | 0.26          | rbf         | 9.29    | 8.41         |
| 2      | 0.28          | rbf         | 8.94    | 3.67         |
| 3      | 0.27          | rbf         | 7.19    | 1.47         |
| 4      | 0.27          | rbf         | 9.98    | 4.00         |   
| 5      | 0.27          | rbf         | 5.35    | 5.27         |   
| 6      | 0.27          | rbf         | 6.52    | 9.33         |   
| 7      | 0.27          | linear      | 2.06    | 2.63         |   
| 8      | 0.26          | rbf         | 2.75    | 4.60         |  


### Convergence Graph

![ss](https://github.com/rohitthapar/Parameter-Optimization-of-SVM/blob/main/Screenshot%202023-04-19%20at%202.44.08%20PM.png)
