SELECT Genre, ROUND(Global_Sales) AS Rounded_Global_Sales, Critic_Score
FROM sales_genre;

SELECT Genre, ROUND(Global_Sales) AS Rounded_Global_Sales, Critic_Score
FROM sales_genre
WHERE Critic_Score > 0;

SELECT Genre, ROUND(Global_Sales) AS Rounded_Global_Sales, Critic_Score
FROM sales_genre
WHERE Critic_Score > 0
ORDER BY Critic_Score DESC;
