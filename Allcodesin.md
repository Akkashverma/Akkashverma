- 👋 Hi, I’m @Akkashverma
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Akkashverma/Akkashverma is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.














Importnt codes here ....


**rouding the value to nearest integer **

select round(avg(population)) from city ;


**select the query for finding the minimum and maximum population in city tABLE**

SELECT MAX(POPULATION) - MIN(POPULATION)
FROM CITY;

**using the replace function to replace the zero if by mistaken left in the data while calculating the avg of salary from employee table **

Replace "T" with "M":

SELECT REPLACE('SQL Tutorial', 'T', 'M');

**above is the syntax of replace statement **

select round(avg(salary)) - round(avg(replace(salary, 0, '')))
from EMPLOYEES;

**query to find the max total earning of emplyee **

select (salary*months) as max_earning  , count(name)
from employee
group by max_earning
order by max_earning desc 
limit 1;

**sum of all the values in a column and rounding the decimical upto 2 points **

select round(sum(LAT_N), 2) , round(sum(LONG_W), 2)
from station;




























































