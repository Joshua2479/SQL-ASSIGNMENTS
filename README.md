show schemas;

show tables;

CREATE database bako;

USE bako;

CREATE table bako(
id INT,
first_name VARCHAR(50),
last_name VARCHAR(50),
gender VARCHAR(10),
location VARCHAR(50));
 
 INSERT INTO bako VALUES(1,'Ajijola','joshua','male','akala'),
                        (2,'Oluwatoba','adekunle','male','dugbe'),
                        (3,'olamide','bamidele','male','dugbe'),
                        (4,'ifeoluwa','ajoye','male','iwo-road'),
                        (5,'temitope','dosunmu','male','dugbe'),
                        (6,'olumide','ajona','male','akobo'),
                        (7,'opeyemi','ishola','male','iwo-road')
                        ;
  SELECT *
  FROM bako;



