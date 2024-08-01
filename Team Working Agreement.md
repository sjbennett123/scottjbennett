# Team Working Agreement

**PTO & Sick Time**

- Give your Manager and the team sufficient notice
- Update the following areas for Vacation time:
  - Slack
  - Outlook
  - Team Calendar
  - Workday
- Don't work when you're sick. Take time off.
  - Designation: Sickness/Medical time off
  - Miscellaneous Paid leave - time to take care of family members
  - [U.S. Salaried Time Off Codes.pdf (sharepoint.com)](https://skydrive3m.sharepoint.com/sites/corpRC0001/Documents/Local/U.S. Salaried Time Off Codes.pdf?csf=1&e=m8OUyB&cid=1c0d7488-490f-4756-a6d4-f7a3136819eb&xsdata=MDV8MDF8fGY0ZTA0NjA5MGVlMDQ5OTg4OWQ1MDhkYmM1YmI2NTJmfGZhY2FjM2M0ZTJhNTQyNTdhZjc2MjA1YzhhODIxZGRifDB8MHw2MzgzMjExODA4NTAyMjc2Njl8VW5rbm93bnxWR1ZoYlhOVFpXTjFjbWwwZVZObGNuWnBZMlY4ZXlKV0lqb2lNQzR3TGpBd01EQWlMQ0pRSWpvaVYybHVNeklpTENKQlRpSTZJazkwYUdWeUlpd2lWMVFpT2pFeGZRPT18MXxMMk5vWVhSekx6RTVPbTFsWlhScGJtZGZUMWROTkU1WFNURk9WRlYwVFhwQk0wNURNREJOUkd4cFRGUm5lVmxVUVhST2Fsa3pXWHBSTUU1SFJtbE9la2w1UUhSb2NtVmhaQzUyTWk5dFpYTnpZV2RsY3k4eE5qazJOVEl4TWpnME1EazJ8MWE5ZmFkZGU3YTkwNGI0ODg5ZDUwOGRiYzViYjY1MmZ8ZDdhZmQ0Njc3MWNhNDYwZTg5M2NlZmIzNWMzN2FlNTk%3D&sdata=TlV0N3VrMjFPK2RvbXFRTFhFdytEUnZKdHVVQ0xDaUY4MHFjcENxYWNtVT0%3D&ovuser=facac3c4-e2a5-4257-af76-205c8a821ddb%2CA7KKDZZ@mmm.com)

**Hours of Work**

- Ensure you're working in a timeframe that supports team collaboration. Ensure you can attend:
  - Standup
  - Demos (as necessary - can be recorded and sent to Jenny ahead of time) & Planning
  - Backlog Refinement
  - Backlog Prioritization
  - QA / Dev Collaboration
  - TWA/DoR/DoD

**Ticket Communication and Work**

- Utilize comments for ticket information discovered during development.
  - If it needs to outlive the Jira, make a Wiki page with information about it and link it to the jira.
- Raise concerns of tickets you see need adjusting (DoR, irrelevant, contradictory, security, duplicating, etc) - would be nice to have a template [Jenny Nichols](https://mmodal.atlassian.net/wiki/people/70121:4978c4d9-686d-41d9-9c16-8dfe84615137?ref=confluence) look into this. - Create a template - special issue types can have templates
- Only Critical bugs after Last RC.
- Choose what you work on, speak up if overloaded.
  - [Jenny Nichols](https://mmodal.atlassian.net/wiki/people/70121:4978c4d9-686d-41d9-9c16-8dfe84615137?ref=confluence) - team needs less #1 priorities, only talk about things that will be done in the next sprint (maybe two) - utilize next two sprints bucket (only review roadmap once a month/quarter) - focus in - Actual prioritization and hold to it (defects?)
- New Features: Add documentation for IC's, DevOps, SA's, Reporting on how to set it up.

**How we Communicate**

- Slack (team)
- MS Teams (meetings, SA's/IC's)
- Wiki (feature details; technical details/ learning)
- Email (internal; official with leadership)
- Mailchimp (customers)

**Disagreements and Team Happiness**

- Talk to Philippe about concerns. 
- Be mindful of others' time zones.
- Be nice!

# Definition of Ready

***"Next two sprints - Ready" bucket should meet all these requirements.***

***[[HCC-7327\] \*TEMPLATE for new feature\* - Jira (atlassian.net)](https://mmodal.atlassian.net/browse/HCC-7327)***

- Pieces are clearly filled out
  - Description
  - Acceptance Criteria (Defining the who and what)
  - Can this be Dark Launched?
  - Notes for Development
  - Linked to Epic - unless it's a "one-off"
  - Steps to Reproduce (for Defect Tickets)
  - Release Notes for Features
  - Testing Steps
    - Can be tested
  - Documentation Impact
  - UI Impact
- Requirements understood
- UX design included, if applicable
- Known dependencies listed
- QA to gather data for testing
- For defects, test cases added to prevent bug in future

# Definition of Done

## Coding & Testing

### For Features

- Acceptance Criteria is met
- UnitTests/Integration Tests built and passing
- Build on separate feature branch
- Basic test scenarios included in QA steps, to be used with Acceptance Criteria and Release Notes (screenshot if possible)
- Add documentation for IC's, DevOps, SA's, Reporting on how to set it up
- Includes PR and Code Review
- Check with Release Coordinator to see where to check it in
- Update the Jira Status
- Watch it as QA tests it and fix any defects associated with it
  - QA adds Automated tests
  - Check and Fix existing tests that could be affected

### For Defects

- QA instructions for non-obvious steps are included
- Release Notes added/clear
- PR and Code Review
- Check with Release Coordinator to see where to check it in

## Dependencies

- Does it change the DB structure?
- Change the config template as needed
- Does this affect Provider Notifications?
- Does this affect Reporting?
- Does this affect Purges?
  - **Null values are touchy - check**
- Check for API Versioning/ 360 endpoint changes
- Check CAPD Endpoint

## Documentation

- Release Notes are written (PO)
- Screenshots of finished result is included - don't add icons - Mary will do it
- [README.md](http://readme.md/)
- Confluence page as needed
- Add documentation for IC's, DevOps, SA's, Reporting on how to set it up