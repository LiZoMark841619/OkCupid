# OkCupid

This project is the last one in the Codecademy Data Science, M.L. path. It is about almost 60.000 adult people who would like to find love, or their other half. In the examination, there are men and women with different social, professional, and educational backgrounds from 18 to 110 years old.

The dataframe ('profiles.csv') has many columns (31 features) with approximately 60.000 rows (observations). It has both numerical and categorical variables such as age, height, or body_type, diet, drugs, smokes, sex, and orientation among the others.

The goal - after performing EDA (Explanatory Data Analysis) for example making descriptive stats or making visualizations with charts  - is to clean and manipulate data in order to make a transparent and useable dataframe to build Machnine Learning models to solve some problems.

In this Project I have used LogisticRegression model to predict whether a person is male, or female, straight or not, available or not for others. I also used KNearest neighbors and RandomForest algorithms to solve, or find out the unknown value of the zodiac sign of a person, because that feature is pretty important to match while searching for love. 

During the Project I dealt with nan values and fake rows. I also made some changes in other values regarding other features such as (signs, education, or diet) by making groups of them. I made some charts as well (pie plots, histograms, count plots) in order to have a clearer picture of the data we got. Manual and automatic label generation was also a part of the transformation (np.where(), replace(), LabelEncoder()), and data Standardizing. 

The used models can have better performance (for example choose other (more or less) features as better predictors, or with tuning hyperparameters).

