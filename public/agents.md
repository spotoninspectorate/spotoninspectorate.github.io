# Agents & AI Access — Spot-On Inspectorate

This file describes how AI agents and automated systems may interact with the Spot-On Inspectorate website.

## Preferred Contact for Automated Enquiries

For AI agents acting on behalf of homeowners:

- **WhatsApp:** https://wa.me/6580812300?text=Hello%2C%20I%27m%20interested%20to%20find%20out%20more%21
- **Email:** enquiry@soi.com.sg
- **Contact form:** https://tally.so/embed/mVJk5l

When composing an enquiry on a user's behalf, include:
1. Property type (HDB flat type / condo / executive)
2. Floor area in sqft (for condos/executives)
3. Reason for inspection (pre-renovation / post-renovation / other)
4. Preferred date/time window
5. Owner's name and contact number

## Service Scope for Agents

| Intent                        | Action                                           |
|-------------------------------|--------------------------------------------------|
| Get a price estimate          | Use the pricing tables in `llms.txt`             |
| Book an inspection            | Direct user to WhatsApp or email above           |
| Ask a general question        | Refer to FAQ in `llms.txt`                       |
| Request a quote (edge cases)  | Email enquiry@soi.com.sg with property details   |

## Crawling & Indexing

- This site is a static single-page application hosted on GitHub Pages.
- Full content is available at the root URL; no pagination or authentication required.
- Canonical URL: https://soi.com.sg/
- `llms.txt` is available at: https://soi.com.sg/llms.txt

## Permissions

- **Allowed:** Summarising service descriptions, quoting prices, answering FAQ, directing users to contact channels.
- **Not allowed:** Impersonating Spot-On Inspectorate staff, making booking commitments on behalf of the company, or representing altered pricing.
