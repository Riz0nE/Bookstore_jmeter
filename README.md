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

## Adding Screenshots
## Load Test
#### Load Test for 1 minutes (Summary Report) 
![LT1](https://github.com/user-attachments/assets/7a88a45f-681d-463a-ba05-f651f17de632)
#### Load Test for 5 minutes (Summary Report and HTML Report)
![LT2](https://github.com/user-attachments/assets/19e3f60a-8ca5-4203-b541-12637491ee9c)
![LTR5min](https://github.com/user-attachments/assets/f6ceb7e5-e969-4722-8071-4d1b9d37a263)
#### Load Test for 10 minutes (Summary Report and HTML Report)
![LT3](https://github.com/user-attachments/assets/bbe10213-0e57-42bd-8f21-baff4888a652)
![LTR10min](https://github.com/user-attachments/assets/5bb2027b-03eb-4f79-b5e2-20e420b1b7df)
#### Load Test for 10 minutes (Summary Report for Actual TPS)
![LTR10min with 1450](https://github.com/user-attachments/assets/fd2b39f3-53e4-463e-80c8-86b63ca5c907)
### Stress Test (only for create booking)
#### Stress Test 10 minites with 1666 User
![S test 3](https://github.com/user-attachments/assets/80590d5e-7918-4a54-952b-16c6279836b6)
#### Stress Test 10 minites with 1750 User
![S test 4](https://github.com/user-attachments/assets/5265b69a-c994-427d-81d0-e33957a5f640)
![Report for stress test 1750](https://github.com/user-attachments/assets/086f46be-a1c7-496b-b0ab-2d496426277e)
#### Stress Test 10 minites with 1850 User
![S test 5 1850](https://github.com/user-attachments/assets/14446425-bb55-423b-b65f-040de7474805)
#### Stress Test 10 minites with 1770 User (Capacity Value)
![S test 5 1770](https://github.com/user-attachments/assets/a7cd6eb8-80e4-45c2-8175-c9d5884fa634)
![st](https://github.com/user-attachments/assets/662b216e-500e-4584-8ae7-573a32669022)


















