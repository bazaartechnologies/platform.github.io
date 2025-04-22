# DefectDojo Playbook

## Table of Contents

- [Introduction](#introduction)
- [Accessing DefectDojo](#accessing-defectdojo)
- [Viewing Your Engagements](#viewing-your-engagements)
- [Managing Test](#managing-tests)
- [Managing Tickets](#managing-tickets)
- [Adding Comments](#adding-comments)
- [Best Practices](#best-practices)
- [Need Help?](#need-help)

## Introduction
DefectDojo is an open-source application vulnerability management tool used to track findings, perform security testing, manage engagements, and streamline communication with developers and stakeholders. It is commonly used by security engineers, developers, and product owners to manage the lifecycle of vulnerabilities.

## Accessing DefectDojo
1. Visit the DefectDojo instance behind the teleport.
    - [http://defectdojopoc.bazaar-engineering.com/](http://defectdojopoc.bazaar-engineering.com/)
2. Login using your corporate credentials.
3. You will land on the dashboard where you can see statistics, recent engagements, and findings

## Viewing Your Engagements
1. From the sidebar, click Engagements under the Product menu
2. Use filters to narrow by Engagements, Product or Status.
3. Click on any engagement to view:
    - **Test type** (e.g., API Scan, Web App Pentest, Gateway Cleaning)
    - **Engagement dates and status**
    - **Associated findings**

## Managing Tests
Each engagement can have associated tests to evaluate the product's security posture.

1. Navigate to the **Tests** tab inside an engagement
2. Click on a test to view details.

## Managing Tickets
1. Navigate to the **Findings** tab inside **Tests**
2. Click on a finding to view its details

## Request Peer Review
Once you understand and fix the ticket (finding), you can initiate a peer review.

1. After addressing the issue in the finding, click on the hamburger (three horizontal lines) icon on the right side of the finding.
2. Select **Request Peer Review** from the dropdown menu.
3. Add the **Reviewers** (team members you want to review the fix).
4. Add any relevant **comments** or notes for the review process.
5. The reviewers will be notified and can provide feedback or approve the fix.

## Watch This Video

Here’s a video demonstrating the process:
- [Click here to watch the video](https://drive.google.com/file/d/1kU5grMyA2Z2lui-zGr7du4HiqhjMXNGP/view?usp=drive_link)

## Best Practices
- Add meaningful descriptions and comments on findings
- Regularly update finding statuses and resolutions
- Use tags to classify or prioritize findings
- Resolve findings after proper validation
- Maintain consistent documentation of actions taken

## Need Help?

If you need assistance:
- Contact the security team on slack: @engr_security

