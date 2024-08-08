# Hotel Bookings Cancellation Data Analysis

This project involves an in-depth analysis of hotel booking cancellations using Excel.

- **Objective**: Analyze the reasons behind booking cancellations and identify patterns to help hotels reduce cancellation rates.

## Dataset Columns

- **hotel**: Type of hotel (e.g., Resort Hotel, City Hotel)
- **is_canceled**: Cancellation status (0 for not canceled, 1 for canceled)
- **arrival_date_year**: Year of arrival
- **arrival_date_month**: Month of arrival
- ...(other relevant columns)

## Project Tasks

1. **Understanding the Business Problem**
2. **Data Cleaning and Transformation**
3.  **Pivot Tables and Charts**

### Analysis and Visualization

   - **Total Bookings and Cancellations by Room Type**
     - **Pivot Table**: Rows - Room Type, Columns - Cancellation Status, Values - Count of Bookings
     - **Chart**: Bar chart showing the number of total bookings and cancellations for each room type.
   - **Total Bookings and Cancellations by Room Status**
     - **Pivot Table**: Rows - Room Status, Columns - Cancellation Status, Values - Count of Bookings
     - **Chart**: Bar chart to compare total bookings and cancellation rates across different room statuses.
   - **Month-wise Cancellation Trends**
     - **Pivot Table**: Rows - Arrival Date Month, Columns - Cancellation Status, Values - Count of Bookings
     - **Chart**: Bar chart showing the number of cancellations for each month.
   - **Total Bookings and Cancellations by Guest Type**
     - **Pivot Table**: Rows - Guest Type, Columns - Cancellation Status, Values - Count of Bookings
     - **Chart**: Bar chart showing total bookings and cancellations for each guest type.
   - **Comparison of Total Bookings and Cancellations by Hotel Type**
     - **Pivot Table**: Rows - Hotel Type, Columns - Cancellation Status, Values - Count of Bookings
     - **Chart**: Pie chart to compare total bookings and cancellations between different hotel types (e.g., Resort Hotel vs. City Hotel).


4. **Interactive Dashboard**
   ![Dashboard (2)](https://github.com/user-attachments/assets/b853c9af-54f1-456f-afbc-ed574fd0081d)

## Insights

- **Total Cancellations**: Out of 119,390 total bookings, 44,224 were cancelled. This indicates a significant cancellation rate that impacts hotel revenue and resource planning.
- **Room Status**: Desired rooms have the highest number of cancellations, suggesting that high-demand rooms are more likely to be cancelled. This could be due to overbooking or guests changing their preferences last minute.
- **Guest Type**: Couples lead in both bookings and cancellations. This demographic's cancellation behavior may be influenced by changes in travel plans or personal reasons.
- **Room Type**: Room type 'A' experiences the most cancellations, likely due to its popularity. Hotels may need to explore policies or incentives to reduce cancellations for this room type.
- **Monthly Trends**: Cancellations are highest in certain months, such as October and August. This trend may reflect seasonal travel behaviors or specific events impacting hotel stays.
- **Hotel Type**: Resort Hotels have a higher cancellation rate compared to City Hotels. This could be due to the leisure nature of resort stays, where plans are more flexible and subject to change.
