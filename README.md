# sql_patika_odev_4  www.patika.dev
sql_patika_odev_4
--answer 1
SELECT DISTINCT replacement_cost FROM film;
--cevap 2
SELECT COUNT(DISTINCT replacement_cost) FROM film;
--CEVAP 3
SELECT COUNT(title) FROM film
WHERE title LIKE 'T&' AND rating = 'G' ;
--cevap 4
SELECT COUNT(country) FROM country
WHERE country LIKE '_____'
--cevap 5
SELECT COUNT(city) FROM city;
WHERE city ILIKE '%r'
