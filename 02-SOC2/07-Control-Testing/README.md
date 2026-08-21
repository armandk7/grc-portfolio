# SOC 2 Control Testing

## Objective

Document the testing performed over selected SOC 2 controls and record testing results, exceptions, and conclusions.

## Testing Approach

Control testing evaluates whether controls are implemented and operating as intended based on the available evidence.

The testing process includes:

1. Identify the control
2. Define the population
3. Select or review the relevant population/sample
4. Inspect supporting evidence
5. Record testing results
6. Document exceptions
7. Evaluate the impact of exceptions

## Control Tested

### C-001 — MFA for Privileged Accounts

**Control Objective:**

Ensure privileged access is protected from unauthorized use by requiring MFA for privileged accounts.

**Evidence Reviewed:**
- MFA configuration
- Privileged account listing

**Population:**
20 privileged accounts

**Tested:**
20 privileged accounts

**Results:**
- Pass: 19
- Exception: 1

**Exception:**

One temporary emergency privileged account did not have MFA enabled.

**Root Cause:**

The account provisioning process did not automatically enforce MFA for temporary privileged accounts.

**Initial Conclusion:**

The exception requires remediation and verification before the finding can be considered closed.

## Disclaimer

This is a fictional SOC 2 simulation created for learning and portfolio purposes. It does not represent a real SOC 2 examination or professional audit engagement.
