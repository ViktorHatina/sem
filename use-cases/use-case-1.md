# USE CASE: 1 Produce a report on the salary of all employees for the Organization

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to produce a report on the salary of all employees* so that *I can support financial reporting of the organisation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

Database contains all employee salary data.

### Success End Condition

A report is available for HR to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

HR Advisor.

### Trigger

A request for finance information is sent to HR.

## MAIN SUCCESS SCENARIO

1. Finance request salary information.
2. HR advisor extracts current salary information of all employees .
3. HR advisor provides report to finance.

## EXTENSIONS

3. **No Employees**:
    1. HR advisor informs finance no employees exist.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0