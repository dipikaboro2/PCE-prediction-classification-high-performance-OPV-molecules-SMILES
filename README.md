# PCE-prediction-classification-high-performance-OPV-molecules-SMILES
Deep learning based PCE Prediction and Classification of high performance OPV molecules from SMILES.

This repository contains codes for Power Conversion Prediction (PCE) prediction of of High performance Organic PhotoVolatic (OPV) molecules.
This is a tensorflow implementation of a Generic model, and two LSTM models.

## The model architectures:
#### Model 1 architecture
<table>
  <tr>
    <td> <img src="img/model1.png"  alt="Model-1" ></td>
  </tr>  
</table>

#### Models 2 and 3 use LSTM for two different tasks:
#### 1. PCE prediction of the OPV molecule. (Model 2)
#### 2. Classifying OPVs into High or Low efficiency of the molecule. (Model 3)
<table>
    <tr>
    <td> <img src="img/model2-3.png"  alt="Model-2-3" ></td>
  </tr> 
</table>

### Results
<table>
    <tr>
    <td> <img src="img/results.png"  alt="Results" ></td>
  </tr> 
</table>
