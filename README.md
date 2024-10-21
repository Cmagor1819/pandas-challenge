# pandas-challenge
I got/referenced the following lines of code from Xpert Learning Assistant/GitHub

school_spending_df["Spending Ranges (Per Student)"] = pd.cut(per_school_capita, spending_bins, labels = labels)
per_school_math = school_data_complete.groupby(["school_name"])["math_score"].mean()
per_school_reading = school_data_complete.groupby(["school_name"])["reading_score"].mean()
students_passing_math = passing_math.groupby(["school_name"]).count()["student_name"]
school_count = school_data_complete["school_name"].nunique()
