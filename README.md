# Mass LinkedIn Profile Scraper | Bulk URLs

**Process large LinkedIn URL files with concurrent, resumable runs and every source field preserved.**

Designed for bulk profile lists. Paste URLs, upload CSV, set concurrency, and optionally provide a `resumeId`. Re-running with the same ID skips URLs already completed. Starting from $0.80 per 1,000
## Check the company and headline before you pay for the full profile

[Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) returns the current company and headline, starting from $0.40 per 1,000. It does not decide whether they match your CRM. Compare the two fields yourself, then run this scraper only on the rows you want to refresh.

At Diamond prices, 10,000 full profiles cost $8. Checking all 10,000 first costs $3. If 1,500 of them need this scraper at $0.80 per 1,000, the refresh is $4.20 instead of $8.


## If you need a different Mawsool Actor

| If this is what you need | Open |
| --- | --- |
| You have an email and want the LinkedIn profile. | [Reverse Email Lookup](https://apify.com/oday/mawsool-email-linkedin-lookup) |
| You have a name and company and want the profile URL. | [LinkedIn Profile Finder](https://apify.com/oday/mawsool-linkedin-profile-finder) |
| You have a profile URL and want the personal email. | [LinkedIn Email Finder](https://apify.com/oday/mawsool-linkedin-personal-email-finder) |
| You only need the current employer, before paying for a full profile. | [Current Company Checker](https://apify.com/oday/mawsool-linkedin-company-checker) |
| You want the current company and headline, and you will compare them to your CRM yourself. | [Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) |
| You want an alert when the employer or headline changes. | [Job Change Tracker](https://apify.com/oday/mawsool-linkedin-job-change-watch) |
| You have a profile URL and want the full profile. | [LinkedIn Profile Scraper](https://apify.com/oday/mawsool-linkedin-profile-details) |
| You want the current employer's website from a profile URL. | [Profile to Company Website](https://apify.com/oday/mawsool-linkedin-profile-to-company-website) |
| You want the job history only. | [Work Experience](https://apify.com/oday/mawsool-linkedin-profile-experience) |
| You want schools and degrees only. | [Education](https://apify.com/oday/mawsool-linkedin-profile-education) |
| You want a yes or no for one certificate. | [Certification Checker](https://apify.com/oday/mawsool-linkedin-certification-checker) |
| You want certificates, patents, courses, and publications. | [Certifications and Patents](https://apify.com/oday/mawsool-linkedin-profile-credentials) |
| You want likes and comments for outreach. | [Profile Activity](https://apify.com/oday/mawsool-linkedin-profile-activity) |
| You have a company URL and want the full company record. | [Company Details](https://apify.com/oday/mawsool-linkedin-company-details) |
| You have a large file of company URLs. | [Mass Company Scraper](https://apify.com/oday/mawsool-mass-linkedin-company-scraper) |
| You want the website, industry, and employee range. | [Firmographics and Website](https://apify.com/oday/mawsool-linkedin-company-firmographics) |
| You want office addresses. | [Company Locations](https://apify.com/oday/mawsool-linkedin-company-locations) |
| You want lookalike companies. | [Similar Companies](https://apify.com/oday/mawsool-linkedin-similar-companies) |
| You want the recent posts on a company page. | [Company Posts](https://apify.com/oday/mawsool-linkedin-company-posts) |
| You want only new posts on the next scheduled run. | [Company Post Monitor](https://apify.com/oday/mawsool-linkedin-company-post-watch) |

The same list is on [Mawsool's Apify profile](https://apify.com/oday).

## Use with AI agents

Apify exposes this Actor to ChatGPT, Claude, Gemini, Grok, and other agents through the Apify MCP server. Tell the agent the input you have, the fields you want back, and the starting price on this page. If you already have profile URLs and only need the current company and headline, use [Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) first and compare the result to your CRM yourself.

 A visitor who starts on one Actor can open the rest from that page.

## Can it handle millions of LinkedIn URLs?

The Actor accepts up to **1,000,000 unique URLs per run**. Completion depends on your Apify timeout, spending limit, plan, and chosen concurrency. Start with 1,000 URLs, measure throughput, then scale.

## What data is returned?

The same complete source payload as LinkedIn [Profile Details](https://apify.com/oday/mawsool-linkedin-profile-details): profile identity, about, current company, experience when available, education, courses, languages, certifications, publications, patents, organizations, activity, followers, connections, and all other API fields.

This is not a guaranteed complete employment timeline. Experience dates can be empty; email and phone are not included.

## Pricing

Same data, same price as the standard Actor: **$1.80 / 1,000** on FREE, with automatic paid-plan discounts down to $0.80 / 1,000.

## Operational controls

- 1–100 concurrent requests.
- `maxUrls` cost cap.
- `resumeId` persists one completion marker per URL.
- Stops when the run spending limit is reached.

## FAQ

### When do I use the mass profile Actor?

Use it for lists up to 1,000,000 profile URLs. The price per profile is the same as [Profile Details](https://apify.com/oday/mawsool-linkedin-profile-details), $1.80 per 1,000. A stopped run continues finished URLs on the next start.
