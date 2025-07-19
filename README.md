# API-Load-Test-JMeter


<h2>Project Summary:</h2> 
I conducted Load Testing and Stress Testing on the Booking APIs to evaluate their performance and identify system limits. Additionally, I implemented API Chaining (JMeter Collection) for the DMoney website’s Transaction APIs. For the Transaction APIs, data was retrieved from CSV files, and multiple API requests were executed concurrently using four threads in JMeter.

<h2>Test Case Scenarios for Load and Stress Testing:</h2>
Created a collection of APIs (JMeter Collection) consisting of Login API, Create Booking API, and Search API HTTP requests.
Executed Load Testing and Stress Testing to measure system performance and determine the bottleneck and capacity thresholds.<br>
<br>
Website for APIs - https://restful-booker.herokuapp.com

<h2>Testcase scenarios for API Chaining in Jmeter Test: </h2>
1. 5 agents perform deposits for 10 customers.<br>
2. 5 customers send money to another 10 customers.<br>
3. 5 customers make payments to 2 merchants.<br>
4. Set the ramp-up time to 120 seconds in all the above thread configuration.<br>
<br>
Website for APIs - http://dmoney.roadtocareer.net

<h2>How to Run?</h2>

<h3> Execute the following steps using JMeter: </h3> 
   
  - ``` git clone https://github.com/Yasir-Hossain-Katib/API-Load-Test.git ```<br>
  - ``` Open ApacheJMeter ``` <br>
  - ``` From apacheJMeter open the JMX File ```<br> 
  - ``` Finally Run ```

<h3>Execute the following steps using CLI: </h3>

  - ``` git clone https://github.com/Yasir-Hossain-Katib/yuyh.git ```
  - ``` jmeter -n -t '.\booking.jmx' -l '.\booking.jtl' -e -o Reports ``` 
  - ``` jmeter -n -t '.\Dmoney.jmx' -l '.\Dmoney.jtl' -e -o Reports ``` 

<h2>Load and Stress Test Excel Report:</h2>

 - **[Load and Stress Test Report](https://docs.google.com/spreadsheets/d/1iGBD9d_MBbxWRMku1ZJT4yFe1w7vU-ic3HExp-wUkZI/edit?gid=0#gid=0)**

<h3>Generated HTML report for Load Test</h3>

![Screenshot 2024-12-04 172009](https://github.com/user-attachments/assets/0cac971e-97c6-47af-9937-87c2000e265c)


<h3>Generated HTML report for Stress Test</h3>

![image](https://github.com/user-attachments/assets/f696a30e-d26a-4dba-997c-0327054d4daa)


<h3>Generated HTML report for DMoney Jmeter Collection Test</h3>

![Screenshot 2024-12-04 185200](https://github.com/user-attachments/assets/32cbe9f9-8333-486b-af4b-8ebacf9e831c)

