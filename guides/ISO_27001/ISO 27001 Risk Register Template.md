# ISO 27001 Risk Register Template

## Purpose:

This Risk Register records identified information security risks, their assessments, and corresponding treatment plans as required by ISO 27001’s risk management framework.

| Risk ID | Asset/Process | Description of Risk | Threat Source | Vulnerability | Impact (High/Med/Low) | Likelihood (High/Med/Low) | Inherent Risk Level (Comb. of Impact & Likelihood) | Current Controls in Place | Residual Risk Level | Risk Treatment Option (Reduce/Accept/Transfer/Avoid) | Treatment Plan/Action Steps | Responsible Person | Due Date | Status |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| 001 | Customer DB | Unauthorized access to customer data | External attacker | Weak password policy | <li>- [X] High</li> <li>- [ ] Med </li> <li>- [ ] Low</li> | <li>- [ ] High</li> <li>- [x] Med </li> <li>- [ ] Low</li> | <li>- [ ] High</li> <li>- [x] Med </li> <li>- [ ] Low</li> | MFA partially implemented | <li>- [x] High</li> <li>- [ ] Med </li> <li>- [ ] Low</li> | <li>- [x] Reduce</li> <li>- [ ] Accept </li> <li>- [ ] Transfer</li> <li>- [ ] Avoid</li> | Implement stricter password rules & full MFA coverage | IT Security Lead | 30 Days | In Progress |
| 002 | Server Room | Physical theft of a server | Insider threat | Inadequate physical locks | <li>- [X] High</li> <li>- [ ] Med </li> <li>- [ ] Low</li>  | <li>- [ ] High</li> <li>- [ ] Med </li> <li>- [x] Low</li>  | <li>- [ ] High</li> <li>- [x] Med </li> <li>- [ ] Low</li>  | Locked door, CCTV cameras | <li>- [ ] High</li> <li>- [ ] Med </li> <li>- [x] Low</li>  | <li>- [x] Reduce</li> <li>- [ ] Accept </li> <li>- [ ] Transfer</li> <li>- [ ] Avoid</li>  | N/A (Risk accepted by management due to cost/benefit) | Facilities Manager | N/A | Reviewed Annually |
| 003 | Payment System | Interception of payment data during transmission | External attacker | Unencrypted transmission | <li>- [X] High</li> <li>- [ ] Med </li> <li>- [ ] Low</li>  | <li>- [X] High</li> <li>- [ ] Med </li> <li>- [ ] Low</li>  | <li>- [X] High</li> <li>- [ ] Med </li> <li>- [ ] Low</li> | None currently | <li>- [X] High</li> <li>- [ ] Med </li> <li>- [ ] Low</li> | <li>- [ ] Reduce</li> <li>- [ ] Accept </li> <li>- [ ] Transfer</li> <li>- [x] Avoid</li>  | Implement TLS encryption, update network firewall rules | Network Engineer | 45 Days | Not Started |

## Instructions for Use:

* **Asset/Process:** Specify which asset (data, system) or process is at risk.  
* **Description of Risk:** Briefly define what could go wrong (e.g., unauthorized access, data loss).  
* **Threat Source & Vulnerability:** Identify who or what could exploit a weakness (e.g., external attacker, employee error) and what vulnerability enables it.  
* **Impact & Likelihood:** Rate the severity of potential damage and the probability of occurrence.  
* **Inherent Risk Level:** Determine the initial risk level without controls.  
* **Current Controls:** Note existing measures that reduce risk.  
* **Residual Risk:** Evaluate risk after applying current controls.  
* **Treatment Option & Plan:** Choose whether to reduce, accept, transfer, or avoid the risk and outline actions for mitigation or acceptance.  
* **Responsible Person & Due Date:** Assign accountability and a treatment implementation deadline.  
* **Status:** Track progress (e.g., Not Started, In Progress, Complete).

## Note:

This template should be reviewed and adapted to fit your organization’s unique environment and risk profile. It serves as a starting framework to simplify compliance with ISO 27001 requirements.
