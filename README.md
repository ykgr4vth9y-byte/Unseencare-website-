# Unseen Care — Website README

## Overview
This is the static website for **Unseen Care**, a premium cleaning business serving NDIS, residential, and commercial clients in Sydney, Australia.

The site is hosted on **Netlify** via the domain **unseencare.com.au**.

---

## How to Make Changes

1. Describe what you want changed to Claude (e.g. "update the phone number", "add a new service", "change the hero text")
2. Claude will produce updated files
3. Download the files
4. Go to [Netlify](https://app.netlify.com) → Your Site → **Deploys**
5. Drag and drop the updated folder into the deploy area
6. Site updates live within seconds

---

## Hosting Details

| Setting | Value |
|---|---|
| Host | Netlify |
| Domain | unseencare.com.au |
| DNS Provider | Registry.com.au |
| A Record | 75.2.60.5 |
| Netlify Load Balancer | apex-loadbalancer.netlify.com |

### DNS Records (Registry.com.au)
| Type | Host | Value |
|---|---|---|
| A | @ | 75.2.60.5 |
| CNAME | www | [your-site].netlify.app |

---

## File Structure

```
unseencare/
│
├── index.html        ← Main homepage (entry point)
├── style.css         ← All site styles
├── script.js         ← Any interactivity
└── assets/
    └── images/       ← Logo, photos, icons
```

---

## Important Notes

- **index.html** must always exist at the root — this is what Netlify serves when someone visits unseencare.com.au
- Always upload the **entire folder**, not just individual files, to avoid breaking anything
- Test changes in an **incognito window** after deploying to avoid cached old version
- SSL certificate is auto-managed by Netlify via Let's Encrypt — do not touch

---

## Contact & Access

| Resource | Link |
|---|---|
| Netlify Dashboard | https://app.netlify.com |
| Domain Manager | https://manage.registry.com.au |
| DNS Checker | https://whatsmydns.net |

---

## Working with Claude

When asking Claude to update the site, provide:
- The **current files** (paste the HTML or attach the file) so Claude has context
- A clear description of **what to change**
- Any **brand preferences** (colours, tone, wording)

Claude will return updated files ready to deploy.
