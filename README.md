# TronHack2022
Level: off-chain voting system on TRON

Technical Stuff
1. Token Counter: hi.html
   - Implements a TRON smart contract 
   - Implements ADIs
   - Takes in users' unique TRONlink address in myaddress
   - Returns the number of tokens in Tronlink wallet 
   
2. Token Counter is used to calculate a users voting power
   - 1:1 ratio of number of tokens (n) to voting power
   - 100,000 total shares (s)
   - n/s = voting power
   
3. Execution (Incomplete)
   - Webflow Site: Level contains all UI design
   - Site connects to Tronlink wallet through TRON Integration 
   - Able to see how much token a user owns 
   - User joins DAO by clicking a button 'Join' underneath DAO token
   - User is taken to Google Form where they enter wallet address to extract token amount and voting right
   - User votes on protocol through the Form
   - Google Sheet database tracks all votes and tallies them in real time 
   - Form stops accepting responses when 'execution time' is reached
   - A consensus of the public is formed all on one platform:)
