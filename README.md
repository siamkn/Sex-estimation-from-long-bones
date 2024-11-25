## **Project Data Structure**

The project is organized into four main folders, with an additional folder for data, each serving a specific purpose.

**1\. BalancedData_gridsearchcv**

This folder is designed for running 15 algorithms using grid search cross-validation on balanced datasets. The subfolders represent various imputation techniques applied during the grid search:

```
BalancedData_gridsearchcv_FancyImputer  
BalancedData_gridsearchcv_IterativeImputer  
BalancedData_gridsearchcv_KNNImputer
```

**2\. UnBalancedData_gridsearchcv**

Similar to the first folder, this section focuses on grid search cross-validation, specifically on unbalanced datasets:

```
UnBalancedData_gridsearchcv_FancyImputer  
UnBalancedData_gridsearchcv_IterativeImputer  
UnBalancedData_gridsearchcv_KNNImputer
```

**3\. BalancedData**

This section contains files for testing the 15 algorithms on balanced samples. Subfolders represent different imputation techniques:

```
BalancedData_FancyImputer  
BalancedData_IterativeImputer  
BalancedData_KNNImputer
```

**4\. UnBalancedData**

Section with unbalanced samples are located here, organized by imputation technique:

```
UnBalancedData_FancyImputer  
UnBalancedData_IterativeImputer  
UnBalancedData_KNNImputer
```

**5\. Data**

This folder contains the raw data used in the project.


