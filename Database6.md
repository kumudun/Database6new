# Week 5
## Exercise 7 -Uptade Queries
### Question 1
update game 
set location = (select ident from airport where name = 
"Nottingham Airport"), co2_consumed = co2_consumed+500 
where screen_name = "Vesa"; 
select*from game;
![screenshot](Screenshot-Q-1.png)

### Question 2
![screenshot](Screenshot-Q-2.png)

### Question 3
delete from goal_reached;
![screenshot](Screenshot-Q-3.png)

### Question 4
 delete from game;
 ![screenshot](Screenshot-Q-4.png)