# SOC 2 Findings

## Objective

Document exceptions identified during SOC 2 control testing, including the condition, root cause, risk impact, and required remediation.

## Finding

### Finding ID: MFA-001

**Control:** C-001 — MFA for Privileged Accounts

**Condition:**

One temporary emergency privileged account did not have MFA enabled.

**Evidence:**

Testing of 20 privileged accounts identified one account without MFA.

**Root Cause:**

The account provisioning process did not automatically enforce MFA for temporary privileged accounts.

**Risk / Impact:**

The account could potentially be accessed using only a password, increasing the risk of unauthorized privileged access.

**Severity:**

High

**Status:**

Open pending remediation and verification.

## Required Remediation

1. Enable MFA on the affected privileged account.
2. Update the privileged account provisioning process to automatically enforce MFA for all privileged accounts, including temporary emergency accounts.
3. Verify remediation through updated configuration and retesting.

## Disclaimer

This is a fictional SOC 2 simulation created for learning and portfolio purposes. It does not represent a real SOC 2 examination or professional audit engagement.
