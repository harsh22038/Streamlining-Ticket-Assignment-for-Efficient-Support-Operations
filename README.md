This project is a ServiceNow customization developed to streamline ticket assignment and improve support operations efficiency. It introduces a dedicated table and related configurations that help organizations manage support requests in a structured, automated, and secure way.

Key Highlights

Custom Table (u_operations_related)
A centralized table to store and manage support-related issues.

Automated Service Request Number
Each ticket receives a unique, auto-generated request number (u_service_request_no) using a script (getNextObjNumberPadded()), reducing manual errors and ensuring traceability.

Issue Classification
A predefined choice list (u_issue) simplifies categorization, including options like:

404 error

Unable to login to platform

Expired user account

Certificate-related issues

Assignment & Tracking

Assigned to Group: Ensures responsibility is clear by routing tickets to the right support team.

Comments field: Allows agents to add notes, troubleshooting details, or additional context for faster resolution.

Roles & Access Controls

platform_role: Can handle platform-related issues.

u_operations_related_user: Provides access to the Operations module with limited permissions.

Admin: Full control with overrides for all operations.

ACLs (Access Control Lists): Secure create, read, update, and delete permissions to maintain integrity.

Application Menu & Modules

Application menu: op

Module: Operations Related for creating, viewing, and managing tickets.

Benefits

✅ Automates repetitive tasks like service request number generation.
✅ Reduces manual errors through predefined issue categories.
✅ Enhances accountability with clear group assignments.
✅ Improves security with role-based access control.
✅ Boosts support team productivity and reduces ticket resolution time.

Purpose

The main purpose of this project is to optimize IT support workflows by providing a structured system for creating, assigning, and resolving support tickets. By combining automation, role-based security, and simplified issue classification, the solution ensures faster response times, better visibility, and improved efficiency across support operations.
