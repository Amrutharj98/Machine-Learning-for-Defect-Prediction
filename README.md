# Machine-Learning-for-Defect-Prediction
### Description:
Developed a machine learning model to predict the lifespan of metal parts based on manufacturing parameters. The goal was to estimate whether a part is defective or usable without destructive testing, helping optimize production processes.

### Key Tasks:
#### ✔ Regression Analysis: Predicted part lifespan using multiple ML models and evaluated performance.
#### ✔ Classification Model: Developed a model to classify parts as defective or non-defective based on a lifespan threshold.
#### ✔ Feature Engineering: Explored alternative methods (statistical thresholds, clustering) for better defect classification.

### Skills & Technologies:
🔹 Machine Learning: Regression & Classification Models

🔹 Data Analysis: Feature Engineering, Model Evaluation, Hyperparameter Tuning

🔹 Tools: Scikit-learn, Pandas, NumPy, Matplotlib
### Dataset Description
This file contains 1000 observations of metal parts that have been destructively tested to estimate their true lifespan for if the part was used for its intended purpose. These lifespan measurements have been collected with processing parameters used when casting the parts, along with observations of the state of the microstructure and observable defects on the completed part.

##### Column Headings:
- Lifespan: Continuous Data. Measured lifespan of a metal part (Hours).

- partType: Categorical Data. Different metal parts being tested. (Blade, Nozzle, Valve, Block).
  
- microstructure: Categorical Data. Observed microstructure for the cast part - equiaxed, columnar or single crystal ('equiGrain', 'singleGrain', 'colGrain').
  
- coolingRate: Integer Data. Speed of liquid metal cooling, controlled with external heaters. (K/s).
  
- quenchTime: Continuous Data. Time completed metal part was immersed in water(seconds).
  
- forgeTime: Continuous Data. Time completed metal part was worked with aautomated hammer (seconds).
  
- HeatTreatTime: Continuous Data. Time completed metal part was given heattreatment (minutes).
  
- Nickel%: Continuous Data. Percentage of Nickel in the metal alloy.
  
- Iron%: Continuous Data. Percentage of Iron in the metal alloy.
  
- Cobalt%: Continuous Data. Percentage of Cobalt in the metal alloy.
  
- Chromium%: Continuous Data. Percentage of Chromium in the metal alloy.
  
- smallDefects: Integer Data. Number of small radius defects observed.
  
- largeDefects: Integer Data. Number of large radius defects observed.
  
- sliverDefects: Integer Data. Number of elongated defects observed.
  
- seedLocation: Categorical Data. Notes whether growth begins at top or bottom of mould (Top, Bottom).
  
- castType: Categorical Data. Type of casting method used (Die, Investment, Continuous).
