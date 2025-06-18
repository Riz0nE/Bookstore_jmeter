# Booking API Load and Stress Test (JMeter)

## 📋 What I Have Done

- Created a JMeter test plan (`booking.jmx`) for login, booking creation, and booking search.
- Performed Load Testing (1, 5, 10, and 20-minute durations).
- Performed Stress Testing by gradually increasing users to identify the bottleneck.
- Generated HTML reports for both load and stress tests.
- Prepared an Excel report containing Load and Stress test.
- Added necessary screenshots and reports for evaluation.

## ⚙️ Prerequisites

- Apache JMeter installed (version 5.5 or above recommended)

## 🚀 How to Run the Tests

1. Open **`booking.jmx`** in JMeter.
2. Adjust the number of users and ramp-up time as needed.
3. To generate HTML reports:
- ```jmeter -n -t booking.jmx -l dmoney.jtl -e -o Reports```
