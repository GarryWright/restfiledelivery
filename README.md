GoLang S3 File API
======================


[![Build Status](https://travis-ci.org/GarryWright/restFileDelivery.svg?branch=master)](https://travis-ci.org/GarryWright/restFileDelivery)
[![Build Status](https://drone.io/github.com/GarryWright/restFileDelivery/status.png)](https://drone.io/github.com/GarryWright/restFileDelivery/latest)
[![Coverage Status](https://coveralls.io/repos/GarryWright/restFileDelivery/badge.svg?branch=master&service=github)](https://coveralls.io/github/GarryWright/restFileDelivery?branch=master)

Add a document to the DB
curl -i -X POST -H "Content-Type: application/json" -d '{"clientid": "HSBC", "requestid": "00003", "ricdays": 21, "fileurl": "http://s3-us-west-2.amazonaws.com/garrysbucket/rics2.txt"}' localhost:3000/files
