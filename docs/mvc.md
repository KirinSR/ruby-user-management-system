
# Model View Controller (MVC) Pattern

GET /about HTTP/1.1
Host: 127.0.0.1

## Routes
Matchers for the URL that is requested

GET for "/about"

I see you requested "/about", we'll give you that to the AboutController to handle

## Models
Databse Wrapper

User 
* query for records
* wrap individual records

## Views
Your response body content
* HTML
* CSV
* PDF
* XML
This what sent back to browser and get displayed

## Controller
Decide how to process a request and define a response