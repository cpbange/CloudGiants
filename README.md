# CloudGiants

## AccountTrigger.apxt
```
After insert trigger.
Passes trigger.new to AccountTrigger_Hander (processOpp() method)
This allows organized trigger handling by creating seperate methods for each 
task.
```

## oppTrig.apxt
```
Before and After insert
Before Insert - Associates the Opportunity with the StandardPriceBook.
After Insert - Adds line item to opportunity per case study requirement.
```

## AccountTrigger_Hander.apxc
```
processOpp(List<Account> accList) - This method creates an Initial Opp for each created account. 
system debug messages still in method. Error handling
```

## TestDataFactory.apxc
```
Creates Test Accounts and Opportunies.
Cant test on data in production. 
@isTest Annotation
List<Account> createAccountWithOpps(Integer numAccounts, Integer numOppsPerAccount
```

## TestAccountDeletion.apxc
```
@isTest static void TestDeleteAccountWithOneOpportunity()
Tests deletion
```

## A flow has been created for this but is not active.
```
flowId = 301Dn000000Tfo5IAC
```

