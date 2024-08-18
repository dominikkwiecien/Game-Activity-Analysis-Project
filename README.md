# Game Activity Analysis Project

This project is an advanced data analysis of video game user activities based on in-game events. It was created using Google Sheets, with the goal of processing raw data to gain insights into user behavior and activity over time. The project involved several tasks related to data processing and visualization.

## Project Structure

1. **Activity Sheet**:

   - Contains data about user activities in games, including game name, activity name, duration, user language, and date-related information.
   - Data was processed to extract the game name and activity, and each activity was assigned a type.
   - Additional columns were created to include the activity month and the first activity month for each user, allowing for cohort analysis.

2. **Activity Types Sheet**:

   - Stores the mapping of activity names to activity types, enabling the aggregation of data by activity type.

3. **Cohort Analysis Sheet**:

   - Contains a pivot table that shows the number of unique users in each activity month (Activity month number).
   - This table was used for further cohort analysis.

4. **Active Users Sheet**:
   - Provides data on users, such as user ID, language, age, and other demographic information.

## Completed Tasks

1. **Splitting the "game_activity_name" Column**: The column was split into two parts — game name and activity name.
2. **Assigning Activity Types**: Based on the activity names, each activity was assigned to a specific type, enabling further analysis.
3. **Adding a User Language Column**: Data from the "active users" sheet was merged with the "activity" sheet to add user language information.
4. **Creating New Date-Related Columns**: Columns related to activity months were created, allowing for cohort analysis.
5. **Cohort Analysis**: A pivot table was prepared to show the number of unique users in each activity month.
6. **Visualization**: The results of the cohort analysis were visualized using a line chart.

## Visualization

The project includes a line chart that shows the number of unique users in each activity month (Activity month number). This chart provides a quick understanding of trends and the dynamics of user activity over the analyzed period.

### How to Use

- Download and open the `Game Activity Analysis Project.xlsx` file to explore the data and charts.
- Use the data and charts to understand user activity trends and the effectiveness of predictions.

## Summary

This project is a comprehensive tool for analyzing video game user data. It includes both data processing and visualization, allowing for a deeper understanding of user behavior patterns. The use of tools like Google Sheets makes the project easy to manage and edit.
