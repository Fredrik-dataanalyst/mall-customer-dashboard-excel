
# Mall Customer Dashboard

## Project Overview

This project aims to showcase an interactive dashboard designed to segment and analyse mall customers based on demographic and spending data. The dashboard provides visual insights into customer behaviour, offering valuable information to inform targeted marketing strategies. This README will outline the dashboard's functionality and present key insights drawn from the data.

## Dataset

The data used in this project is the ** Mall Customer Segmentation Data available on Kaggle. This dataset includes customer demographic information, annual income, and spending scores (a metric of the customers' spending power), which are used to analyze customer segments. The demographic information includes customers' age and sex.

## Motivation

Understanding the demographics and spending patterns of mall customers is crucial for optimizing marketing efforts. This project explores two key strategies for increasing profitability:

1. Targeting larger customer demographics to increase their spending.
2. Attracting high-income customers with higher spending scores to boost mall visits and purchases.

By analysing these approaches, the dashboard helps identify which customer segments hold the most potential for targeted marketing, allowing the mall to develop data-driven campaigns for maximum impact.

## The Dashboard's functionality

The dashboard contains 2 slicers and 8 charts. 

![Displaying_dashboard](https://github.com/user-attachments/assets/37a92147-58cd-43ab-835d-193f8b865da0)

Below the title of the Dashboard, 'Mall Customers Information,' you’ll find the slicers, indicated by red arrows. These are connected in various ways to the different charts. When you press their buttons, the connected charts update accordingly.

![Highlighting_slicers](https://github.com/user-attachments/assets/556bb666-37f7-48e0-a719-f001484358f6)


One slicer allows the user to select which age groups should be represented, while the other allows selection by sex. However, these slicers only affect certain charts, as described below.

The first four charts, located beneath the slicers, are connected to both slicers. Two of these are pie charts: one displays the proportions of customers across age categories, while the other displays the proportion of customers by sex. The single-bar charts next to the pie charts show the average spending score and average annual income.

![Displaying_four_first_charts](https://github.com/user-attachments/assets/a28dd744-02ba-4500-9637-9e35bcb9a4ed)

Note that all of these charts are updated using the slicers. The slicers determine which customers are represented in the charts.

![Pushing_68-77 ](https://github.com/user-attachments/assets/64ade2c9-1ee9-4383-8bd8-76c79a2846e1)

![Pusing_Female](https://github.com/user-attachments/assets/8e99f81c-eb11-4289-ae19-569d4eace6fb)

The next two charts are a line chart of the number of visitors across age categories and a single-bar chart displaying the total number of customers. The line chart is affected only by the sex slicer, so pressing any button on the age slicer does not change this chart; all age categories are still displayed. However, the chart showing the number of customers is updated by both slicers.

![5th_and_6th_chart_change_when_pressing_buttons_on_age](https://github.com/user-attachments/assets/a482051f-7ad3-403d-a286-4fbf5a14ca5e)

The final two charts include a vertical bar chart displaying spending scores by sex across age groups, and a horizontal bar chart displaying average annual income by age group for each sex. The vertical bar chart is only affected by the sex slicer, while the horizontal bar chart responds to both slicers.

![Updates_of_7th_and_8th_with_buttons](https://github.com/user-attachments/assets/1bd666d7-1b45-4980-973f-5a5363a0ea49)


## Analysis

Some initial findings are:

* The dashboard indicates that people aged 28–37 visit the mall most frequently, with females being slightly more represented.

* There are more females than males in the sample, though the difference is minor.

* Average annual income is highest among males aged 28–37. For females, it peaks in the 38–47 age group.

* The average spending score is highest for both males and females in the 28–37 age group.

This analysis suggests that individuals aged 28–37, particularly females, are the most frequent visitors to the mall. This is likely because people in this age range may have settled down and have children to provide for. The average income peaks for males at this age but for females later, possibly due to child-rearing responsibilities. Both male and female spending scores are highest for the 28–37 age group, indicating they likely have higher expenses at this stage of life.

## Conclusion

The customer segment that visits the mall most frequently is the 28–37 age group, especially females. Males in this category spend the most, and both males and females in this group have the highest spending scores. Therefore, the mall should target this demographic to improve profitability.

- **Dataset Source**: [Mall Customer Segmentation Data on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

*(Note: To access and download the dataset, you may need a Kaggle account.)*
