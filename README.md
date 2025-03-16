## Schema

'''sql 

SELECT * 
FROM netflix 
WHERE type = 'TV Show'
AND SPLIT_PART(duration, ' ', 1)::INTEGER > 5;

,,,