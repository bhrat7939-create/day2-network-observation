# Day 2 - DNS, TCP, TLS, HTTP Exploration

## Website Tested

shorterloop.com

### Request 1

GET /
Status: 200 OK

Type: document

Header:
content-type: text/html

### Request 2

GET /favicon.ico

Status: 200 OK

Type: image

Header:
content-type: image/x-icon

### Request 3

GET main.css

Status: 200 OK

Type: stylesheet

Header:
content-type: text/css

### Request 4

GET main.js

Status: 200 OK

Type: script

Header:
content-type: application/javascript

## DNS Lookup

nslookup shorterloop.com

Result:
76.76.21.21
