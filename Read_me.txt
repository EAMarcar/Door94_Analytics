## Read me for Demo_load project

Step 1 
Create data needed for set up
      Schools (including district column)  => Demo_schools
      Programs  => Demo_programs
      Staff?
      ??
Step 2
Use set-up data to create students   => Demo_students
      Assign schools

Step 3
Create sections (use programs)

Step 4
Load students and sections to Door94 (Tiffani does magic)

Step 5
Use output from Door94 to create Student/section file

A file from Door94 containing section IDs and another containing Student IDs are read in. These files are matched to Section and Student information respectively so that the output file will contain the necessary Door94 IDs for the Student/section records to be created.

This step also uses programs and staff data output from CORE.

Step 6
Tiffani does rest of magic in Door94

Step 7
Extract files from Door94 are produced and loaded into Power BI analytics data model.


Final counts for current run:
------------------------------
Schools: 16  (added to existing test environment which had a few fake schools)
Programs: TBD
Staff: 32  (two per school, added to existing names)
Students: 800  (50 per school)
Sections: 48 (3 per school)


Questions:
-----------
Is there a way to automate session input?  Yes - bulk
How many students?  (my preference: at least 200)  100/school   => Currently using 50 
How many schools? (at least 10 from aat least 3 districts) => Changed to 16, 4 from each of 4 districts
How many programs?  More generic - 10   => we have 7 so far
Start and end dates; school year? 20-21 FY => School year on students file set to "2020-2021"
Randomly assigned variables - levels OK?  => need to discuss some values and ranges 
Below here not started: 
How many sections?  Teen, etc   
How many sessions?  (at least 3 per section) based on section












end
