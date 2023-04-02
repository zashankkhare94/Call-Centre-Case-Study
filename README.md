# Call-Centre-Case-Study
This case study is about the team that handles incoming calls for Royal Bank of Scotland (RBS) that is one of the banks that employs service solutions of CallIn PLC. 

Problem Statement

RBS Board has hired services of Brent Associates to audit its accounts and the auditors have sought pay-out details to CallIn PLC. You are working with Brent Associates as data analyst and have been called in the team to render your services and investigate inconsistencies, if any. All information was tallied but the pay-outs given to CallIn PLC for the month of February 1999 were suspiciously incorrect and hence your major task is to audit this information and assess if payout has been accurately done and state exchequer has not been cheated upon. 

As per historical records, the RBS Team at CallIn PLC constituted of following team in February 1999: 

●	8 agent positions

●	1 shift-supervisor position

●	5 agent positions for internet services (in an adjacent room) 

The team operated for:

●	During weekdays (Sunday to Thursday), the call centre is staffed from 7:00am to midnight. 

●	During weekends (Friday-Saturday), it closes at 14:00 on Friday and reopens at around 20:00 on Saturday. 

●	The automated service (VRU) operates 7 days a week, 24 hours a day.

Below is the summary of compensation structure that was contracted between RBS and CallIn PLC in effect during the month of February 1999:

●	Fixed Charges: 
This is the fixed amount a minimum of which will be billed to RBS by CallIn PLC. This is non-negotiable and non-deductible even under the provisions of applied penalties (Refer later part of this section on clarification of penalties applicable on CallIn PLC).

  o	Operation sustenance fees: EUR 100,000/ month (The fixed fee is to be billed to RBS every month from the date of billing)
  o	Monthly third-party usage charges: This amount is charged in lieu of fixed third party vendors on boarded by CallIn PLC on behalf of RBS including but not limited to Cloud Telephone Services, Internet Connections, Network Maintenance and Server Maintenance Fees, Equipment AMC etc. This flat fee is EUR 20,000/ month
  
●	Variable Charges:

  o	VRU Call charges: These relate to the usage of VRU facility by RBS customers:
    ▪	Calls handled by VRU are not billed to RBS upto a duration of 120,000 seconds 
    ▪	From 120,001st second onwards, VRU calls are charged at EUR 0.5/ second.
  o	Service Time Charges: This is the main avenue where CallIn PLC generates majority of revenue from the bank. This relates to calls that are transferred and handled by agents. 
    ▪	Upto a total of 30,00,000 seconds, the RBS is billed at EUR 0.5/ second
    ▪	From 30,00,001st minute onwards, the bill is raised at EUR 1/ second.
    
Apart from these charges, certain penalties are agreed and contracted which mandates CallIn PLC to be penalized in case of non-satisfactory servicing of agreement upto the standards of RBS bank:

●	Queuing of customers: RBS does not want its customers to wait in queue for unreasonably long periods. 
Hence:
  o	Queue time <= 1 minute per call is not penalized 
  o	Queuing time > 1 and <= 3 minutes is penalized at EUR 0.5/ minute. 
  o	Queuing time > 3 and <= 5 minutes is penalized at EUR 1/ minute. 
  o	Any queuing time of > 5 minutes is penalized at EUR 2/ minute
  
●	Call Disconnection: Call disconnection penalty is levied over and above the queuing penalty
  o	Every customer that hangs up the call/ disconnects the call due to non-availability of agents is charged at EUR 10/ instance. These can be found by the calls where outcome is “AGENT” and server is “NO-SERVER”. 
  o	If the outcome is “HANG” and server is “NO-SERVER”, the penalty is applied at EUR 5/ instance. These charges are over and above the queue time.
  
Please find below the summary of payments done to CallIn PLC by RBS for the services rendered in the month of February 1999:
Verify if the payments are correctly calculated and during the course of case study
