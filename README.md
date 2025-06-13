
# Deja2Synthetics UI

This self-hosted tool converts SmartBear DejaClick XML scripts into Elastic Synthetics JavaScript journeys.

## Features

- Upload and parse DejaClick XML
- Convert to @elastic/synthetics-compatible `.journey.ts` files
- Preview and edit journeys in Monaco editor
- Run and debug journeys with live logs

## Setup Instructions

### Backend

```bash
cd backend
npm install
node server.js
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

> Ensure `@elastic/synthetics` is installed globally or locally in backend.

### Docker (Optional)

```bash
docker-compose up
```

