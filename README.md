Student Gradebook Analyzer

Project Overview:

Student Gradebook Analyzer is a Python project developed using the Pandas library. It reads student data from a CSV file and performs various statistical analyses such as Average, Median, Maximum, Minimum, Grade Calculation, and Student Ranking.

This project demonstrates basic data analysis using Python and Pandas.



Features:

- Read student data from a CSV file
- Calculate Average marks of each student
- Calculate Median marks
- Find Maximum marks
- Find Minimum marks
- Assign Grades based on Average
- Sort students according to Average marks
- Display ranked student list



Technologies Used:

- Python
- Pandas



Dataset:

The dataset contains the following columns:

- Roll_No
- Name
- Maths
- Physics
- Chemistry
- English

Example:

| Roll_No | Name | Maths | Physics | Chemistry | English |
|---------|------|--------|----------|------------|----------|
|101|Aman|85|78|82|88|
|102|Rahul|92|85|89|91|



Calculations Performed:

For every student, the program calculates:

- Average Marks
- Median Marks
- Maximum Marks
- Minimum Marks
- Grade



Grade Criteria:

| Average Marks | Grade |
|---------------|-------|
|90 - 100       |    A+ |
|80 - 89        |    A  |
|70 - 79        |    B+ |
|60 - 69        |    B  |
|50 - 59        |    C  |
|40 - 49        |    D  |
|Below 40       |  FAIL |



Sorting:

Students are sorted in descending order based on their Average Marks to identify the top performers.



Required Library:

Install Pandas before running the project.

```bash
pip install pandas
```



How to Run:

1. Place the `STUDENTS.csv` file in the project folder.
2. Install Pandas.
3. Run the Python script.

```bash
python student_gradebook.py
```



Output:

The program generates the following new columns:

- Average
- Median
- Maximum
- Minimum
- Grade

Students are displayed in descending order of Average Marks.



Project Structure:

```
Student Gradebook Analyzer/
│
├── STUDENTS.csv
├── student_gradebook.py
└── README.md
```



Future Improvements:

- Add Total Marks column
- Calculate Student Rank
- Generate Bar Chart and Pie Chart
- Subject-wise Analysis
- Export processed data into a new CSV file
- Interactive menu using input()



Author:

**Prerna**

Student Gradebook Analyzer Project using Python and Pandas.
