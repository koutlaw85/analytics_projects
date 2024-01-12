# analytics_projects

The objective of this capstone project was to analyze smart device usage data, focusing on Fitbit tracker data, to gain valuable insights into consumer behavior regarding non-Bellabeat smart devices. The dataset, hosted on Kaggle, was securely stored in an iCloud drive folder and organized in a zip file containing various CSV files, offering minute-level output for physical activity, heart rate, and sleep monitoring.

To ensure the reliability of the data, a thorough analysis was conducted, acknowledging the potential impact of factors such as changes in user behavior, environmental influences, and synchronization delays between activity and device data.

Data preprocessing involved converting date-stored characters to date-time objects, checking for missing values, and validating the TotalDistance column in the DailyActivity dataset. The merging of Sleep and Daily Activity datasets enhanced the analysis, revealing that the original Daily Activity dataset had 33 unique participants, but after the merge, there were 24 unique participants. An outer join was applied to retain all records from the Daily Activity table, resulting in a joined dataset with 33 unique participants.

Further exploration included gathering summary statistics, examining trends in device usage across various metrics (Daily Activity & Steps, Intensities, and Sleep), and drilling down to weekdays for a more detailed analysis of activities by day.

A significant finding was that users engaged more in light active activity compared to other types of activity (sedentary, moderately, very active) in terms of distance and time spent. This insight suggests an opportunity for Bellabeat to market towards sedentary users, emphasizing the app's potential to facilitate small but meaningful steps to increase overall activity.
