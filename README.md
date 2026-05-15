# Project Name - Shark Attacks miniproject

**Summary**
    In this project we want to analyze all the available data on shark attacks around the world. This impacts the safety of everyone on the seas and beaches           around the world. Our purpose is to be able to find out where and what activities are statistically more dangerous to help prevent those encounters.
    Safe turism and safe sports are our main goal. Improving life-threatning experiences is key.

    
## Business problems and oportunities
    
- Core problem:
    In today's data-driven market and connected people, companies and even places often struggle with people's bad experiences impacting their reputation, becoming an issue on the revenew side. 
    When the only information you receive about something you are interested in, is other person's personal experience instead of the actual and reliable information and data, promoting places to perform certain activities becomes unpredictable. This project bridges that information gap between personal and individual experiences and real and reliable information.
   
- Opportunity:
    By analyzing historical trends and cleaning anomalies from the data, we can unlock hidden patterns to improve the decision making when it comes to holiday or vacation destinations. With this approach, we can safely introduce costumers to the safest places to perform their activities.



## Problem Statements & Hypotheses

To guide the analytical process, this project addresses the following specific problem statements and testable hypotheses:

  > how the human behavior impacts the shark attacks

  > are they more likely to be provoked?
  
  > what activities are the most impacted

  > where are the attacks happening

  > how many fatal attacks have been - and if its relevant in percentage

  > we can encourage water-based activities in places where shark attacks are less likely





## Data Analysis & Cleaning Process

1.  **Data Profiling & Inspection:**
    * Assessed shape, data types (`df.info()`), and basic descriptive statistics (`df.describe()`).
    * Identified structural anomalies, missing values, and duplicate entries.
2.  **Handling Missing Values & Duplicates:**
    * Dropped exact duplicate rows to prevent statistical bias.
    * Imputed missing 
3.  **Data Type Conversion & Standardization:**
    * Cleaned and stripped string formats (e.g., removing `$` and `,` and white spaces)
    * Cast object types to explicit datetime or numerical formats using `pandas`


## Methodology - How we did it

We defined one function for each need and each step of the cleaning process. Once we have them, we can retrieve each one of them to get easily the needed data. If we want it all cleaned, we can run the main function that contains all the cleaning sub-functions. This way we can clean a whole dataset with just running the main function.

After cleaning, the returned dataframe was used to run static functions to see more clearly the actual values and display the statistics - for a visual understanding.
This visual data was imported to a presentation to provide clear and reliable information.
