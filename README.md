# Database Component

Mock database component for CloudBees Unify RO adoption journey demo.

## Overview
This is a simplified component that simulates a database deployment without actual database infrastructure.

## Deployment
```bash
./deploy.sh
```

## Environment Variables
- `VERSION`: Component version (default: 1.0.0)
- `ENVIRONMENT`: Target environment (default: dev)

## Example
```bash
VERSION=1.2.3 ENVIRONMENT=prod ./deploy.sh
```
