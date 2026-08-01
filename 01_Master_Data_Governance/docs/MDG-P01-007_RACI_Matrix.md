# RACI Matrix

## 1. Purpose

The purpose of this document is to define the roles and responsibilities for the Master Data Governance process. A RACI Matrix ensures that each activity has clear ownership, supports accountability, and improves collaboration across business functions.

---

## 2. RACI Definitions

| Letter | Meaning | Description |
|--------|---------|-------------|
| **R** | Responsible | Performs the work required to complete the activity. |
| **A** | Accountable | Owns the activity and approves the final outcome. Only one accountable role should exist for each activity. |
| **C** | Consulted | Provides input, expertise, or advice before a decision is made. |
| **I** | Informed | Receives updates on progress or completion of the activity. |

---

## 3. Roles

| Role | Description |
|------|-------------|
| Business User | Initiates master data requests. |
| Engineering | Provides product and engineering master data. |
| Procurement | Provides supplier and purchasing information. |
| Production Planning | Validates planning-related master data. |
| Quality | Ensures compliance with quality standards. |
| Data Management Team | Reviews, approves, and governs master data. |
| IT / SAP Team | Maintains SAP S/4HANA configuration, workflows, and system support. |

---

## 4. RACI Matrix

| Activity | Business User | Engineering | Procurement | Production Planning | Quality | Data Management | IT / SAP |
|----------|---------------|-------------|-------------|---------------------|---------|-----------------|-----------|
| Submit Master Data Request | **R** | I | I | I | I | I | I |
| Provide Technical Information | C | **R** | I | I | I | I | I |
| Validate Supplier Information | I | I | **R** | I | I | C | I |
| Validate Planning Information | I | I | I | **R** | I | C | I |
| Review Data Completeness | I | C | C | C | C | **R/A** | I |
| Verify Data Quality Standards | I | C | C | C | **R** | **A** | I |
| Approve Master Data | I | I | I | I | C | **R/A** | I |
| Configure Validation Rules | I | I | I | I | I | C | **R/A** |
| Maintain SAP Workflow | I | I | I | I | I | C | **R/A** |
| Monitor Data Quality KPIs | I | C | C | C | C | **R/A** | I |

---

## 5. Benefits

The RACI Matrix provides:

- Clear ownership of every activity.
- Reduced duplication of responsibilities.
- Improved communication between departments.
- Better governance and accountability.
- Faster decision-making during the master data lifecycle.

---

## 6. Conclusion

The RACI Matrix establishes clear responsibilities for every stage of the master data governance process. By defining ownership and accountability, the organization can improve collaboration, strengthen governance, and support consistent master data quality across all business functions.