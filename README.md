# CS50L Database Design Assignment

1. How many actors have the first name Meryl?
   Answer: Used SQL query with `LIKE 'Meryl %'` on the `people` table to count actors named Meryl.

2. How many movies about Titanic?
   Answer: Counted movies with `LIKE '%Titanic%'` on the `movies` table.  
   Note: May not be fully accurate, as some Titanic-related movies may not have "Titanic" in the title, and some titles with "Titanic" may not be about the ship.

3. How many movies has Kevin Bacon acted in? 
   Answer: Counted movies by joining `cast_members` and `people` tables for Kevin Bacon.
