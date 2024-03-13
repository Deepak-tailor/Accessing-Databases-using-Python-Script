# Accessing-Databases-using-Python-Script
Project on pythn


-*******ouput should be like this*******_


Table is ready
SELECT * FROM Department
    DEPT_ID   DEP_NAME MANAGER_ID LOC_ID
0       Rav      Ahuja    TORONTO     CA
1      Raul      Chong    Markham     CA
2      Hima  Vasudevan    Chicago     US
3      John     Thomas   Illinois     US
4     Alice      James   Illinois     US
5     Steve      Wells   Illinois     US
6   Santosh      Kumar   Illinois     US
7     Ahmed    Hussain   Illinois     US
8     Nancy      Allen   Illinois     US
9      Mary     Thomas   Illinois     US
10  Bharath      Gupta   Illinois     US
11   Andrea      Jones   Illinois     US
12      Ann      Jacob   Illinois     US
13     Amit      Kumar   NewDelhi     IN
SELECT DEP_NAME FROM Department
     DEP_NAME
0       Ahuja
1       Chong
2   Vasudevan
3      Thomas
4       James
5       Wells
6       Kumar
7     Hussain
8       Allen
9      Thomas
10      Gupta
11      Jones
12      Jacob
13      Kumar
SELECT COUNT(*) FROM Department
   COUNT(*)
0        14
Data appended successfully
theia@theia-deepak231451:/home/project$ python3.11 db_code.py
Table is ready
SELECT * FROM Department
    DEPT_ID   DEP_NAME MANAGER_ID LOC_ID
0       Rav      Ahuja    TORONTO     CA
1      Raul      Chong    Markham     CA
2      Hima  Vasudevan    Chicago     US
3      John     Thomas   Illinois     US
4     Alice      James   Illinois     US
5     Steve      Wells   Illinois     US
6   Santosh      Kumar   Illinois     US
7     Ahmed    Hussain   Illinois     US
8     Nancy      Allen   Illinois     US
9      Mary     Thomas   Illinois     US
10  Bharath      Gupta   Illinois     US
11   Andrea      Jones   Illinois     US
12      Ann      Jacob   Illinois     US
13     Amit      Kumar   NewDelhi     IN
SELECT DEP_NAME FROM Department
     DEP_NAME
0       Ahuja
1       Chong
2   Vasudevan
3      Thomas
4       James
5       Wells
6       Kumar
7     Hussain
8       Allen
9      Thomas
10      Gupta
11      Jones
12      Jacob
13      Kumar
SELECT COUNT(*) FROM Department
   COUNT(*)
0        14
