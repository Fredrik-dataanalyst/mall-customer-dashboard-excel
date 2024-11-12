## Dataset

The data used in this project is the **Mall Customer Segmentation Data** available on Kaggle. This dataset includes customer demographic information, annual income, and spending scores (A metric of the customers' spending power), which are used to analyze customer segments. The demographic information is the customers' age and sex. 

## Motivation

One could ask what type of customer the Mall's marketing team should target with their campaigns to obtain more profit. The demographic of the mall's customers is important in itself for this matter, whether the customers are males or females, or the age of the customers. For the larger group of customers visiting the mall, the mall should emphasise targetting, making this group spend more. Another idea is to target customers with higher annual income and higher spending scores, making more customers in this category visit the mall and buy products. 

## The Dashboard's functionality

The dashboard contains 2 slicers and 8 charts. 

Below the title of the Dashboard 'Mall Customers Information' one can find the slicers, these are connected in various ways to the different charts. 

One of these slicers allows the user to select which age groups should be represented, and the other which sex. However, these slicers are only connected to certain charts, as will be shown. 

The first four charts, below the slicers, are connected to both of them. Two of these are pie charts, one displaying the proportions of customers between the age categories and the other one displaying the proportion of customers in the sexes. The single-bar bar charts next to the pie charts display the average spending score and average annual salary.

Note that all of these charts are updated with the slicers. The slicers determine which customers are represented in the charts.

The next two charts are a line chart of the number of visitors over the age categories and a single-bar bar chart displaying the number of customers. The line chart is only determined by one of the slicers (the one of sex). So pressing any button on the age-slicer does not change this chart. All age categories are still displayed. The chart, displaying the number of customers, is updated by both slicers. 

The last two charts are a vertical bar chart, displaying the spending score between males and females over the age groups, and a horizontal bar chart displaying the average annual salary among age groups between the two sexes. The first of these is only updated by the slicer of the sex category and the other one by both slicers.

## Analysis

Some initial points to make are:

-The dashboard indicates that people in age 28-37 most frequently visits the mall, given that the sample is random. Especially females.

-There are more females than males in the sample but the difference is not great.

-The average annual salary is the greatest in males, aged 28-37. For females the greatest annual salary is in the age category 38-47. 

-The average Spending Score is the greatest among males age 28-37 and females age 28-37.

The picture we get is that females and males aged 28-37 most usually visits the mall. This is likely due to that people at this age have settled down and had children whom they need to provide for. The average annual salary is the greatest for males, age 28-37, but the greatest at a later age for women, probably due to the women usually having to care for their children at this age. The spending score is the highest for both males and females, at age 28-37. This confirms that they have to spend more because they have had children at this age.

## Conclusion

The group of customers most frequently visiting the store are 28-37 years old, especially the females. The males in this category are spending the most. The males and the females in this category have the highest spending scores. Thus, the conclusion is that the mall should target this category of customers to improve profit.

- **Dataset Source**: [Mall Customer Segmentation Data on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

*(Note: To access and download the dataset, you may need a Kaggle account.)*
