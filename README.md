# 990ready-site

The public holding page at https://990ready.com, served by GitHub Pages from `main`. It says what 990 Ready is and that it opens for the 2027 filing season, and points to Obligare's free calendar until then.

990 Ready is a product of Alleviate Technologies, Inc. The product itself will run on the Obligare platform; when it does, the domain moves there and this repository is archived.

- `index.html`: the page, one file, no build step. Obligare's design language (Instrument Serif, DM Sans, Obsidian) with 990 Ready's green accent.
- `fonts/`: the same self hosted fonts as obligare.com (SIL Open Font License).
- `CNAME`: the custom domain. DNS is at GoDaddy: four A records for GitHub Pages on `@`, and `www` as a CNAME to `alleviate-technologies.github.io`. 990ready.us, 990ready.org, get990ready.com and get990ready.org forward here (GoDaddy domain forwarding, permanent, to https://990ready.com).

House style: American English, no em dashes, no hyphenated compound modifiers. The page makes no claim that 990 Ready files returns.
