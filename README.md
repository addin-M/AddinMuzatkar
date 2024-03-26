Title: Predicting Sales Order of Press Cage

Background:
In palm oil mill industry, press cage is heavily used as a wear-and-tear part in a screw press machine. The press cage applies pressure to the fruit bunches, causing the oil to be squeezed out from the mesocarp.
The solid components of the fruit, such as fibres and kernel, remain inside the press cage, while the extracted oil flows out. This key function of press cage in extracting palm oil has led to its continuous demand,
hence to a high production order from client. Oftentimes this high demand resulted in a backlog when the manufacturing schedule is not properly planned.

Problem Definition:
The current average period between sales order date of press cage and delivery date is a month. Currently there is no proper analysis of previous order trend by management. Hence, they would like to improve the delivery time by preparing a proper projection for the manufacturing schedule. 

Objectives:
For this research, we would like to study the trend of press cage (PCG) sales order by using ARIMA time-series analysis, and determine if there is any seasonal pattern in the order.
By using the same ARIMA analysis, a one-step ahead and dynamic prediction for a particular press cage model are to be made.

Datasets Description:
Source: Datasets are taken from the sales order of various press cage model. The code PCG used to represent press cage, and the number following it is the model specs capacity
(i.e. PCG-P15 referring to model press cage that can run a capacity of 15ton/hour of fresh fruit bunch). Particularly for this project, we will only use PCG-P15 as target model due to its high average number of orders.
The sales quantity recorded for this dataset is taken from weekly report, throughout 10 years of production. The target column is quantity model. The time-series index is calculated from the StartDate column,
which represent the start date of the week.
Number of samples: 500+
Attributes: Year, Month, month week, WeekNum, StartDate, model names.
