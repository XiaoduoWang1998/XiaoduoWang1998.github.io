---
title: Personal AI Team
---

# Personal AI Team

Personal AI Team is a personal, locally operated task coordinator. It organizes
tasks, agent responses and generated project artifacts, then saves recoverable
operational archives in the owner's Google Drive.

## Why the application connects to Google Drive

The desktop application uploads project archives, downloads them to verify their
checksums, and restores them when the owner requests recovery. It uses the
`drive.file` permission, which covers specific files created by or explicitly
opened with the application. An additional application allowlist limits normal
operations to its dedicated operational folder and registered files.

The application does not request full Google Drive access. The owner signs in
directly with Google. Refresh credentials are stored in Windows Credential
Manager on the owner's computer, outside the archive and this website.

## Personal use and control

This application is intended for its owner's personal use. Local project data
remains queued if synchronization fails. Archives are verified before the
application records successful publication. The owner chooses which configured
AI tools receive task context; the Drive synchronization process itself does
not call AI models. Paid model APIs are disabled by default.

This website contains application information only. It does not provide access
to the owner's Drive, credentials, task conversations or personal memory.

[Privacy policy](privacy.html) · [Terms of use](terms.html)

Contact: [xiaoduowang1998@gmail.com](mailto:xiaoduowang1998@gmail.com)
