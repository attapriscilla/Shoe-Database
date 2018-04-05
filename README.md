# Shoe-Database

CREATE TABLE Shoe (
   id INT NOT NULL AUTO_INCREMENT ,
   price INT NOT NULL,
   size INT NOT NULL,
   heel_length TEXT NOT NULL,
   Description TEXT NOT NULL,
   PRIMARY KEY (id)
);
CREATE TABLE Rating (
   id INT NOT NULL AUTO_INCREMENT ,
   rating INT NOT NULL,
 Shoe_id INT NOT NULL,
   PRIMARY KEY (id)
);

CREATE TABLE Image (
   id INT NOT NULL AUTO_INCREMENT ,
   image BLOB NOT NULL,
Shoe_id INT NOT NULL,
   PRIMARY KEY (id)
);
Insert into Shoe (price, size, heel_length, description)
values ( 50, 12, 'short',' black heels');
Insert into Shoe (price, size, heel_length, description)
values ( 50, 12, 'short',' black heels');
Insert into Shoe (price, size, heel_length, description)
values ( 50, 12, 'short',' black heels');
Insert into Shoe (price, size, heel_length, description)
values ( 50, 12, 'short',' black heels');
Insert into Shoe (price, size, heel_length, description)
values ( 50, 12, 'short',' black heels');
Insert into Shoe (price, size, heel_length, description)
values ( 50, 12, 'short',' black heels');
Insert into Shoe (price, size, heel_length, description)
values ( 50, 12, 'short',' black heels');
Insert into Shoe (price, size, heel_length, description)
values ( 50, 12, 'short',' black heels');
Insert into Shoe (price, size, heel_length, description)
values ( 50, 12, 'short',' black heels');
Insert into Shoe (price, size, heel_length, description)
values ( 50, 12, 'short',' black heels');
Insert into Shoe (price, size, heel_length, description)
values ( 50, 12, 'short',' black heels');
Insert into Shoe (price, size, heel_length, description)
values ( 500, 12, 'high heels',' black heels');
