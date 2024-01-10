Splitwise is an algorithm that helps us settling bills among friends and family. It manages the cash flow.

Let us look how we implement splitwise algorithm and track expenses shared :-

1. Firstly we take the number of person included in the share(expenses).

2. After that we calculate net amount for every individual.

3.now we have to look that who has credited maximum and debited maximum and find the minimum of the max credited and debited amount now debit that amount to the max debitor and credit that amount to the max creditor.

4. if the minimum of max credited and debited is equal to max credited amount then remove maximum creditor from set of person and recur for the remaining (n-1) persons.

5.if the minimum of max credited and debited is equal to max debited amount then remove maximum creditor from set of person and recur for the remaining (n-1) persons.