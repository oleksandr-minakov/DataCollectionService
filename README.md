# Data collection service
Application is designed to collect data from users.

## Technologies ##
1. IDE: IntelliJ IDEA 
2. Java 8
3. Hibernate 5.2.5.Final
4. Play Framework 2.5.x (scala-templating) 
5. Database: PostgreSQL 9.4
6. WebSockets
7. Bootstrap, HTML, CSS, JavaScript/JQuery 

## How to use ##
####For unauthorized users####
1. Response collecting page. It give possibility to fill all active field created on page #2. Not required fields can be left empty. Resetting form will clean out all entered data.

####For authorized users####

2. Field create/edit page. Here admin be able to create new fields with definite number of properties. All properties are required. After saving new field user will be redirected to page #3. Page available on path domainname.com/fields

3. List of fields page. Page available by direct link. Here all Fields stored in database will be listed. Admin able to create, edit, and delete fields. Removing fields done with AJAX. Page available on path domainname.com/fields

4. Responses page. All the responses completed by users are collected here. They are appear in this list automatically after submitting. Columns on this page correspond with each field created on page #2. Page available on path domainname.com/responses.

## Development ##
####IntelliJ IDEA####
Open build.sbt file in your IDE using File -> Open.
