# GO REST Load Testing 

## Description
This load test using the GoRest public API (https://gorest.co.in/public/v2/users) using JMeter.

## Necessary Tools
- Apache JMeter (version 5.4 or higher)
- Java (version 8 or higher)
- GoRest API Token

----
## Test Analise

### Data Test

- **Endpoint:** https://gorest.co.in/public/v2/users
- **Method:** GET
- **Total Samples:** 300
- **Tool:** Apache JMeter

### Summary of Results

- **Average Response Time:** 5501 ms (High value for a GET request)
- **Minimum Response Time:** 476 ms (Good value)
- **Maximum Response Time:** 10893 ms (High value for a request)
- **Standard Deviation:** 2973.62 ms (High variation between response times, low consistency)
- **Error Rate:** 14.00% (High error rate - 42/300 requests failed)
- **Throughput:** 27.0 requests per second (...)
- **Received Data:** 55.23 KB/sec (...)
- **Sent Data:** 6.65 KB/sec (...)
- **Average Bytes per Request:** 2092.2 bytes (...)

![Sumary Report](/summary-report.png)
