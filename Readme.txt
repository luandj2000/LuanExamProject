The following file paths need to be changed before running the automation tests.

1: Go to the config.properties file and change the excelDataDir path:

From	C:\\InspiredExam\\LuanExamProject\\
To	C:\\LuanExamProject\\ 
Alternatively	Add the directory:  InspiredExam on your c drive and clone the project to that directory.


Running automation tests:

There are no spesific profiles for this project, only a default one.
Therefore the standard command can be used to run the project's tests:  mvn test

