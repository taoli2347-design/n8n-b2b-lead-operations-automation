# Sanitized Workflow Package

These workflow JSON files are portfolio-safe copies of real n8n workflows.

Sanitization applied:
- Removed n8n credential bindings.
- Removed workflow IDs, version IDs, and instance metadata.
- Replaced internal Data Table IDs and project URLs with placeholders.
- Replaced personal email, phone number, and company identity used in outreach templates.
- Replaced the Bark notification key with `YOUR_BARK_KEY`.
- Replaced the local WhatsApp bridge port with `YOUR_PORT`.
- Replaced webhook IDs with public placeholder UUIDs.
- Removed pinned data.

Important:
These files demonstrate workflow architecture and logic. They are not plug-and-play.
Before running them, configure your own n8n Data Tables, Gmail OAuth credential,
Bark/notification endpoint if used, and local WhatsApp bridge endpoint if used.
