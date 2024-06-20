# Darya Boginskaya
## Junior Frontend Developer
## Contact information:
**Phone:** +357 94 485 639


**E-mail:** daria.boginska96@gmail.com


**Telegram:** @dariaboginska


**Discord:** Darya Boginskaya(@daria9696)


**GitHub:** [daria9696](https://github.com/daria9696)


## About Myself:
At the moment, I am independently acquiring basic knowledge in web page layout, solving logical problems and writing practice code.


 My goal is to contribute to innovative projects and continuously grow as a software developer. Although I am at the beginning of my career, my dedication to learning and exploring new technologies has equipped me with a solid foundation in coding and problem-solving.


 Despite not having professional experience yet, I have engaged in various personal projects and online courses to hone my skills. I am eager to apply my knowledge in a practical setting and contribute to a dynamic team.


 I am confident that my enthusiasm for programming and my drive to excel will make me a valuable addition to your team.


 ## Skills
 *HTML 5
 *CSS/SASS
 *Python (Foundations, OOP, pandas)
 *JavaScript (basics)
 *MySQL/PostgreSQL (DDL, DML, DCL, TCL)
 *SQL for Analysis (Window Function/ Window Frames: PL/pgSQL)
 *Git/GitHub
 *Methodologies of work (SCRUM, Kanban)
 *VS Code, IntelliJ IDEA
 *Dbeaver
 *Pycharm
 *Jupiter


## Code Examples
<span style="color:grey">SELECT c.name, sum(amount) AS total_income
FROM payment p --payment, because we want To know total amount per rental, so we join the payment and rental tables
    JOIN rental r ON r.rental_id = p.rental_id 
        JOIN inventory i ON r.inventory_id = i.inventory_id --inventory, film_category anf film tables just conjuctive tables
            JOIN film f ON i.film_id = f.film_id 
                JOIN film_category fc ON f.film_id = fc.film_id 
                     JOIN category c ON fc.category_id = c.category_id  -- we search only those customer_id from rental table which is are correspond to our subquery  
                         WHERE r.customer_id IN (SELECT cus.customer_id --here in subquery we join customer, address,city, country, to select customers who live in United States.
                                                       FROM customer cus
                                                           JOIN address a ON cus.address_id = a.address_id 
                                                               JOIN city cit ON a.city_id = cit.city_id
                                                                    JOIN country cou ON cit.country_id = cou.country_id 
                                                                        WHERE cou.country = 'United States')
GROUP BY c.name --group by name of category to know total amount per each category 
ORDER BY total_income DESC --sorting by sum of income in descending order 
FETCH FIRST 3 ROWS WITH TIES  --here we want TO find top 3 category-movies. I chose "fetch first n rows with ties" IN CASE IF we have additional category film WITH the same total_income AS we chosen  *grey* text</span>.



## Education
-**The University of Environment and Life Sciences** (MSc - Bioinformatics) 2019-2022


-**The University of Wroclaw** (BSc - Biotechnology) 2016-2019

## Languages
-**English:** (Advanced, according to [EPAM English test result](https://examinator.epam.com/passing/attendances/791480))


-**Russian:** (Native)


-**Ukranian:** (Intermediate)


-**Polish:** (Advanced)
