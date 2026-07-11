# @ai-native-solutions/meilisearch-sdk

Sovereign wrapper for **Meilisearch** · Search

**100 endpoints** wrapped from OpenAPI spec.

## Install
```bash
npm install @ai-native-solutions/meilisearch-sdk
```

## Use
```js
import Meilisearch from '@ai-native-solutions/meilisearch-sdk';
const client = new Meilisearch({ apiKey: process.env.MEILISEARCH_KEY });
```

## Endpoints (100)
- `GET /batches` · Get batches
- `GET /batches/{batchUid}` · Get one batch
- `POST /dumps` · Create a dump
- `GET /experimental-features` · Get all experimental features
- `PATCH /experimental-features` · Configure experimental features
- `GET /health` · Get Health
- `GET /indexes` · List indexes
- `POST /indexes` · Create index
- `GET /indexes/{indexUid}` · Get index
- `PATCH /indexes/{indexUid}` · Update index
- `DELETE /indexes/{indexUid}` · Delete index
- `POST /indexes/{indexUid}/delete-batch` · Delete documents by batch
- `GET /indexes/{indexUid}/documents` · Get documents
- `POST /indexes/{indexUid}/documents` · Add or replace documents
- `PUT /indexes/{indexUid}/documents` · Add or update documents
- `DELETE /indexes/{indexUid}/documents` · Delete all documents
- `POST /indexes/{indexUid}/documents/delete` · Delete documents by filter
- `POST /indexes/{indexUid}/documents/edit` · Edit documents by function.
- `POST /indexes/{indexUid}/documents/fetch` · Get documents with POST
- `GET /indexes/{indexUid}/documents/{documentId}` · Get one document
_...and 80 more_

## License
MIT · Copyright 2026 AI-Native Solutions

## Upstream
- Docs: https://www.meilisearch.com/docs/reference/api/overview
- Homepage: https://meilisearch.com
