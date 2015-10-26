[![Build Status](https://travis-ci.org/dregules/takeaway-backend.svg?branch=master)](https://travis-ci.org/dregules/takeaway-backend)
[![Code Climate](https://codeclimate.com/github/dregules/takeaway-backend/badges/gpa.svg)](https://codeclimate.com/github/dregules/takeaway-backend)

SUMMARY
==================
Written the logic for a take-away delivery tool that uses the Twilio API for notifications.


Instructions
-------
`bundle install`

For testing

run `rspec`

USER STORIES
-----
```
As a customer
So that I can check if I want to order something
I would like to see a list of dishes with prices

As a customer
So that I can order the meal I want
I would like to be able to select some number of several available dishes

As a customer
So that I can verify that my order is correct
I would like to check that the total I have been given matches the sum of the various dishes in my order

As a customer
So that I am reassured that my order will be delivered on time
I would like to receive a text such as "Thank you! Your order was placed and will be delivered before 18:52" after I have ordered
```

Additional Features to Build
-----
* Order food via sms
* Continuous notifications through Twilio
