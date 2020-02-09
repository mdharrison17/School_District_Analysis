# School_District_Analysis
## Challenge 4 Learning Outcome Written Report

This challenge uses Jupyter Notebook and Pandas library to create data frames of school data using logical operations with conditionals, retrieve data from data frames, merging data frames, filter, slice and sort dataframes and clean and replace data within the data frames.  We then look at the data and create an analysis after the data has been cleaned up.  

9th Grade students math and reading scores at Thomas High have been changed to NaN per administrators.  The following is an analysis on how the datasets before and after the changes compare.

1.	How is the district summary affected?
The district summary was barely affected by the change the change in grades.  Percent passing math, percent passing reading and percent overall passing each roughly went down 1 percent.

2.	How is the school summary affected?
The school summary was only affected by changes in the row for Thomas High School.  Percent passing math went down about 36%, percent passing reading went down about 28%, and overall passing for Thomas High School went down about 26%.  Information for all other rows remain the same.

3.	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to other schools?
Thomas High School was second top school, after changing the ninth graders grades, they dropped off of the Top 5 list (down to 8th), but did not make the bottom list.  There were still other worse performing schools overall.

4.	How does replacing the ninth-grade scores affect the math and reading scores:

a.	By grade – Only Thomas High School was affected, 9th grade scores of course, were NaN.

b.	By school spending – Thomas High School was in the range of $630-$644, which means this is the only range that was affected.  Percent passing math went down 6%, went down 7% and overall percent passing went down 7 percent.

c.	By school size – Thomas High School was a medium school, so this is the only row data that was affected.  Percent passing math went down 6%, percent passing reading went down 6% and overall percent passing went down 6% as well.

d.	By school type – There are two school types, Thomas High School is a charter school, so the information for district schools is not affected.  The Percent passing math and percent passing reading both went down 4%, overall passing percent went down 3%.
