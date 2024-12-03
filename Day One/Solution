SELECT customer_name, COUNT(DISTINCT activity) AS Number_Of_Activities
FROM rentals
GROUP BY customer_name
HAVING COUNT(DISTINCT activity) > 1;
