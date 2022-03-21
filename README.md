# Odev8.sql

--1.test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

``CREATE TABLE employee(
	id INT,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);``

--2.Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

``insert into employee (id, name, birthday, email) values (1, 'Paul Malter', '2021-11-10', 'pmalter0@nytimes.com');
insert into employee (id, name, birthday, email) values (2, 'Hobie Rabbe', '2021-08-09', 'hrabbe1@sfgate.com');
insert into employee (id, name, birthday, email) values (3, 'Ainslie Lethieulier', '2021-04-23', 'alethieulier2@ehow.com');
insert into employee (id, name, birthday, email) values (4, 'Lowell Fairbard', '2022-02-18', 'lfairbard3@icio.us');
insert into employee (id, name, birthday, email) values (5, 'Egan Faux', '2021-07-01', 'efaux4@yellowpages.com');
insert into employee (id, name, birthday, email) values (6, 'Tricia Dance', '2022-02-15', 'tdance5@wikipedia.org');
insert into employee (id, name, birthday, email) values (7, 'Gabbie Ternault', '2022-03-06', 'gternault6@paypal.com');
insert into employee (id, name, birthday, email) values (8, 'Shelly O''Beirne', '2021-11-29', 'sobeirne7@ask.com');
insert into employee (id, name, birthday, email) values (9, 'Alleyn Galton', '2021-07-14', 'agalton8@businessweek.com');
insert into employee (id, name, birthday, email) values (10, 'Langston Meeron', '2021-04-21', 'lmeeron9@cafepress.com');
insert into employee (id, name, birthday, email) values (11, 'Cindra Huerta', '2021-10-20', 'chuertaa@netvibes.com');
insert into employee (id, name, birthday, email) values (12, 'Verene Jessep', '2021-09-11', 'vjessepb@mediafire.com');
insert into employee (id, name, birthday, email) values (13, 'Veronika Jaime', '2021-10-13', 'vjaimec@moonfruit.com');
insert into employee (id, name, birthday, email) values (14, 'Travis Godby', '2021-09-29', 'tgodbyd@apple.com');
insert into employee (id, name, birthday, email) values (15, 'Blakelee Sayles', '2021-06-12', 'bsaylese@apple.com');
insert into employee (id, name, birthday, email) values (16, 'Alex Rivallant', '2021-06-04', 'arivallantf@aol.com');
insert into employee (id, name, birthday, email) values (17, 'Sophia Tipton', '2021-06-15', 'stiptong@foxnews.com');
insert into employee (id, name, birthday, email) values (18, 'Engelbert Schwerin', '2022-03-15', 'eschwerinh@psu.edu');
insert into employee (id, name, birthday, email) values (19, 'Arlen Blessed', '2021-03-27', 'ablessedi@craigslist.org');
insert into employee (id, name, birthday, email) values (20, 'Rubina Antonov', '2022-03-06', 'rantonovj@lycos.com');
insert into employee (id, name, birthday, email) values (21, 'Lemmie Seifert', '2021-10-26', 'lseifertk@jiathis.com');
insert into employee (id, name, birthday, email) values (22, 'Inez Hampe', '2021-05-19', 'ihampel@usda.gov');
insert into employee (id, name, birthday, email) values (23, 'Melicent Ucchino', '2022-02-05', 'mucchinom@i2i.jp');
insert into employee (id, name, birthday, email) values (24, 'Ileane Berthot', '2021-10-07', 'iberthotn@globo.com');
insert into employee (id, name, birthday, email) values (25, 'Donella Nisot', '2021-07-23', 'dnisoto@java.com');
insert into employee (id, name, birthday, email) values (26, 'Mab Keener', '2022-03-12', 'mkeenerp@vistaprint.com');
insert into employee (id, name, birthday, email) values (27, 'Zonnya Hadlee', '2021-12-22', 'zhadleeq@state.gov');
insert into employee (id, name, birthday, email) values (28, 'Andras Lenormand', '2021-04-16', 'alenormandr@printfriendly.com');
insert into employee (id, name, birthday, email) values (29, 'Garvy Maleham', '2021-10-25', 'gmalehams@ihg.com');
insert into employee (id, name, birthday, email) values (30, 'Cart Raynham', '2021-07-22', 'craynhamt@wunderground.com');
insert into employee (id, name, birthday, email) values (31, 'Ilsa Bolgar', '2021-10-06', 'ibolgaru@berkeley.edu');
insert into employee (id, name, birthday, email) values (32, 'Jo ann Culshaw', '2021-10-05', 'jannv@bbc.co.uk');
insert into employee (id, name, birthday, email) values (33, 'Sauncho Richin', '2021-09-14', 'srichinw@wikipedia.org');
insert into employee (id, name, birthday, email) values (34, 'Cy Elloway', '2021-09-10', 'cellowayx@webeden.co.uk');
insert into employee (id, name, birthday, email) values (35, 'Marylou Bantham', '2021-06-22', 'mbanthamy@oracle.com');
insert into employee (id, name, birthday, email) values (36, 'Basilius Everson', '2021-10-06', 'beversonz@apple.com');
insert into employee (id, name, birthday, email) values (37, 'Tildy Albone', '2021-04-22', 'talbone10@home.pl');
insert into employee (id, name, birthday, email) values (38, 'Sally Shade', '2022-02-07', 'sshade11@zdnet.com');
insert into employee (id, name, birthday, email) values (39, 'Jud Kinningley', '2021-11-09', 'jkinningley12@cpanel.net');
insert into employee (id, name, birthday, email) values (40, 'Thaddus Spradbrow', '2021-10-01', 'tspradbrow13@biblegateway.com');
insert into employee (id, name, birthday, email) values (41, 'Ranique Byk', '2021-06-14', 'rbyk14@cbsnews.com');
insert into employee (id, name, birthday, email) values (42, 'Malissia Yankeev', '2021-12-26', 'myankeev15@hatena.ne.jp');
insert into employee (id, name, birthday, email) values (43, 'Berthe Dodsley', '2021-09-05', 'bdodsley16@issuu.com');
insert into employee (id, name, birthday, email) values (44, 'Sutton Oliveras', '2021-09-26', 'soliveras17@sitemeter.com');
insert into employee (id, name, birthday, email) values (45, 'Cyb Rosendall', '2022-01-21', 'crosendall18@hatena.ne.jp');
insert into employee (id, name, birthday, email) values (46, 'Melissa Guesford', '2021-04-28', 'mguesford19@ucla.edu');
insert into employee (id, name, birthday, email) values (47, 'Emma Dartan', '2021-07-28', 'edartan1a@gnu.org');
insert into employee (id, name, birthday, email) values (48, 'Eleanora Di Roberto', '2022-01-13', 'edi1b@nationalgeographic.com');
insert into employee (id, name, birthday, email) values (49, 'Mattias McNeely', '2021-09-19', 'mmcneely1c@psu.edu');
insert into employee (id, name, birthday, email) values (50, 'Ruprecht Adie', '2022-03-08', 'radie1d@surveymonkey.com');``

--3.Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

``UPDATE employee
SET name = 'Odetta Byk'
WHERE id>45;

UPDATE employee
SET name = 'Paul Malter',
    birthday = '1988-07-01',
	  email = 'pmalter0@nytimes.com'
WHERE id = 10;

UPDATE employee
SET name = 'Lowell Fairbard',
	birthday = '1987-02-01',
	email = 'lfairbard3@icio.us'
WHERE id = 42;

UPDATE employee
SET name = 'Penny Mattosoff',
	birthday = '1937-12-08',
	email = 'pmattosoff1d@blinklist.com'
WHERE id = 35;

UPDATE employee
SET name = 'Melissa Guesford',
	birthday = '2021-04-28',
	email = 'mguesford19@ucla.edu'
WHERE id = 25;
``

--4.Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

``DELETE FROM employee
WHERE id IN (1,4,7,12,22);``
