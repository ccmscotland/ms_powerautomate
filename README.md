# Microsoft Power Automate Solutions

A repository of production-ready Power Automate workflows, cloud flows, architecture specifications, and SharePoint integration blueprints.

---

## Solutions Catalog

### 1. [Process Approval System](./Process-Approval)
A multi-stage approval workflow integrated with SharePoint Online and Microsoft Lists Forms.

* **Key Features**:
  * **Dynamic Phase Milestone Tracking**: Automatically assigns Phase 1–4 based on SharePoint creation timestamps.
  * **Intelligent Branching**: Dynamic routing for Teams, SharePoint, and Transfer requests.
  * **Duplicate Prevention**: Queries SharePoint via OData to identify and isolate duplicate submissions.
  * **Automated Data Validation**: Pre-checks mandatory metadata and flags incomplete requests.
  * **Human-in-the-Loop Approvals**: Interactive Adaptive Cards delivered via Microsoft Teams and Outlook.
  * **Multi-Channel Notifications**: Automated branded HTML status emails for submission receipts, approvals, and rejections.

* **Solution Assets**:
  * [Full Architecture Specification & Blueprint](./Process-Approval/README.md)
  * [Exported Flow Definition (JSON)](./Process-Approval/flow-definition.json)
  * [SharePoint List Schema Dump](./Process-Approval/sharepoint-list-fields.json)
  * [Sample Test Payload](./Process-Approval/sample-test-payload.json)

---

## Repository Structure

```
ms_powerautomate/
├── README.md                              # Solutions catalog and repository overview
└── Process-Approval/                      # Process Approval flow solution package
    ├── README.md                          # Full architectural specification & re-use guide
    ├── flow-definition.json               # Power Automate Logic Apps flow definition
    ├── sharepoint-list-fields.json        # Complete SharePoint list schema export
    └── sample-test-payload.json           # Sample JSON test payload
```
