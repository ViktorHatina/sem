# USE CASE: 3 Produce a report on the salary of employees in given department for the Department Manager

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *department manager* I want *to produce a report on the salary of employees in my department* so that *I can support financial reporting for my department.*

### Scope

Department

### Level

Primary task.

### Preconditions

We know the role.  Database contains current employee salary data.

### Success End Condition

A report is available for department manager to provide for his/her department.

### Failed End Condition

No report is produced.

### Primary Actor

Department Manager.

### Trigger

A request for finance information is sent to dep. manager.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for a given department.
2. Department Manager captures department (matches it with his/hers dep.) to get salary information for employees in his/her department.
3. Department Manager extracts current salary information of all employees of his/hers department.
4. Department Manager has report for his/hers department.

## EXTENSIONS

3. **Department does not exist**:
    1. Department Manager informs finance no department exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0