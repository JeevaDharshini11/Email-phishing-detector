# Email-phishing-detector
Rules used:
KeywordRule: checks for words like “urgent”, “password”, “win”.
LinkRule: checks if links are fake or not secure.
SenderRule: checks if the sender address is suspicious.

Project Workflow:
User enters email details (sender, subject, body, links).
The system applies multiple phishing rules.
Each rule checks for suspicious signs.
If any rule detects a problem → email is marked as phishing.
Otherwise → email is safe.
