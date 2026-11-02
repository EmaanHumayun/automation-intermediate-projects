# Project Index — Level 2: Intermediate

Detailed technical briefs for all projects in this tier.


---

### Project 06: CRM Lead Management Automation
- **Directory**: [`06-crm-lead-management-automation`](./06-crm-lead-management-automation)
- **Status**: `Planned`
- **Core Technology**: Node.js, Express, HubSpot/Mock CRM API, Redis, BullMQ
- **Summary**: Automated lead ingest pipeline syncing webhooks from inbound marketing to CRM platforms with qualification scoring and deduplication.
- **Problem Solved**: Sales teams lose qualified leads due to delayed manual data entry into CRM and lack of automated lead scoring.
- **Key Concepts**: CRM contact lifecycles, lead scoring algorithms, asynchronous queue workers, OAuth 2.0 token refreshes, deduplication lookups.


---

### Project 07: E-commerce Order Automation
- **Directory**: [`07-ecommerce-order-automation`](./07-ecommerce-order-automation)
- **Status**: `Planned`
- **Core Technology**: Node.js, PostgreSQL, Stripe Webhooks, Redis, BullMQ
- **Summary**: Transactional order processing pipeline handling payment webhooks, inventory decrement, receipt generation, and fulfillment dispatch.
- **Problem Solved**: E-commerce platforms require bulletproof order processing that never loses an order during traffic spikes or payment gateway retries.
- **Key Concepts**: Stripe signature verification, database transactions (ACID), idempotency tables, distributed job queues, customer receipt dispatch.


---

### Project 08: Social Media Content Publishing Automation
- **Directory**: [`08-social-media-content-publishing-automation`](./08-social-media-content-publishing-automation)
- **Status**: `Planned`
- **Core Technology**: Python, Meta Graph API, X API, Cron, S3 Object Storage
- **Summary**: Multi-platform content scheduling engine publishing text and media across social networks with platform-specific formatting and telemetry.
- **Problem Solved**: Publishing content manually across multiple social networks leads to formatting errors, inconsistent timing, and tedious administrative overhead.
- **Key Concepts**: Platform rate limiting, image resizing/aspect ratio adaptation, scheduled database polling, OAuth token refreshing, social analytics capture.


---

### Project 09: Customer Support Ticket Automation
- **Directory**: [`09-customer-support-ticket-automation`](./09-customer-support-ticket-automation)
- **Status**: `Planned`
- **Core Technology**: Node.js, Express, Zendesk/Helpdesk API, Slack API, Regex/NLP
- **Summary**: Intelligent ticket triage and dispatch engine evaluating customer urgency, assigning priority tags, and alerting on-call engineers.
- **Problem Solved**: High volumes of customer support tickets cause critical outages to sit in general queues without immediate triage.
- **Key Concepts**: Keyword sentiment analysis, SLA escalation triggers, webhook notifications, Slack channel alerting, automated acknowledgment emails.


---

### Project 10: Invoice and Payment Reconciliation Automation
- **Directory**: [`10-invoice-and-payment-reconciliation-automation`](./10-invoice-and-payment-reconciliation-automation)
- **Status**: `Planned`
- **Core Technology**: Python, Pandas, Stripe API, PostgreSQL, SMTP Reporting
- **Summary**: Financial automation engine matching payment gateway settlements against internal accounting records and detecting fee discrepancies.
- **Problem Solved**: Finance teams spend hours manually cross-referencing bank payouts, payment processor transaction fees, and internal order records.
- **Key Concepts**: Batch transaction ETL, data joining with Pandas, floating-point currency safety, automated audit report generation, discrepancy alerting.
