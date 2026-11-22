# QA Testing Portfolio

Hands-on manual testing practice by an aspiring QA tester with a finance and pensions background. The project uses a made-up pension contribution form, so no real systems or member data are involved.

## The scenario
A member enters a monthly pension contribution. The requirements are:
1. The member enters a monthly contribution in whole pounds
2. The valid range is £50 to £500 inclusive
3. Amounts outside the range show an error message and are not saved

## What's in this repository

| Document | What it shows |
|---|---|
| [Requirements review](requirements-review.pdf) | Gaps and ambiguities found in the requirements, each with problem, impact, question for the business analyst and priority |
| [Test cases](test-cases.pdf) | 9 test cases using boundary value analysis and invalid-input tests, with results and links to Jira tickets |
| [Jira screenshots](jira-screenshots.pdf) | Kanban board, bug reports and requirement review tickets |

## What I did
- **Reviewed requirements (static testing):** found gaps such as undefined behaviour for decimals (£50.50), blank and non-numeric input, existing contributions, and save failures, then prioritised them High, Medium or Low.
- **Designed test cases:** used two-value boundary value analysis (£49, £50, £500, £501) plus a mid-range value and invalid inputs.
- **Logged defects in Jira:** two bugs where out-of-range amounts (£49 and £501) were wrongly accepted, each linked to its failed test case.
- **Handled unclear requirements:** where the expected result wasn't defined, I raised a Jira ticket and marked the test as not run rather than guessing.

## Tools and techniques
Jira (Kanban and Scrum), Excel, boundary value analysis, equivalence partitioning, requirements review, bug reporting, test case design.

## Currently learning
Preparing for the ISTQB Certified Tester Foundation Level exam, with API testing (Postman), SQL and basic test automation (Playwright) next.

## Notes
The test results are practice data: there is no real system under test. This repository will grow as I add API testing, SQL and automation projects.
