## Active project ongoing: Labour Cost of Trading Economics
*Scenario: You haven't got a license in Trading Economics, but you want to automate the extraction of historical data*

![image](https://github.com/user-attachments/assets/f266f7bf-4dca-45ae-a642-302f323dcea8)

*What I have attempted, is this...*

(1) Select the option for showing 10 years range and in line chart format

![image](https://github.com/user-attachments/assets/90940ca3-0325-4c0b-9cf4-85d434774c28)

(2) This gives an SVG path when located the element

![image](https://github.com/user-attachments/assets/15b56248-53e8-4e56-ba6a-93a8a38d60d5)

(3) With the help of Last and Previous data points...

![image](https://github.com/user-attachments/assets/477484ab-1adf-4bc1-b132-64de318613f7)

(4) Calculate the offset and coefficient (slope) and reverse engineer the original data points

![image](https://github.com/user-attachments/assets/38bf3472-7aac-4cc1-9d47-0854e6f18a3b)

(5) Save as a dataframe for further procedures

![image](https://github.com/user-attachments/assets/157db0dc-d475-4b31-b422-677f6d22ad91)

However...

At this stage, I am stuck with the selenium part🥲, it somehow couldn't extract the path element with XPATH 
"//*[@id="highcharts-inhwuj5-0"]/svg/g[7]/g[1]/path[1]"

Research ongoing...


## Disclaimer: ##
I write this code just for practice / learning purpose, not for commercial use.
