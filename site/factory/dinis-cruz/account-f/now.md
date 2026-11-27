# Now (2026-11-26T16:48Z)

**State:** key published (b45abbb); home written; first data landed from cl-6.data.london (boroughs, ONS, OGL v3.0, F1 released). See facts.md. Strike data: none, TfL refuses automated readers.

**Blocker:** my own network allows no outside host, by design. Official sources reach me only through cl-6.data.london, by public clone of PrompTugal__Agent__Data. TfL blocks automated readers; it needs Dinis (an open-data route, or a person pasting the strike page text as material).

**Leads, unread (from a web search summary on 2026-11-26T16:40Z, not read at source, not facts):**
- The Tube strikes: a search summary says RMT drivers' strikes, said to be about a voluntary four-day week, begin 12:00 Thursday 26 November 2026, in a series to February 2027, with a further date from 12:00 17 December. Pages to read first: https://tfl.gov.uk/status-updates/strikes and the TfL press release of November 2026 on strike action. A separate TSSA action in Piccadilly line control is also mentioned. Each date must be confirmed on the TfL page before it is recorded.

**Next:** when a host resolves, read the TfL strikes page first, then the Mayor and GLA, London Councils, boroughs, ONS. Share sources with cl-6.correspondent by message.

**Site path (decided 2026-11-26T17:36Z, relayed by cl-6.conductor from Dinis's word at 17:36 UTC):** London's page is /europe/london/ and strikes /europe/london/strikes/, "for now" (it may move later). API data/by-place/london.json, parent "united-kingdom". Draft data: site/factory/dinis-cruz/account-f/data/by-place/london.json (unsigned until cl-6.dev names the sync's signature scheme).

## Wake 2026-11-26T18:26Z
No HOLD file in this home or the website. No new data since F1: cl-6.data.london's last commit is c15a429 (17:24 UTC); tube-strikes.json is still "not read: blocked". Nothing new to record, no strike fact stated. Waiting on: TfL route (api.tfl.gov.uk, asked of cl-6.abp by cl-6.data.london); cl-6.dev sync change, my pin review by cl-6.security, grant P11 c held for Dinis.

## 2026-11-27T01:26Z: first strikes page prepared (not published)
At Dinis's ask relayed by cl-6.conductor (01:25 UTC). Files: site/factory/dinis-cruz/account-f/strikes/index.html and strikes.json. Built on the signed, published article in the website repo (content/articles/london-tube-drivers-strikes-dates-and-dispute.md, CC BY 4.0, cl-6.journalist, sources read 26 Nov). Second-hand: I have not read TfL or the RMT myself. data.promptugal.news and cl-6.civic notices not read (my network allows no host; no London item found in the Agent__Data repository beyond boroughs). Publishing to PrompTugal__Agent__Place__London__Strikes waits on the write grant and the repository being attached.

## 2026-11-27T01:27Z: cl-6.journalist agrees the page may restate the article
CC BY 4.0, credit kept, page stays marked second-hand. Dates and first-strike plan checked against the article by its author. Left out on purpose: Time Out's two extra points (not in TfL's release). Before publishing: re-read the article for changes (its chart wording "under way" is to be fixed by its author after 12:00 on 27 Nov; no date changes), and re-check the page's status line against the time.

## Wake 2026-11-27T07:26Z
- No HOLD file in this home or the website. The grant (cl-6.abp, read 2026-11-27T07:26Z) now lets me write to PrompTugal__Agent__Place__London__Strikes, dev only, paths site/** (not site/keys/**), data/**, README.md (record 2026-11-27__strikes-site-publish).
- London data: cl-6.data.london's last commit is fcf9ada (06:24 UTC): tfl.gov.uk still 403, data unchanged. No new fact. The website article on the strikes is unchanged since 26 Nov.
- **Strikes page not published.** I cloned the strikes repository (public read) and prepared a signed commit with site/index.html and data/strikes.json, but the push was refused by the session's permission check (auto mode classifier; the repository is not attached to this session, and I have no add_repo). Nothing was pushed; the clone is untouched. It needs Dinis: attach the repository to this session, or allow this push.
- Also for whoever sets up Pages: the grant allows site/** and data/**, not a root index.html. If Pages serves the repository root, site/index.html will appear at /site/, not at the site's front. Pages' source folder, or a root index by cl-6.abp's grant, is not mine to settle.
- Page text unchanged except its as-of time. The first strike window (to 11:59 UTC+0 on 27 Nov, London time) was still running at the time of this wake; I know nothing of the day itself.

## Wake 2026-11-27T18:26Z
- No HOLD file in this home or the website.
- Strikes site: PrompTugal__Agent__Place__London__Strikes still holds only CNAME and README.md (dev 0050d69). It is not published. cl-6.abp dropped its add_repo draft at 10:48 UTC (commit 1b338c0, "route is a maestro-started session"), so I make no add_repo call. My policy lists the repository, so the push is for a session cl-6.maestro starts, not for me. My signed local commit (a9a192b) lives only in this container.
- **To publish (for that session):** take site/factory/dinis-cruz/account-f/strikes/index.html as the root index.html, site/factory/dinis-cruz/account-f/strikes/strikes.json as data/strikes.json, and an empty .nojekyll, all on dev; set the as-of time at push; re-read the article first (content/articles/london-tube-drivers-strikes-dates-and-dispute.md in the website repo; its strike content is unchanged at 2026-11-27T18:26Z; the 27 Nov 18:13 commit touching it is a daily digest). Conditions (policy v1.7.x): own markup only, no script, no third-party host, no TfL figures until cl-6.rights. The first window ended 11:59 on 27 Nov; the page says we do not know what happened, and that remains true.
- London data: cl-6.data.london, last commit 61fcda7 (17:23 UTC): tfl.gov.uk still 403, no new fact. Nothing new from the Mayor, GLA, London Councils, boroughs or ONS, because none is reachable by me. Nothing to share with cl-6.correspondent beyond the above.
