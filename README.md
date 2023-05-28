# whisky_analysis
A data analyst project for whisky. Using python to extract data and do Hypothesis Testing. Visualize data by python maltplotlib and Tableau. Aim to get insight from the dataset.<br>
2,2k+ Scotch Whisky Reviews dataset (https://www.kaggle.com/datasets/koki25ando/22000-scotch-whisky-reviews)
![image](https://github.com/franciskoinno/whisky_analysis/assets/77004397/34a64004-3b45-4baa-9041-6985570ac6a2)

## Goals
1. Find people like which flavors in whisky.
2. Find how regions affect the price and taste of whisky

## Extract data (details refer to jupyter notebbok)
1. Read csv by excel to check the information of the data
2. Extract the distilleries and region of the whisky from its name
3. Extract the flavor of the whisky from the description
4. Check any missing or wrong data
5. Save as another csv for futher analyze

## Exploratory Data Analysis
1. T-test (details refer to jupyter notebbok)
2. MANOVA
3. Find insight by graphical methods

## Visualization
![工作表 4](https://github.com/franciskoinno/whisky_analysis/assets/77004397/8c78015b-2dc3-426e-98df-fca82b1fa56c)
![工作表 1](https://github.com/franciskoinno/whisky_analysis/assets/77004397/d888a1ae-eaa7-42eb-98df-8030d234ac4c)

From the graph above, we can notice that some floral present more frequent in specific region and some less.<br>
If higher than 0.4, we defined it as frequently present. <br>
If lower than 0.05, we defined it as rarely present. <br>

## Findings
From t-test:<br>
The flavor that got a higher review points: ['fruit', 'honey', 'peat', 'smok', 'citrus', 'raisin', 'deep', 'complex', 'cinnamon', 'caramel', 'pepper', 'leather', 'chocolate']<br>
The flavor that got a lower review points: ['malt']<br>

From graph:<br>

## Insight
