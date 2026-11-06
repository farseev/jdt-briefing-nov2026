# JDT website proposal: SEO / AEO / GEO maintenance

Rebuild: `SITE_BASE=<base url> PREVIEW=0 python3 build.py <out>` (PREVIEW=1 adds the proposal banner and noindex).

## Keep identical in five places
The one-line definition must match in: meta description of the home JSON-LD Organization, `#answer-box`, `llms.txt`, `llms-full.txt`, and the suggested citation in `ai.txt`:

> Johor Darul Ta'zim FC (JDT), the Southern Tigers, is Johor's professional football club, playing at Sultan Ibrahim Stadium in Iskandar Puteri, Malaysia.

## Before going live on the club domain
- Serve from the domain root (e.g. johorsoutherntigers.my) so robots.txt, llms.txt and .well-known/security.txt are found at the host root.
- Set PREVIEW=0 (removes noindex and the proposal banner), submit sitemap.xml in Google Search Console and Bing Webmaster Tools.
- Replace generated images with licensed club photography and the real crest; add a named author per article.
- Re-check every fact and link against the club's own pages.

## Audit chain
- how-young-johor-players-reach-the-jdt-first-team: theme 'Youth & local talent' (PARTIAL), TOUCHIGH study 11893, news https://www.nst.com.my/amp/sports/football/2026/08/1520540/jdts-youth-pipeline-keeps-producing-champions
- family-matchday-guide-sultan-ibrahim-stadium: theme 'Local culture & traditions' (OPEN (creators MED)), TOUCHIGH study 11893, news https://www.bernama.com/en/news.php?id=2399941
- jdt-matchday-checklist-tickets-gates-kick-off: theme 'Match awareness & real-time info' (PARTIAL), TOUCHIGH study 11893, news https://theiskandarian.com/?p=30481
