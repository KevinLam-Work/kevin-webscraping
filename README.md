## Active project ongoing: Labour Cost of Trading Economics
*Scenario: You haven't got a license in Trading Economics, but you want to automate the extraction of historical data*

![image](https://github.com/user-attachments/assets/f266f7bf-4dca-45ae-a642-302f323dcea8)

*What I have attempted, is this...*

(1) Select the option for showing 10 years range and in line chart format

![image](https://github.com/user-attachments/assets/90940ca3-0325-4c0b-9cf4-85d434774c28)

(2) This gives an SVG path when located the element

![image](https://github.com/user-attachments/assets/15b56248-53e8-4e56-ba6a-93a8a38d60d5)

(3) Extract the SVG path with CCS_SELECTOR

![image](https://github.com/user-attachments/assets/2ece46c6-e440-454e-ac98-644aaf36e0bf)

(4) Then, with the help of Chart Height, Last and Previous data points...

![image](https://github.com/user-attachments/assets/6c2889eb-4504-4c4a-9a84-41bca39bf4d4)

![image](https://github.com/user-attachments/assets/477484ab-1adf-4bc1-b132-64de318613f7)

(5) Calculate the offset and coefficient (slope) and reverse engineer the original data points

![image](https://github.com/user-attachments/assets/c50e77b9-0891-4a56-9108-2cfb6a8c8b1d)

(6) Save as a dataframe for further procedures

![image](https://github.com/user-attachments/assets/ffb0dfe6-f473-442b-a02c-694b2a34ed4d)


## What's next? ##
1. Format and export to excel, csv, etc.
2. Make it reusable for other sources, not just for Australia

## Disclaimer: ##
I write this code just for practice / learning purpose, not intended for commercial use.
