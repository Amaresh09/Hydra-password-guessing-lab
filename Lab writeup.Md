# SSH & SMB Authentication Behavior + Traffic Observations (Authorized Lab)

## Objective
Study how SSH (TCP/22) and SMB (TCP/445) behave during authentication activity and observe high-level traffic patterns in an isolated lab.

## Environment (Authorized)
- Kali Linux VM + Windows VM (isolated lab network)
- Tools: service verification + packet capture tool (high-level)

## Protocol Notes
### SSH (TCP/22)
- What SSH is used for
- What you observed about connections/auth behavior (high-level)

### SMB (TCP/445)
- What SMB is used for
- Why SMB is stateful and may not tolerate heavy parallel authentication attempts
- Mention the “single thread” observation without describing attack steps

## Traffic Observation (High-Level)
- What you saw in packet capture (no IPs/credentials)
- How defenders can detect abnormal auth bursts

## Defensive Takeaways
- Password policy + account lockout/rate limiting
- Monitoring auth logs
- Restrict SMB exposure, segmentation, firewalling

## Disclaimer
Educational lab in an authorized environment. No real systems targeted. No credentials or attack steps included.
