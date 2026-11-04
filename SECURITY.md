# Security and privacy

NoteReach's source repository is private. For a sensitive report, contact Mathew through the dev-site support channel or use GitHub's private vulnerability reporting if it is enabled for the public binary-distribution repository. If no private route is listed, request one without including sensitive details. Do not publish an exploit, credential, private score or sensitive diagnostic in a public issue.

The app's Dorico authorization token belongs in macOS Keychain. It should never appear in logs, issues, screenshots, test fixtures or source control. Tests use synthetic tokens and in-memory stores.

Keyboard Maestro setup backups can contain an entire personal macro library. They stay in the user's Application Support directory and must not be uploaded as bug-report attachments. Review any diagnostic before sharing it.

The beta has no guaranteed security-response timeline. Fixes will target the current release; please update before retesting a report.
