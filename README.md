# QA - Mobile + SaaS Dashboard

Junior QA Engineer | Mobile iOS/Android + API + Dashboard

## TC-07: Project Sync Test
**Precondition:** Logged in iOS app + Web dashboard
**Steps:**
1. Create project "QA-Sync-Test" on iOS
2. Verify 201 response POST /api/projects in Postman
3. Query DB to confirm exists
4. Refresh SaaS dashboard Chrome - project appears
5. Validate fields match mobile vs web
6. Offline edit then online - sync works
**Expected:** Data consistent, no duplication
**Tools:** Postman, Jira, GitHub Issues, BrowserStack

## Bug Report Template
Title: [Critical] Short summary
Steps to Repro, Expected vs Actual, Video, Device
