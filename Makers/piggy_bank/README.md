# Piggy Bank
# The parts of this program are:
1) class PiggyBank
- this will be the class that comprises several methods - initialize, balance, shake, and break (possibly desposit as well)
2) method initialize 
- this will initialize the instance variable *task* which will be taken as the argument in our various methods.
- Above this initialize method will be attr_reader - which seems to be a necessary step (not sure why - will research more)
3) method *Balance*
- this will contain a method called *balance* which store an integer (representing the number of coins in the Piggybank)
4) method *Shake*
-  shake will return "cling" if the *balance* > 0 
5) method *Break*
- break will return a string "Here's your savings #{balance}"
- break will also reset balance to 0
6) method *Deposit*
- deposit will ask for user_input - namely, 'how many coins would you like to deposit?' 
