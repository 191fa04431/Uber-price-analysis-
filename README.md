# Uber-price-analysis-


𝗦𝘂𝗺𝗺𝗮𝗿𝘆 𝗼𝗳 𝘁𝗵𝗲 𝗖𝗼𝗱𝗲:

𝗜𝗺𝗽𝗼𝗿𝘁𝗶𝗻𝗴 𝘁𝗵𝗲 𝗱𝗮𝘁𝗮: The code imports necessary libraries such as numpy, pandas, seaborn, matplotlib, and various modules from sklearn for data manipulation, visualization, and machine learning.

𝗗𝗮𝘁𝗮 𝗟𝗼𝗮𝗱𝗶𝗻𝗴: It loads a CSV file containing Uber ride data into a DataFrame.

𝗗𝗮𝘁𝗮 𝗖𝗹𝗲𝗮𝗻𝗶𝗻𝗴:

• Displays the first few rows and information about the data frame.
• Drops unnecessary columns (Unnamed: 0, key, pickup_datetime).
• Fills missing values in dropoff_longitude and dropoff_latitude with their respective means.
• Distance Calculation: Implements the Haversine formula to calculate the distance between pickup and dropoff locations, adding a new column distance_km to the DataFrame.

𝗘𝘅𝗽𝗹𝗼𝗿𝗮𝘁𝗼𝗿𝘆 𝗗𝗮𝘁𝗮 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀 (𝗘𝗗𝗔):

• Various visualizations are created, including scatter plots, histograms, box plots, and a correlation matrix heatmap to analyze the relationships between features and the fare amount.

𝗢𝘂𝘁𝗹𝗶𝗲𝗿 𝗗𝗲𝘁𝗲𝗰𝘁𝗶𝗼𝗻 𝗮𝗻𝗱 𝗥𝗲𝗺𝗼𝘃𝗮𝗹: Identifies and removes outliers based on the Interquartile Range (IQR) method.

𝗗𝗮𝘁𝗮 𝗦𝗽𝗹𝗶𝘁𝘁𝗶𝗻𝗴: Splits the data into features (X) and target variable (Y), then further splits it into training and testing sets.

𝗠𝗼𝗱𝗲𝗹 𝗧𝗿𝗮𝗶𝗻𝗶𝗻𝗴: Initializes multiple regression models (e.g., Linear Regression, Random Forest, XGBoost) and trains them on the training data.

𝗠𝗼𝗱𝗲𝗹 𝗘𝘃𝗮𝗹𝘂𝗮𝘁𝗶𝗼𝗻: Evaluates each model using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2), storing the results in a DataFrame.

𝗩𝗶𝘀𝘂𝗮𝗹𝗶𝘇𝗮𝘁𝗶𝗼𝗻 𝗼𝗳 𝗥𝗲𝘀𝘂𝗹𝘁𝘀: Plots the performance metrics of the models for comparison.

If you enjoy my work, please give it a star — thank you for staying until the end. 

I’m open to discussions and eager to learn; looking forward to it!
