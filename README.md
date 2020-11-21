# Attendance-Project
I have a data set containing attendance of the students from a university. I have to clean the data and perform certain tasks on it.
This data contains a lot of anomalies like:
- Columns names present in multiple rows.
- Space in front of column names and the data. When printed,'\xa0' appears in front of every string
- '---' present in the data, different data types of columns, and so on...

Tasks to be performed:
1.  Students with attendance < 75% in even one subject are to be reported in a separate file called "Make up list".
2.  The "Make up list" must show all of the above headers and details, e.g. including serial number, student roll no, uid, subject, % attendance.
3.  Make up list for theory and practical must be separate.
4.  Any other relevant headers or details may be added in the "Make up list".
5.  Students not in the "Make up list" must be separately listed in a file called "Attendance_OK" file.
6.  All input and output files are required to be CSV files.
