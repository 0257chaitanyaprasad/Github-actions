# Salesforce Deployment Pull Request
 
Complete the applicable details. Enter N/A where a section does not apply.
 
## 1. Pull Request Details
 
Source Branch:
Example: feature/NCL-1234-affidavit-update or UAT
 
Target Branch:
Enter UAT or main
 
Deployment Environment:
 
[ ] UAT
[ ] Production
 
Deployment Scope:
 
[ ] Single Jira story
[ ] Multiple Jira stories
[ ] Approved release
 
Jira Number(s) and Link(s):
List all Jira stories included in this Pull Request.
 
Confluence Page:
Paste the related Confluence page, or enter N/A.
 
Change Summary:
Briefly explain what changed and why.
 
 
## 2. Apex Testing
 
Are Apex classes or triggers included?
 
[ ] No
[ ] Yes
 
Apex Classes / Triggers:
List the Apex classes or triggers, or enter N/A.
 
Related Test Classes:
Required when an Apex class or trigger is included. Enter N/A otherwise.
 
Relevant Code Coverage:
Coverage must be more than 75% for Apex changes. Enter N/A otherwise.
 
 
## 3. Deployment Tasks
 
Pre-Deployment Tasks Required?
 
[ ] No
[ ] Yes
 
Pre-Deployment Tasks and Owner:
Enter the tasks and responsible owner, or enter N/A.
 
Post-Deployment Tasks Required?
 
[ ] No
[ ] Yes
 
Post-Deployment Tasks and Owner:
Enter the tasks, responsible owner, and validation required, or enter N/A.
 
 
## 4. Rollback Plan
 
Rollback Required If:
Describe the conditions that would require a rollback.
 
Rollback Steps:
 
1.
2.
3.
 
Rollback Owner:
Enter the responsible person or team.
 
Rollback Validation:
Explain how the previous working state will be confirmed.
 
 
## 5. Reviewer Checklist
 
[ ] Source and target branches are correct
[ ] Jira link and change summary are provided
[ ] Confluence page is provided or marked N/A
[ ] Apex classes and related test classes are listed or marked N/A
[ ] Relevant Apex coverage is more than 75% or marked N/A
[ ] Pre-deployment tasks are provided or marked N/A
[ ] Post-deployment tasks are provided or marked N/A
[ ] Rollback plan is complete
[ ] Required pipeline checks passed
[ ] Pull Request is ready for approval and merge
