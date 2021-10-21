## create database BBS;
 BBS 데이터베이스 생성
 
 ## use BBS;
BBS 데이터 베이스 사용

## user 테이블 생성
CREATE TABLE user (    
userID varchar(20) not null,    
userPassword varchar(20),    
userName varchar(20),    
userGender varchar(1),    
userDate date,    
primary key (userID)    
);

