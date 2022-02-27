# USE CASE: 6 View employee's details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to view employee's details* so that *the employee's promotion request can be supported.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the indiviudal employee identificators.  Database contains current employee details including salary data.

### Success End Condition

HR advisor is able to view employee's details and promotion request.

### Failed End Condition

HR advisor is not able to access employee details, or information related to promotion requests.

### Primary Actor

HR Advisor.

### Trigger

HR advisor conscidering/deciding on promotions.

## MAIN SUCCESS SCENARIO

1. HR advisor searches for employee's details.
2. HR advisor captures employee's name (identificator) to get further details.
3. HR advisor views employee information and has access to promotion requests.


## EXTENSIONS

3. **Incorrect Identification**:
    1. HR advisor must fix employee's identification to access their details.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0