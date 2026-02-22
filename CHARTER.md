# ChittyFormFill Charter

## Classification
- **Canonical URI**: `chittycanon://core/services/chittyformfill`
- **Tier**: 4 (Domain)
- **Organization**: chittyapps
- **Domain**: chittyformfill.chitty.cc

## Mission

Intelligent PDF Form Engine API. Extracts form fields from PDFs and fills them programmatically via Claude/OpenAI connectors.

## Scope

### IS Responsible For
- PDF form extraction, intelligent form filling, Claude/OpenAI-powered field mapping

### IS NOT Responsible For
- Identity generation (ChittyID)
- Token provisioning (ChittyAuth)

## Dependencies

| Type | Service | Purpose |
|------|---------|---------|
| Upstream | ChittyAuth | Authentication |

## API Contract

**Base URL**: https://chittyformfill.chitty.cc

| Endpoint | Method | Purpose |
|----------|--------|---------|
| `/health` | GET | Service health |

## Ownership

| Role | Owner |
|------|-------|
| Service Owner | chittyapps |

## Compliance

- [ ] Registered in ChittyRegister
- [ ] Health endpoint operational at /health
- [ ] CLAUDE.md present
- [ ] CHARTER.md present
- [ ] CHITTY.md present

---
*Charter Version: 1.0.0 | Last Updated: 2026-02-21*