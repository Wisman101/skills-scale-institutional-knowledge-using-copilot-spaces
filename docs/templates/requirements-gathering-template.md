# Requirements Gathering Template

This template guides the Business Analyst through the requirements gathering process to ensure comprehensive and clear requirements documentation.

## How to Use
1. Use this template during the requirements gathering phase
2. Conduct stakeholder interviews and workshops to gather information
3. Document requirements clearly and maintain traceability
4. Review with Product Manager and development team to validate feasibility

---

## Project Information
- **Project Name:** [Enter project name]
- **Business Analyst:** [Name]
- **Date Created:** [Date]
- **Last Updated:** [Date]
- **Version:** [e.g., 1.0]

---

## 1. Business Context

### Business Problem / Opportunity
[Describe the business problem or opportunity this project addresses]

### Business Objectives
- [Objective 1]
- [Objective 2]
- [Objective 3]

### Success Criteria
[How will success be measured? What are the key performance indicators?]

### Scope
**In Scope:**
- [Item 1]
- [Item 2]

**Out of Scope:**
- [Item 1]
- [Item 2]

---

## 2. Stakeholder Analysis

| Stakeholder Name/Group | Role | Interest Level | Influence Level | Requirements Priority | Contact Info |
|------------------------|------|----------------|-----------------|----------------------|--------------|
| [Name/Group] | [Role] | High/Med/Low | High/Med/Low | High/Med/Low | [Email/Phone] |
| | | | | | |

---

## 3. Functional Requirements

