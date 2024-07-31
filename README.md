# Shop-jpa-backend
shopping mall Back-end Study Repository

<br>

### Database Setting
```sql
-- 데이터베이스 생성
create database shop default character set utf8 collate utf8_general_ci;
```

<br>

### properties 설정 확인

``` properties
# MySQL 설정 확인
spring.datasource.url=jdbc:mysql://localhost:3306/shop?serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=1234

# 리소스 경로 확인
itemImgLocation=C:/shop/upload/img/item
uploadPath=file:///C:/shop/
```