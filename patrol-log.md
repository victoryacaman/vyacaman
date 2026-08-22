# Patrol Log — Gmail-derived (no calendar connector)

Tracks patrol-log candidates (meeting invites, reservations, appointment confirmations)
found in Gmail by the Batcomputer's recurring watch. See `CLAUDE.md` → PATROL LOG for
how this is generated and its limits — it only catches events that arrived as an email;
it misses anything created straight in a calendar app with no emailed invite.

Query used each check: `in:inbox subject:(invitation OR invite OR "invited you" OR "save the date" OR appointment OR reservation OR confirmed OR RSVP OR calendly OR zoom OR "google meet") newer_than:3d`

## Detected

<!-- one line per new item: - [YYYY-MM-DD HH:MM UTC] Subject — sender (gmail thread id: THREAD_ID) -->
(none yet)
