# pandas-challenge
Penn Data Science Bootcamp Module 4 Challenge

Analyze district-wide standardized test results from 15 schools. 

Performed the necessary calculations and then created a high-level snapshot of the district's key metrics in a DataFrame.

Includes the following:

Total number of unique schools

Total students

Total budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)


Performed the necessary calculations and then created a DataFrame that summarizes key metrics about each school.

Includes the following:

School name

School type

Total students

Total school budget

Per student budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

Sorted the schools by % Overall Passing in descending order and display the top 5 rows.
Saved the results in a DataFrame called "top_schools".
Sorted the schools by % Overall Passing in ascending order and display the top 5 rows.
Saved the results in a DataFrame called "bottom_schools".

Performd the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school and repeated for the average reading score for students in each grade level.

Create a table that breaks down school performance based on average spending ranges (per student).
Used the scores above to create a DataFrame called spending_summary.

Includes the following metrics in the table:

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.
Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).