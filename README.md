# Agent dostop

Google access (Gmail, Calendar, Drive, Docs, Sheets, Slides, Tasks, Contacts) for personal AI assistants that run on your own device.

This repository hosts the public pages for the app's Google OAuth consent screen:

- [Overview](https://oskarsonc.github.io/agent-dostop/)
- [Privacy Policy](https://oskarsonc.github.io/agent-dostop/privacy.html)
- [Terms of Service](https://oskarsonc.github.io/agent-dostop/terms.html)

## Permissions

| Service | Scope | Access |
|---|---|---|
| Gmail | `gmail.readonly`, `gmail.compose`, `gmail.send`, `gmail.modify`, `gmail.labels`, `gmail.settings.basic` | Read, draft, send, organize |
| Google Calendar | `calendar`, `calendar.events`, `calendar.readonly` | Read and manage events |
| Google Drive | `drive`, `drive.file`, `drive.readonly` | Read and manage files |
| Docs, Sheets, Slides | `documents`, `spreadsheets`, `presentations` (+ read-only) | Read and edit |
| Tasks, Contacts | `tasks`, `contacts` (+ read-only) | Read and manage |

The app has no server. Sign-in tokens stay on the user's device. Access can be revoked at any time in [Google Account permissions](https://myaccount.google.com/permissions).
