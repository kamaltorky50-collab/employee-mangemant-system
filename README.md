[README.md](https://github.com/user-attachments/files/33283345/README.md)
# employee-mangemant-system
# Employee Management System

**Student name:** كمال احمد كمال خليل تركي **
**Student ID:** 2200103 **

## Description
Java implementation of the supplied UML diagram: abstract `Employee`, `CommissionEmployee`,
`MonthlyEmployee`, `HourlyEmployee`, `Department`, and `Gender`. Includes inheritance,
constructors, getters/setters, salary calculations, employee management, demo data and tests.

## Requirements
JDK 8 or later. No external libraries.

## Structure
```text
src/Main.java
src/model/{Employee,CommissionEmployee,MonthlyEmployee,HourlyEmployee,Department,Gender}.java
src/test/MainTest.java
README.md
```

## Compile and run
From the project root:
```bash
mkdir -p out
javac -d out src/model/*.java src/Main.java src/test/MainTest.java
java -cp out Main
java -ea -cp out MainTest
```
On Windows Command Prompt, use `mkdir out`.

## GitHub
Replace the student name and ID above. Create a public repository without initializing a README, then run:
```bash
git init
git add .
git commit -m "Implement employee management UML diagram"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```
Submit your repository URL in the assignment Google Form.
