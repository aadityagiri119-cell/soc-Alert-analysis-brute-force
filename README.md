# soc-Alert-analysis-brute-force
# SOC Alert Analysis

##  Alert Name
Multiple Failed Login Attempts

## Log Data
Source IP: 192.168.1.10
Target: Admin Account
Attempts: 25

##  Investigation Steps
1. Checked login logs
2. Identified repeated failures
3. Checked IP reputation

##  Findings
- Possible brute force attack
- Unauthorized access attempt

##  Verdict
True Positive

##  Escalation
Escalated to L2

##  Recommendation
- Block IP
- Enable account lockout
- Reset password
