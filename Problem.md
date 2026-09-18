# C Program Pseudocodes

## 1. Display Student Information Using Different Data Types
BEGIN
    SET student_id (INTEGER) = 101
    SET gpa (FLOAT) = 3.85
    SET grade (CHARACTER) = 'A'

    PRINT "Student ID:", student_id
    PRINT "GPA:", gpa
    PRINT "Grade:", grade
END

## 2. Read and Display a Character Using getchar() and putchar()
BEGIN
    PRINT "Enter a character: "
    READ ch USING getchar()
    PRINT "You entered: "
    WRITE ch USING putchar()
END

## 3. Display a Floating-Point Value Using Different Precision Settings
BEGIN
    SET num (FLOAT) = 12.345678

    PRINT "Default float:", num
    PRINT "2 decimal places (%.2f):", FORMAT(num, 2)
    PRINT "4 decimal places (%.4f):", FORMAT(num, 4)
END
