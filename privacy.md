---
title: Personal AI Team Privacy Policy
---

# Privacy policy

Effective date: 5 November 2026

Personal AI Team is operated by its owner for personal task coordination and
archive recovery. This policy describes the application's Google Drive access.

## Data accessed and purpose

The application requests only Google's `drive.file` permission. It creates and
uses a dedicated operational folder and accesses registered project archive
files within its application-level boundary. It reads file identifiers,
metadata, versions and archive contents to synchronize, check integrity and
restore operational history. It also reads the signed-in Google account email
through Drive to ensure the intended account is being used.

Archives can contain task instructions, agent responses, event history and
generated artifacts selected by the owner for the project. They do not contain
OAuth credentials. The synchronization component does not request permission to
read all files in the owner's Drive.

## Storage and security

Operational archives are stored in the owner's Google Drive and in local
working, queue, recovery or backup directories. OAuth refresh credentials are
stored in Windows Credential Manager. They are not placed in project archives,
prompts, source control or this website. Transfer checksums and remote readback
are used to detect changed or incomplete archives. These safeguards do not
provide isolation from arbitrary programs running as the same Windows user.

## Sharing and use by AI tools

The Drive synchronization process transfers data between the owner's computer
and Google Drive. It does not invoke AI models. Separately, when the owner runs
an AI task, explicitly configured tools may receive the task context the owner
has authorized. Their processing is governed by their respective services and
the owner's settings. Google authorization credentials are not supplied to
those tools through task context.

The application does not sell Google user data, use it for advertising or
provide it for credit decisions. It does not use Google user data to develop or
train generalized AI or machine-learning models. Personal AI Team's use and
transfer of information received from Google APIs will adhere to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Retention, revocation and deletion

The owner controls local copies and Drive archives. Failed synchronization
leaves pending data locally; verified cache copies may be removed according to
the configured cache policy. Historical archives and backups are not
automatically deleted by the current setup.

The owner can revoke the application's access in Google Account settings and
remove its Windows Credential Manager entry. Revocation stops future authorized
access but does not itself delete previously stored archives or local copies.
The owner may delete those copies separately through the storage services or
local filesystem. Recovery should account for any deletion instructions before
restoring old data.

## This information website

This website does not request Google sign-in, collect task data, or contain
application analytics. Its hosting provider may process ordinary web requests
under its own privacy policy. No private operational archive is published here.

## Contact and changes

Questions or deletion assistance: [xiaoduowang1998@gmail.com](mailto:xiaoduowang1998@gmail.com).
This policy will be updated before materially changing the application's data
practices; the effective date above identifies this version.

[Application home](index.html) · [Terms of use](terms.html)
