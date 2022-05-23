## Apex_Triggers
### Get Started with Apex Triggers
#### Learning Objectives:
#### After completing this unit, you'll be able to:
#### Write a trigger for a Salesforce object.
#### Use trigger context variables.
#### Call a class method from a trigger.
#### Use the sObject addError() method in a trigger to restrict save operations.

### Writing Apex Triggers
#### Apex triggers enable you to perform custom actions before or after events to records in Salesforce, such as insertions, updates, or deletions. Just like database #### systems support triggers, Apex provides trigger support for managing records.
#### Typically, you use triggers to perform operations based on specific conditions, to modify related records or restrict certain operations from happening. You can use #### triggers to do anything you can do in Apex, including executing SOQL and DML or calling custom Apex methods.

### Trigger Syntax:
```
trigger TriggerName on ObjectName (trigger_events) {
   code_block
}
Example:


```
### The events you can specify are:
* ####  before insert
* ####  before update
* ####  before delete
* ####  after insert
* ####  after update
* ####  after delete
* #### after undelete

***

** Bulk Apex Triggers
#### Learning Objectives
After completing this unit, you'll be able to:
* #### Write triggers that operate on collections of sObjects.
* #### Write triggers that perform efficient SOQL and DML operations.
* #### Bulk Trigger Design Patterns
***
