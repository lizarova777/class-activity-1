# Class Activity 1
## Data Manipulation

In this repository, you will find data describing Swirl activity from a graduate course in Data Mining. 

### Instructions

1. Load the libraries  `tidyr` and `dplyr`
2. Create a data frame from the `swirl-data.csv` file called `DF1`

The variables are:

`course_name` - the name of the R course the student attempted  
`lesson_name` - the lesson name  
`question_number` - the question number attempted
`correct` - whether the question was answered correctly  
`attempt` - how many times the student attempted the question  
`skipped` - whether the student skipped the question  
`datetime` - the date and time the student attempted the question  
`hash` - anonymyzed student ID  

3. Create a new data frame that only includes the variables `hash`, `lesson_name` and `attempt` called `DF2`

4. Use the `group_by` function to create a data frame that sums all the attempts for each `hash` by each `lesson_name` called `DF3`

5. Convert `DF3` to this format  

6. Create a new data frame from `DF1` called `DF4` that only includes the variables `hash` and `correct`

7. Convert the `correct` variable so that `TRUE` is coded as the **number** `1` and `FALSE` is coded as `0`  

8. Create a new data frame that called `DF4` that provides a mean score for each student

9. Convert the `datetime` variable into month-day-year format and create a new data frame (`DF5`) that shows the average correct for each day

