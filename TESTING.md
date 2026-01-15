# Testing Documentation

## Test Strategy

As a QA engineer, I approached this project with systematic validation of each security control.

## Identity & Access Tests

### Test Suite 1: RBAC Validation

| Test Case | User | Resource | Expected | Actual | Status |
|-----------|------|----------|----------|--------|--------|
| TC-001 | DevUser | rg-dev-001 | Access granted | ✅ Granted | PASS |
| TC-002 | DevUser | rg-prod-001 | Access denied | ✅ Denied | PASS |
| TC-003 | OpsUser | rg-prod-001 | Access granted | ✅ Granted | PASS |
| TC-004 | Auditor | Any RG | Read only | ✅ Read-only | PASS |

[Continue with more test cases...]

## Policy Tests

[Document your policy testing...]

## Key Vault Access Tests

[Document access testing...]

