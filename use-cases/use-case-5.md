# USE CASE: 5 Add new employee's details to the system

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to add a new employee's details* so that *I can ensure the new employee is paid.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the new employee details.  Database allows new employee entries.

### Success End Condition

A new employee's details are added to the database.

### Failed End Condition

Employee's details are not added to the database and employee may not get payed on time.

### Primary Actor

HR Advisor.

### Trigger

Act of adding new employee's information into the system.

## MAIN SUCCESS SCENARIO

1. HR advisor receives information from new employee
2. HR advisor accesses the database with current employees
3. HR advisor adds new employee providing detailed information


## EXTENSIONS

3. **Information is incorrect**:
    1. HR advisor informs finance no that information is incorrect and must be updated.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0