```SQL
/*To get all the managers in the database by selecting who has the job title manager*/
SELECT * FROM EMPLOYEE
WHERE Job_title = 'Manager';

/*Or if the manager is equal to NULL*/
SELECT * FROM EMPLOYEE
WHERE Manager IS NULL;
```
