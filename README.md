# Quiz_Advanced_Databases
Repository in which the solution to the advanced database quiz shall be stored 

IMPORTANT INFORMATION:

The quiz contains the solution to the following items:

Do the following:

1. Create a bigtablespace with the name "big_tbs_your_name" example 'big_tbs_andres". It should contains one datafile of 1Gb
2. Create a tablespace named "quiz" with three datafiles, each of them of 200Mb. When more space is required, 600 kilobyte extents will be added up to a maximum size of 100 Mb
3. Create a profile with:
  No limit for sessions.
  No limit for CPU per session
  No limit for attempts failed
  Idle time of 15 minutes
4. Create a user with the default tablespace created in the item 2 and assign profile created in last step.
5. Allow the user to connect to the application
