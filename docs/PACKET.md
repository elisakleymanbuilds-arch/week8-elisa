Problem
When a person in Mexico loses control of her accounts and her identity is used to impersonate her, there is no single place to go. She has to visit the Cyber Police, the INE, the Fiscalía, and CONDUSEF, one by one, while the scam is still running. My role is OPERATOR so my problem is not the victim's pain directly. My problem is this: who helps the first person, what breaks first, and what happens when there are 100 cases. I use the case of Madel from my earlier brief as evidence, not as a new interview. The operational gap is a usable sequence of next steps when the victim is scared, locked out, or using a phone that may still be compromised.

Exact User
The exact user is a case coordinator in a small pilot help desk for breach victims in Mexico. The coordinator works with a backup and a verified referral directory. The service has limited hours. The coordinator is not a lawyer, not a bank employee, and not a police officer. She supports navigation. The decisions about account recovery, freezes, complaints, and refunds belong to the institutions, not to her. The coordinator must not ask for IDs, passwords, codes, or private messages.

Success Definition
Before this module closes, a coordinator can open the live URL, walk through a fictional breach case in Spanish, receive a usable first-hour plan, see which institution is responsible for each step, and export a local evidence packet. The tool never uploads IDs, passwords, codes, or private messages. The tool shows service hours, waiting status, and a safe-device alternative on every screen.

Mockup Description
A simple browser page with a blue header that says "First Hour - Breach Victim Assistant". Under the header there is a small banner that says "Simulated data, no personal data is stored." Below that there are two buttons: "Start intake" and "See wait times". The intake page has four simple questions in Spanish: what happened, is your current device safe, what institution have you already contacted, and what is your main worry. After the questions, the tool shows a priority level, a short checklist, and the name of the institution responsible for each step. At the bottom there is a button that says "Export local packet" and a footer that says the tool does not store personal data and does not replace the police, the bank, or the Fiscalía.



Benchmark
The best existing solutions on Earth for this are IdentityTheft.gov from the US FTC, the GoFundMe route for reporting a fundraiser created in someone's name, and the UK ICO breach assessment tool. Mine differs and localizes by adapting their sequence into one short Spanish flow with a local evidence packet and verified Mexican referral routes, and by making the operational limits visible: service hours, waiting status, and a safe-device branch on every screen. The reason this has not reached Mexico is that there is no shared national fraud intake, no data bridge between the Buró de Crédito and CONDUSEF, and no legal path for a civil triage service to hand evidence directly to the Fiscalía. A Mexican version does not need to copy their budget. It needs to copy their shape: one intake, one case coordinator, one honest sequence.

Long View
In three years, this could become a small, open first-hour layer that any civil help desk, university clinic, or bank call center can adapt without holding the victim's private data. It would always say what the service does not do, and it would always point to the institution that can actually act. The goal is not to replace the police or the bank. The goal is to make sure that no victim in Mexico spends her first hour alone and confused.






Scope Cut
No bank API. No government API. No platform API. No server-side storage of personal data. No ID uploads. No password or code collection. No automated sending, freezing, or complaints. No 24/7 promise. No guarantee of refund or recovery. No ride-hailing or unrelated features. All cases in the prototype are fictional and labeled as simulated.

Architecture + Stack

Layer
Tool / Tech
Purpose
Frontend
HTML5, CSS3, Vanilla JavaScript
Simple browser interface that runs on any phone or laptop.
Decision logic
Rule-based classifier in JavaScript
Assigns priority based on case type and answers.
AI helper
LLM rewriting of the coordinator's notes into plain Spanish, no personal data sent
Makes the checklist easier to read.
Data
Fictional case JSON, labeled on screen
Avoids pretending to have real integrations.
Deployment
GitHub Pages
Free hosting with a public live URL.



Test Plan
Open the URL and start the intake as a coordinator. Confirm the safe-device question appears first.
Choose "device not safe" and confirm the safe-device alternative and printable route appear.
Choose "device safe" and complete the four intake questions. Confirm a priority level and checklist appear.
Confirm the responsible institution appears for each step.
Confirm the export local packet button works and produces a printable view.
Confirm the footer states clearly that the tool does not store personal data and does not replace the police, the bank, or the Fiscalía.
Confirm no field anywhere asks for an ID, password, code, or private message.

