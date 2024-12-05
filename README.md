# grupaa-GMari
https://github.com/GiancarloMari/grupaa-GMari

SELECT biljka.naziv
FROM biljka
JOIN vrsta ON biljka.vrsta = vrsta.id
WHERE vrsta.naziv = 'Ružovke'
AND biljka.cijena <=5
ORDER BY biljka.naziv ASC;
