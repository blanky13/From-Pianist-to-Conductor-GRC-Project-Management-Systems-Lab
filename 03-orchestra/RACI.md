# OrchestraX RACI

## Purpose

The RACI model makes ownership visible before execution begins.

**R = Responsible** — performs the work  
**A = Accountable** — owns the outcome  
**C = Consulted** — provides expertise or input  
**I = Informed** — needs awareness of the result

## Example: Joiner-Mover-Leaver Access Process

| Activity | Sponsor | GRC / PM | IT | Security | HR | Control Owner | Audit |
|---|---|---|---|---|---|---|---|
| Define business requirement | A | R | C | C | C | C | I |
| Define access procedure | I | R | C | C | C | A | I |
| New joiner notification | I | I | R | I | A/R | C | I |
| Account provisioning | I | I | A/R | C | C | C | I |
| Access review | I | R | C | A | C | A/R | C |
| Leaver notification | I | I | R | I | A/R | C | I |
| Access removal | I | I | A/R | C | C | C | I |
| Evidence collection | I | A/R | R | C | C | R | I |
| Control testing | I | R | C | A | C | C | A/R |

> This table is a learning simulation, not a universal organizational RACI.

## RACI Quality Checks

Before approving a RACI:

- Is there exactly one clear Accountable role for each outcome?
- Is Responsible assigned to the people actually performing the work?
- Are Consulted roles genuinely needed?
- Are there unnecessary Informed roles?
- Does the RACI match the real process?
- Does the control owner have enough authority to be accountable?
- Are dependencies between activities visible?

## Common Failure Pattern

A weak RACI can look complete because every cell is populated.

That does not mean ownership is clear.

A useful RACI should reduce ambiguity, not create administrative noise.

## Conductor Exercise

Take one control and deliberately create a flawed RACI.

Then diagnose:

- Where is accountability missing?
- Where are two teams both assuming the other owns the outcome?
- Where is a specialist being made accountable without authority?
- Which stakeholder has been unnecessarily included?

Then correct the model.
