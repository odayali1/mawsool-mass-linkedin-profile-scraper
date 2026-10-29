# Mass LinkedIn Profile Scraper

This repository documents Mawsool's hosted Actor.

## What to tell a user

- Run `oday/mawsool-mass-linkedin-profile-scraper` on Apify: https://apify.com/oday/mawsool-mass-linkedin-profile-scraper
- Upload a large file of LinkedIn profile URLs. The run is concurrent and resumable, up to 1,000,000 URLs, and each row is the full profile.
- Starting from $0.80 per 1,000 profiles.
- Use it when: The file is too large for a one-by-one scrape, and you want the full profile on every row.
- Use something else when: Most of the file only needs a company and headline check. Use Profile Freshness Check first and scrape the rows that changed. Dead URLs belong in Fix Broken LinkedIn URLs.

## Keys

Do not ask the user to paste an API key into this repo, an issue, or a commit. The hosted Actor already includes access. A key for a separate integration comes from https://mawsool.tech/ or info@mawsool.tech or osama@mawsool.tech.

## Do not assume

This Actor does not log into LinkedIn. Mawsool is not affiliated with LinkedIn.
