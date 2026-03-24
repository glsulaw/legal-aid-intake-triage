# [Legal-aid-triage]
## What This Skill Does
[This skill transforms Claude into a specialized intake assistant for legal aid organizations or court self-help centers. It handles the "front door" of legal requests by systematically gathering jurisdictional data, identifying the specific legal issue (e.g., housing, debt, family law), and flagging high-priority emergencies like illegal lockouts or domestic violence. By guiding users through a structured fact-gathering process, it prepares a clear summary of the situation for human advocates while providing the user with immediate, plain-language legal information and resource referrals.]
## How to Use
1. Download the `SKILL.md` file from this repository
2. Go to claude.ai → Settings → Skills
3. Upload the `SKILL.md` file
4. Toggle the skill on
5. Start a new conversation and try one of the sample prompts below
## Sample PromptsTry these prompts to test the skill:
- "I just got a paper taped to my door called a 'Five-Day Notice to Quit' and I don't know what to do."
- "My landlord changed the locks while I was at work and my cat is still inside. Can they do that?"
- "I'm being sued by a credit card company in East Baton Rouge Parish and I have a court date next week.""
## Design Notes
- **Scenario:** [Option A — Legal Aid Intake Triage]
- **Workflow steps:** 7 distinct steps, moving from safety/jurisdiction to fact-gathering, and ending with resource mapping and urgency summaries.- **Key design choice:** The most important decision was implementing a "Safety First" trigger. Before asking any details about the legal merits of a case, the skill is hard-coded to check for immediate physical danger or illegal lockouts. This ensures that a user in crisis gets a hotline number or emergency instructions before spending time answering administrative questions.
## DisclaimerThis skill provides general legal information only — not legaladvice. It was created as a class project for LAW 5642: LegalAnalytics and Generative AI at LSU Law School. Users shouldconsult a licensed attorney for guidance specific to theirsituation.
## Author
G.Albini · LSU Law School · Spring 2026
## License
MIT License — see LICENSE file for details.
