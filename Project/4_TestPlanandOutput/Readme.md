## Test Plan
# High Level Test Plan
|  Test ID  |  Description  |  Expected Input  |  Expected Output  |  Status  |
| ------  | ------  | ------ | ------ | ------ |
|  H01  |  Writing Code  |  Compiling the Code  |  No Errors  |  Implemented  |   
|  H02  |  Generating Hex FIle  |  Hex File  |  Hex File  |  Implemented  |
|  H03  |  Making the Circuit  |  Components  |  Circuit  |  Implemented  |
|  H04  |  Buzzer  |  Component  |  Buzzer sound  |  Implemented  |
|  H05  |  Input Password  |  #/*1234#  |  Correct Pass  |  Implemented  |
|  H06  |  Input Password  |  * 1234*#  |  Wrong Pass  |  Implemented  |
|  H07  |  Input Password  |  No Input  |  Count down display  |  Implemented  |

# Low Level Test Plan
|  Test ID  |  Description  |  Expected Input  |  Expected Output  |  Status  |
| ------  | ------  | ------ | ------ | ------ |
|  L01  |  Library files  |  Added Library files  |  Execution without Errors  |  Implemented  |   
|  L02  |  Countdown display  |  Run  |  Display  |  Implemented  |
|  L03  |  Circuit   |  Implementing Circuit    |  Run Circuit  |  Implemented  |

## If no password is entered: Output- Buzzer triggered
![image](https://user-images.githubusercontent.com/98816218/156928634-2e04679a-e9d0-482d-beaa-d4b733d71f39.png)
## If password is *1234# -Correct Pass
![image](https://user-images.githubusercontent.com/98816218/157174010-ddad5676-2e89-48a6-867f-d9fec2069aa4.png)
## If password is *1234*# -Wrong Pass and Buzzer is triggered
![image](https://user-images.githubusercontent.com/98816218/157174310-ea1e62b0-540d-42e3-abd5-7a8ca31e2552.png)
