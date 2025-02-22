---
title: Countries
---

import useBaseUrl from '@docusaurus/useBaseUrl';

Your "**Countries**" report shows where in the world your visitors are coming from. You can click on the "details" button to see the full list of countries ranked by the number of visitors. There you can also see the percentage of your total traffic the individual country stands for.

<img alt="Countries" src={useBaseUrl('img/countries.png')} />

## How it works

Plausible uses the [MaxMind GeoIP database](https://www.maxmind.com/en/home) to determine the visitor country based on their IP address. The IP address itself
is discarded to make sure we do not store any personal data.

:::note
Do you see wrong data in your countries report? Are you using Cloudflare and having your sites proxied? A proxy can override the remote IP which would lead to wrong geolocation data in your stats. Remove the proxy and make it just a DNS record in your Cloudflare settings to solve the issue.
:::
