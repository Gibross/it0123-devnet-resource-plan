# IT0123 DevNet Resource Validation Plan

## Student and Project

- Name: NATHAN LEI C. SANTOS
- Section: TS31
- Repository name: `it0123-devnet-resource-plan`

## Purpose

Selecting the correct DevNet resource before beginning a network-automation task is essential because it will corelate to the needs, expertise, and infrastructure of the project. Choosing the right platform minimizes the downtime needed; Also this is to prevent the disruption of resources. 

## Validated Resource Decisions

UC1 (Quick read-only API exploration) always-on-sandbox because the team required immediate access without waiting for provisioning. The official evidence used was https://developer.cisco.com/site/sandbox/.

UC2 (Private configuration testing): reservation-sandbox because the most critical requirement was gaining private administrative access while accepting setup time. The official evidence used was https://developer.cisco.com/site/sandbox/.

UC3 (Guided API concept practice): learning-lab because a beginner needs structured, guided educational content before making independent API calls. The official evidence used was https://developer.cisco.com/learning/labs/.

UC4 (Reusable automation example): code-exchange because the developer specifically needed to search and examine existing automation code repositories. The official evidence used was https://developer.cisco.com/codeexchange/.


## AI Evaluation

I accept the AI's recommendation to use UC1, because it precisely satisfies the team's problem. UC2 also provides pre-built Cisco platforms to test API and SDK without disruption. Even in UC4 I accept the recommendation as codeexchange is an official repo for devs to explore sample solutions and implementations.

## Validation Evidence

- Validator result: VALIDATION COMPLETE: 9/9 checks passed
- Command used: python validate_plan.py
- Official Cisco pages reviewed:

https://developer.cisco.com/site/sandbox/
https://developer.cisco.com/learning/labs
https://developer.cisco.com/codeexchange/

## Git Evidence

- Initial commit message: init repossitory with template README
- Validation commit message: feat: Complete student plan and pass 9 checks
- Output of `git log --oneline`:

033acf6 (HEAD -> master) feat: Complete student plan and pass 9 checks
a7c2833 init repossitory with template README

## AI-Use Disclosure

Used Gemini to assist in classifying the DevNet use cases and generating the required JSON payload. The AI successfully identified the decisive requirements for each scenario and drafted the initial summaries and rationales. I checked the official Cisco URLs to ensure they matched the expected validator formats.