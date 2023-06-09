1#SORU - actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.

1#CEVAP - (SELECT first_name FROM actor)
UNION
(SELECT first_name FROM customer);

1#<img width="960" alt="1" src="https://github.com/ugurcnsft/Patika-SQL-Odev-11/assets/129968939/7d0e128c-6bfa-4ad1-ba68-b222df5d2877">

2#SORU - actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.

2#CEVAP - ![image](https://github.com/ugurcnsft/Patika-SQL-Odev-11/assets/129968939/f74cf14f-8ab0-4017-833b-f0ac72043afb)

2# <img width="960" alt="2" src="https://github.com/ugurcnsft/Patika-SQL-Odev-11/assets/129968939/5c793608-98ac-4fc4-b205-1c8b8db8e831">

3#SORU - actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.

3#CEVAP - (SELECT first_name FROM actor)
EXCEPT
(SELECT first_name FROM customer);

3# <img width="960" alt="3" src="https://github.com/ugurcnsft/Patika-SQL-Odev-11/assets/129968939/945c39ba-9eb6-4ffa-b6bf-341d83808e5f">
