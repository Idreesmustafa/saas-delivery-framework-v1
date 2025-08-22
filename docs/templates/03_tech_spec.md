# Technical Specification (FE + BE)

Feature name:
Owner(s):
Date:
Related docs: (Problem Review, UI/UX Review, Figma, tickets)

Overview:
(What the feature does, who it impacts, success criteria.)

## Data model / schema
Canonical model (JSON example):
```json
{
  "id": "uuid",
  "companyId": "uuid",
  "status": "draft|active|archived",
  "config": { "exampleFlag": true, "threshold": 3 },
  "createdAt": "iso8601",
  "updatedAt": "iso8601"
}
