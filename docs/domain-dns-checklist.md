# Domain And DNS Checklist For yibinfan.cc

## Buy The Domain

1. Search for `yibinfan.cc` at a registrar.
2. Register it for at least 2 years if the price is reasonable.
3. Enable auto-renew.
4. Enable domain lock.
5. Enable WHOIS/privacy protection if offered.

## Connect Hosting

Choose one:

- Cloudflare Pages
- GitHub Pages
- Netlify
- Vercel

Typical DNS records:

```text
@      A or CNAME      host-provided value
www    CNAME           host-provided value
```

The hosting provider will give the exact values.

## Email

Optional but professional:

```text
yibin115@uw.edu
yibin@yibinfan.cc
```

Possible providers:

- Google Workspace
- Microsoft 365
- Fastmail
- Proton Mail

## Redirects

Make sure all of these resolve cleanly:

- `https://yibinfan.cc`
- `https://www.yibinfan.cc`
- `http://yibinfan.cc`
- `http://www.yibinfan.cc`

Pick either root or `www` as canonical. For a personal site, root domain is usually cleaner:

```text
https://yibinfan.cc
```

