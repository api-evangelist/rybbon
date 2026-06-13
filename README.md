# Rybbon

Rybbon (now BHN Rewards) is a digital rewards management platform with a REST API for sending gift cards and prepaid virtual cards, managing reward campaigns, tracking recipient engagement, and accessing reward analytics. The platform supports both Instant Rewards and Points-to-Rewards integration models, authenticated via OAuth 2.0 client credentials, and serves marketing, market research, academic research, and employee incentive use cases globally.

**Website:** https://www.bhnrewards.com/  
**Developer Docs:** https://developer.bhnrewards.com/  
**Status Page:** https://status.rybbon.net/  
**Pricing:** https://www.bhnrewards.com/pricing/  
**Blog:** https://www.bhnrewards.com/blog/

## APIs

- **Instant Rewards API** — Send digital gift cards, virtual Visa/Mastercard, and other rewards instantly to recipients via REST API.
- **Points-to-Rewards API** — Allocate points to recipients programmatically; recipients redeem points for digital rewards.

## Authentication

OAuth 2.0 client credentials flow. Obtain a Client ID and Client Secret from BHN Rewards Settings → API, then exchange them at `https://oauth.rybbon.net/oauth2/token` for a Bearer token used on all API calls.

## Resources

- [Plans & Pricing](plans/rybbon-plans-pricing.yml)
- [Rate Limits](rate-limits/rybbon-rate-limits.yml)
- [FinOps](finops/rybbon-finops.yml)
- [APIs.json](apis.yml)
