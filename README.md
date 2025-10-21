# Hotel Booking API Test Suite
Automated API testing project using Postman & Newman.

## Files
- Hotel_Booking_API_Suite.postman_collection.json — Collection
- Mini_Project.postman_environment.json — Environment
- BookingReport.html — Newman HTML Report

// newman run Hotel_Booking_API_Suite.postman_collection.json -e Mini_Project.postman_environment.json

//cd C:\Users\hp\Postman\files newman run "Hotel_Booking_API_Suite.postman_collection.json" ^
 -e "Mini_Project.postman_environment.json" ^
 -r cli,html --reporter-html-export "BookingReport.html"

