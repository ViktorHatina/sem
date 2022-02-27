# USE CASE: 9 Delete an employee's details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to delete an employee's details* so that *the company is compliant with data retention legislation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the ID of employee information that is to be deleted/removed.  Database contains employee data.

### Success End Condition

Employee's details deleted.

### Failed End Condition

Employee's details not fully deleted/removed.

### Primary Actor

HR Advisor.

### Trigger

A request for HR to remove given employee' information/details.

## MAIN SUCCESS SCENARIO

1. Company/HR/Leadership request the removal of a certain employee from the system.
2. HR advisor captures name of the employee to get their details.
3. HR advisor removes the details 

## EXTENSIONS

3. **Detail Remainder**:
    1. HR must check for any remainders of data tied to employee's infromation in the system

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0