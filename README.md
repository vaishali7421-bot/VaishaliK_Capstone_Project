# VaishaliK_Capstone_Project
We have dropped columns "umpire3", "player_dismissed","dismissal_kind","fielder as missing values percentage was more than 80%'
The date column was converted from object to datetime format using pd.to_datetime().
The columns which ahs missing values less than 10% has replaced with Unknow and no .
Outliers were detected in the win_by_runs and win_by_wickets columns using the Interquartile Range (IQR) method.
Mumbai Indians won the highest number of matches among all teams in the dataset.
