# Scrape LinkedIn profiles in bulk from a URL file

Upload a large file of LinkedIn profile URLs. The run is concurrent and resumable, up to 1,000,000 URLs, and each row is the full profile.

Starting from $0.80 per 1,000 profiles.

Run it on Apify: https://apify.com/oday/mawsool-mass-linkedin-profile-scraper. The hosted Actor already includes access. An API key for your own integration is at [mawsool.tech](https://mawsool.tech/) and [the docs](https://docs.mawsool.tech/). Questions: osama@mawsool.tech or info@mawsool.tech.

## When this is the right Actor

The file is too large for a one-by-one scrape, and you want the full profile on every row.

## When to use a different Actor

Most of the file only needs a company and headline check. Use Profile Freshness Check first and scrape the rows that changed. Dead URLs belong in Fix Broken LinkedIn URLs.

Mawsool is not affiliated with LinkedIn.
