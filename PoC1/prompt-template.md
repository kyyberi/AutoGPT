We are building a data product which has metadata model descibed in attachment JSON Schema. 

Write needed Scrum user stories to be imported to JIRA for the below described EPIC for a data product. User stories should indicate how to build the data product. Try to analyze what data is needed, how to present it, which pricing models to apply. The stories must utilize the mentioned JSON schema. Create user stories for each of these elements: "product", "pricingPlans", "dataOps", "dataAccess", "dataQuality", "SLA", "license", "dataHolder"

Product owner provided JIRA and generation configuration: 
    -    EPIC KEY: "AID-29"
    -    Granularity: Minimum of 5 user stories, even more is better. 
    -    Project name: "AI-developer"
    -    Project Key: "AID"

EPIC CONTENT:
Objective: Implement Lead Response Time (LRT) as a Key Performance Indicator (KPI) to measure and improve the efficiency of the sales team’s response to inbound leads. The result is a data product, which is a periodically updated dataset.

Driver: Quick response to potential customers is critical in today’s competitive market. The faster a company can respond to a lead, the higher the chance of conversion.

Usage scopes: Company Internal

Industry: Mining equipment

Value proposition: By monitoring and improving Lead Response Time, the company can enhance the effectiveness of the sales funnel, thereby driving revenue growth and improving the overall performance of the sales department. 
More detailed value propositions: Increased lead conversion rates due to timely engagement, Enhanced customer satisfaction and experience, Data-driven insights to optimize sales processes and training.


EXAMPLE CSV OUTPUT FOR USER STORY:
*User story:*  \\
As an ODP system, I want to automatically monitor the SDI system every day 
at 2am to check for new, unpublished, or updated layers in order to keep the 
ODP updated. 
\\ 
\\ *Acceptance criteria:*  \\
- ODP system successfully connects to SDI using REST APIs \\
- ODP system can identify new, unpublished, or updated layers from SDI. \\
- Automated tests confirm the monitoring function works as expected. \\
\\ 
\\ *Privacy and security requirements:*  \\
- Ensure secure connection to SDI APIs. \\
- No personal data should be accessed or stored. \\
\\ 

Output rules for the CSV output:
- no do not show just a few user stories, generate all user stories
- Important: keep each user story on one line in the CSV
- Header fields of the CSV: "Epic", "ProjectType", "IssueType", "Summary", "Description", "Project Name", "Project Key"
- in header Epic value must always be EPIC KEY given in the beginning
- All values in user story line fields must be encapsulated both sides with  single " char
- ProjectType is always: "Software"
- IssueType is always “Story”
- MUST HAVE: Keep example formatting chars: *, \\
- Output MUST be a single CSV file