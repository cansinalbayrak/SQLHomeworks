# **SQL HOMEWORK8**
1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```SQL
CREATE TABLE employee (
	id INTEGER,
	name VARCHAR(50), 
	birthday DATE, 
	email VARCHAR(100)
);
```
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
[MOCKAROO_LINK](https://www.mockaroo.com/)
```SQL
insert into employee (id, name, birthday, email) values (1, 'Eduino', '1955-05-21', 'etrolley0@earthlink.net');
insert into employee (id, name, birthday, email) values (2, 'Teriann', '1936-08-05', 'tvanderson1@lycos.com');
insert into employee (id, name, birthday, email) values (3, 'Glori', '2000-02-02', 'gokynsillaghe2@ifeng.com');
insert into employee (id, name, birthday, email) values (4, 'Giusto', '1963-05-20', 'gcamock3@deviantart.com');
insert into employee (id, name, birthday, email) values (5, 'Kanya', '1936-09-22', 'kgosford4@yellowpages.com');
insert into employee (id, name, birthday, email) values (6, 'Callie', '1958-08-04', 'ckemp5@nps.gov');
insert into employee (id, name, birthday, email) values (7, 'Timoteo', '1921-06-21', 'tfranzonello6@geocities.com');
insert into employee (id, name, birthday, email) values (8, 'Mayor', '1951-09-12', 'mclemendot7@aol.com');
insert into employee (id, name, birthday, email) values (9, 'Lena', '1902-06-25', 'lbelden8@usa.gov');
insert into employee (id, name, birthday, email) values (10, 'Ralph', '1990-06-16', 'rgallandre9@wikipedia.org');
insert into employee (id, name, birthday, email) values (11, 'Sunny', '1960-01-08', 'schaudreta@msn.com');
insert into employee (id, name, birthday, email) values (12, 'Edyth', '1908-06-07', 'ecammomileb@ocn.ne.jp');
insert into employee (id, name, birthday, email) values (13, 'Joel', '1931-03-20', 'jlappingc@g.co');
insert into employee (id, name, birthday, email) values (14, 'Ursala', '1967-01-21', 'utremolletd@cnet.com');
insert into employee (id, name, birthday, email) values (15, 'Alvy', '1945-08-26', 'agalle@twitpic.com');
insert into employee (id, name, birthday, email) values (16, 'Stanfield', '1944-09-15', 'snichollsf@shinystat.com');
insert into employee (id, name, birthday, email) values (17, 'Roxie', '1920-08-09', 'rspraggeg@com.com');
insert into employee (id, name, birthday, email) values (18, 'Ryan', '1925-01-09', 'rvignauxh@si.edu');
insert into employee (id, name, birthday, email) values (19, 'Friedrick', '1975-05-08', 'fsoalli@com.com');
insert into employee (id, name, birthday, email) values (20, 'Sibby', '1991-03-07', 'smccolmj@sina.com.cn');
insert into employee (id, name, birthday, email) values (21, 'Thorin', '1985-02-12', 'twynnek@weebly.com');
insert into employee (id, name, birthday, email) values (22, 'Catherin', '1994-12-22', 'cirwinl@mashable.com');
insert into employee (id, name, birthday, email) values (23, 'Tilda', '1978-06-22', 'tloosemorem@twitter.com');
insert into employee (id, name, birthday, email) values (24, 'Peirce', '1950-06-17', 'pivainn@cocolog-nifty.com');
insert into employee (id, name, birthday, email) values (25, 'Munroe', '1958-07-14', 'mkittleo@latimes.com');
insert into employee (id, name, birthday, email) values (26, 'Nadya', '1955-08-09', 'nvigoursp@behance.net');
insert into employee (id, name, birthday, email) values (27, 'Shelby', '1945-02-28', 'sstarrsq@virginia.edu');
insert into employee (id, name, birthday, email) values (28, 'Blanca', '1937-06-22', 'bpendreyr@wisc.edu');
insert into employee (id, name, birthday, email) values (29, 'Moshe', '2000-07-16', 'mhayballs@facebook.com');
insert into employee (id, name, birthday, email) values (30, 'Bailie', '1955-05-11', 'briccat@ow.ly');
insert into employee (id, name, birthday, email) values (31, 'Chic', '1931-05-02', 'cmccuisu@mapquest.com');
insert into employee (id, name, birthday, email) values (32, 'Grantley', '1937-03-15', 'gshortonv@freewebs.com');
insert into employee (id, name, birthday, email) values (33, 'Wilhelmine', '1950-08-27', 'whigganw@123-reg.co.uk');
insert into employee (id, name, birthday, email) values (34, 'Morgan', '1951-09-01', 'mizsakx@forbes.com');
insert into employee (id, name, birthday, email) values (35, 'Alicea', '1971-03-06', 'aclemoy@mit.edu');
insert into employee (id, name, birthday, email) values (36, 'Brandtr', '1946-01-13', 'bruppelz@discovery.com');
insert into employee (id, name, birthday, email) values (37, 'Selinda', '1928-01-31', 'stompkins10@domainmarket.com');
insert into employee (id, name, birthday, email) values (38, 'Claus', '1961-01-09', 'ckeeney11@de.vu');
insert into employee (id, name, birthday, email) values (39, 'Agneta', '1939-01-31', 'awoollends12@unblog.fr');
insert into employee (id, name, birthday, email) values (40, 'Phylis', '1927-08-31', 'pbewley13@unicef.org');
insert into employee (id, name, birthday, email) values (41, 'Poul', '1904-06-25', 'plamburne14@whitehouse.gov');
insert into employee (id, name, birthday, email) values (42, 'Lorin', '1948-02-21', 'lforsey15@addtoany.com');
insert into employee (id, name, birthday, email) values (43, 'Nara', '1968-03-09', 'nhallgough16@jimdo.com');
insert into employee (id, name, birthday, email) values (44, 'Katuscha', '1924-09-18', 'kpetts17@prnewswire.com');
insert into employee (id, name, birthday, email) values (45, 'Philippa', '1929-09-23', 'pshimony18@xing.com');
insert into employee (id, name, birthday, email) values (46, 'Loise', '1914-01-14', 'lrojas19@multiply.com');
insert into employee (id, name, birthday, email) values (47, 'Harrie', '1966-09-21', 'hthinn1a@g.co');
insert into employee (id, name, birthday, email) values (48, 'Lea', '1951-01-25', 'larzu1b@ebay.com');
insert into employee (id, name, birthday, email) values (49, 'Danita', '1901-09-27', 'dcostigan1c@amazonaws.com');
insert into employee (id, name, birthday, email) values (50, 'Loralie', '1910-04-30', 'lsmellie1d@opera.com');
```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```SQL
UPDATE employee
SET name = 'Kibare',
	birthday = '1999.12.11',
	email = 'kibare@gmail.com'
WHERE id <6;
```
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```SQL
DELETE FROM employee
WHERE name LIKE 'Kiba%';
```