### Requirement Template
For each requirement, provide:
- **ID:** [Unique identifier, e.g., FR-001]
- **Title:** [Short descriptive title]
- **Description:** [Detailed description of what the system should do]
- **Business Justification:** [Why this requirement is needed]
- **Priority:** [Must Have / Should Have / Could Have / Won't Have (MoSCoW)]
- **Acceptance Criteria:** [Specific, testable criteria]
- **Dependencies:** [Related requirements or external dependencies]
- **Source:** [Who requested this requirement]

---

### Example Requirements

#### FR-001: User Authentication
- **Title:** User Login with Multi-Factor Authentication
- **Description:** System shall allow users to log in using email and password, followed by a multi-factor authentication code sent via SMS or email
- **Business Justification:** Required for security compliance and to protect customer data
- **Priority:** Must Have
- **Acceptance Criteria:**
  - Users can enter email and password on login page
  - System validates credentials against user database
  - Upon successful validation, system sends MFA code to user's registered contact method
  - Users can enter MFA code to complete authentication
  - System provides appropriate error messages for invalid credentials or MFA codes
  - Session timeout occurs after 30 minutes of inactivity
- **Dependencies:** None
- **Source:** Security team, compliance requirements

---

### [Add your requirements here]

#### FR-002: [Requirement Title]
- **Title:** 
- **Description:** 
- **Business Justification:** 
- **Priority:** 
- **Acceptance Criteria:**
  - 
  - 
  - 
- **Dependencies:** 
- **Source:** 

---

## 4. Non-Functional Requirements

### Performance Requirements
| ID | Requirement | Target Metric | Priority |
|----|-------------|---------------|----------|
| NFR-001 | Page load time | < 2 seconds | High |
| NFR-002 | API response time | < 500ms for 95th percentile | High |

### Security Requirements
| ID | Requirement | Description | Priority |
|----|-------------|-------------|----------|
| NFR-010 | Data encryption | All sensitive data encrypted at rest and in transit | Must Have |
| NFR-011 | Access control | Role-based access control for all system functions | Must Have |

### Usability Requirements
| ID | Requirement | Description | Priority |
|----|-------------|-------------|----------|
| NFR-020 | Accessibility | WCAG 2.1 Level AA compliance | Should Have |
| NFR-021 | Mobile responsiveness | Support mobile devices with screen sizes 320px and above | Must Have |

### Scalability Requirements
| ID | Requirement | Description | Priority |
|----|-------------|-------------|----------|
| NFR-030 | Concurrent users | Support 10,000 concurrent users | High |
| NFR-031 | Data volume | Handle up to 1 million records without performance degradation | Medium |

### Reliability Requirements
| ID | Requirement | Description | Priority |
|----|-------------|-------------|----------|
| NFR-040 | System uptime | 99.9% uptime during business hours | High |
| NFR-041 | Data backup | Daily automated backups with 30-day retention | Must Have |

---

## 5. User Stories (if using Agile methodology)

### User Story Template
**As a** [type of user]  
**I want** [an action or feature]  
**So that** [benefit or value]

**Acceptance Criteria:**
- [Criterion 1]
- [Criterion 2]
- [Criterion 3]

**Story Points:** [Estimate]  
**Priority:** [High/Medium/Low]

---

### Example User Stories

#### Story 1: User Profile Management
**As a** registered user  
**I want** to update my profile information  
**So that** my account details remain current and accurate

**Acceptance Criteria:**
- Users can access profile settings from the main navigation
- Users can edit name, email, phone number, and preferences
- System validates email format and phone number format
- Users receive confirmation message upon successful update
- Changes are reflected immediately in the user's session

**Story Points:** 5  
**Priority:** High

---

## 6. Business Rules

Document specific business logic and rules:

| ID | Business Rule | Description | Impact |
|----|---------------|-------------|--------|
| BR-001 | [Rule name] | [Description of the rule] | [Systems/processes affected] |
| BR-002 | | | |

---

## 7. Data Requirements

### Data Entities
| Entity Name | Description | Key Attributes | Relationships |
|-------------|-------------|----------------|---------------|
| User | System user account | UserID, Email, Name, Role | Has many: Orders, Preferences |
| | | | |

### Data Migration Requirements
[Describe any data migration needs from existing systems]

### Data Retention Policy
[Specify how long different types of data should be retained]

---

## 8. Integration Requirements

| System Name | Integration Type | Data Exchange | Frequency | Owner |
|-------------|-----------------|---------------|-----------|-------|
| [System] | API/Batch/Real-time | [Data description] | [Frequency] | [Team/Contact] |
| | | | | |

---

## 9. Assumptions and Constraints

### Assumptions
- [Assumption 1]
- [Assumption 2]

### Constraints
- **Technical:** [e.g., Must use existing authentication system]
- **Budget:** [Budget limitations]
- **Timeline:** [Schedule constraints]
- **Resource:** [Resource limitations]
- **Regulatory:** [Compliance requirements]

---

## 10. Open Questions and Issues

| ID | Question/Issue | Assigned To | Status | Resolution Date |
|----|---------------|-------------|--------|-----------------|
| Q-001 | [Question or issue] | [Name] | Open/Resolved | [Date] |
| | | | | |

---

## 11. Requirements Traceability Matrix

| Requirement ID | Source | Design Document | Test Case ID | Status |
|----------------|--------|-----------------|--------------|--------|
| FR-001 | Security Team | DD-001 | TC-001, TC-002 | Approved |
| | | | | |

---

## 12. Review and Approval

### Review History
| Version | Date | Reviewed By | Comments | Status |
|---------|------|-------------|----------|--------|
| 1.0 | [Date] | [Name] | [Comments] | Draft/Approved |
| | | | | |

### Approval Sign-off
- **Business Analyst:** _________________ Date: _______
- **Product Manager:** _________________ Date: _______
- **Project Manager:** _________________ Date: _______
- **Technical Lead:** _________________ Date: _______
- **Key Stakeholder:** _________________ Date: _______

---

## 13. Appendices

### Glossary
| Term | Definition |
|------|------------|
| [Term] | [Definition] |

### References
- [Related document 1]
- [Related document 2]

### Supporting Documents
- [Link to wireframes]
- [Link to process flows]
- [Link to data models]

---

## Notes for Business Analysts
- Schedule regular reviews with stakeholders to validate requirements
- Keep requirements at an appropriate level of detail (not too high-level, not too specific)
- Ensure all requirements are testable and measurable
- Maintain traceability from business objectives to individual requirements
- Update this document as requirements evolve through the project lifecycle
- Use workshops and collaborative sessions to resolve ambiguities
- Document all decisions and rationale for future reference
