# Airtable

This directory contains scripts and configuration for managing metadata and content operations using Airtable.

Recommended tasks:

- Set up an Airtable base with tables for content deliverables/requests, campaign tracking, objectives, and team, as suggested in Airtable's content operations guide ([www.airtable.com](https://www.airtable.com/guides/marketing/how-to-use-airtable-for-content-operations)).
- Define fields for content source (e.g., platform, URL), posting date, and user interaction metrics (likes/comments/shares) to evaluate relevance.
- Create scripts to sync new content metadata and relevance scores from ingestion/embedding processes into Airtable.
- Configure integration with Pinecone via workflow tools (e.g., BuildShip) to automatically upsert vectors when a new record is added ([buildship.com](https://buildship.com/integrations/apps/airtable-and-pinecone#:~:text=integrate%20Airtable%20and%20Pinecone%20Step,3%20%20Documentation)).
- Use Airtable automations or API to update relevance scores based on user interactions and feedback over time.
