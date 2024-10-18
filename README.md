# pandas-challenge

# Summary

The Spending_Summary shows that school spending per capita does not seem to consistently affect student scores - in math, reading or overall. In fact, schools that spend less per capita tend to correlate to higher test scores. For example, schools with a spending range of $630 or less per student produced average scores and passing percentages in math, reading and overall that consistently exceeded schools who spent between $630-$680 per student.
  
The Size_Summary shows that schools with a Large population tend to result in lower test scores while Medium and Small schools result in higher test scores. One of the most significant differences was in % Overall Passing: about 58.3% of students in large schools passed overall compared to 90.6% in medium schools and 89.9% in small schools.

The School_Type table shows that between Charter and District schools, the former produced higher test scores in every category. The % Overall Passing showed the greatest difference: Charter schools were at 90.4% while District schools lagged behind at 53.7%. This data is further supported by the Highest Performing Schools (all Charter) and Bottom Performing Schools (all District) data sets. 

# Conclusions

We can conclude that school spending is not a large factor in improving test scores. The two most important factors in this data set are size and school type: small and medium schools result in higher test scores than large schools and charter schools significantly out-perform district schools.

# Code Support
To calcuate the total school budget and per capita spending, I received code support from the Xpert learning assistant as well as a TA. The end result code was my own work in combination with those two sources to make edits.
To create bins and calculate spending ranges, I received code support from the Xpert learning assistant as well as a BCS assistant. I modified this code that was provided to me by the BCS assistant: school_spending_df["Spending Ranges (Per Student)"] = pd.cut(per_capita_spending, spending_bins, labels=labels, right=False) 
