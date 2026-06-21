# Reddit Marketing for B2B SaaS — Research

Status: not started yet. Planned as a future research project, same structure as my other two:
- [AI-Powered SEO Content Production](https://github.com/Nijenth/AI-powered-SEO-content-production-Research)
- [Newsletter / Email Marketing for B2B SaaS](https://github.com/Nijenth/Newsletter-email-marketing-for-B2B-SaaS)

## Why Reddit marketing

Reddit has an official, free Data API (PRAW for Python), which makes it one of the few topics on the original list where I can pull real source material through a legitimate API rather than relying only on YouTube transcripts or manual collection. That's the main reason I picked it as my next project.

## Planned approach

- Find 10 genuine practitioners (people who've actually run Reddit marketing/community campaigns for B2B SaaS, not just commentators)
- Use Reddit's official API to pull relevant public posts/comments from relevant subreddits and practitioner activity, respecting Reddit's terms and rate limits
- Pull YouTube/podcast transcripts the same way as my other two projects, using the free `youtube-transcript-api` library
- Same repo structure: `research/sources.md`, `research/youtube-transcripts/`, `research/other/`, `research/reddit-data/`
- Commit incrementally, not all at once

## Status

Just the plan so far. Will build this out properly when I have time.