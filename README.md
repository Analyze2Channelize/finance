# margincall-early-warning-system
Background

The borrower from <LENDER> pldeges his collateral accounts with <LENDER>. Each collateral account can have one or more stocks and other instruments as well. For the purpose of this project, all non-equity products are out of scope. From <LENDER> perspective, the collateral account can be treated as portfolio where all the instruments are pledged. Based on the daily EOD snapshot of client's collateral account received from Custodian, <LENDER> system runs a Margin process and generates margin calls if required. The Margin process takes into account many factors, but one of the most important factors is Current price of the instrument.
The other factor is quantity of each instrument.
  
Goal

Based on the client-pledged holdings data at EOD T, our AIM in this POC is to predict what is the probability of a client's porfolio to go in to a margin call at EOD T+7.
