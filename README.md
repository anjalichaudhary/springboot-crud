## SpringBoot Java App

### Steps to run
    1. mvn clean package
    2. java -jar target/springbootcrudexample-0.0.1-SNAPSHOT.jar

### To run test cases 
    mvn clean test

### To Test
GET

    curl --location --request GET 'https://testlab.fsd-mygreatlearning.net:8080/employee/' \
    --header 'Content-Type: application/json'


POST

    curl --location --request POST 'https://testlab.fsd-mygreatlearning.net:8080/employee' \
    --header 'Content-Type: application/json' \
    --data-raw '{
        "first_name": "Test 2",
        "last_name": "Java",
        "gender": "M",
        "birth_date": "1996-12-07",
        "hire_date": "2011-12-07"
    }'