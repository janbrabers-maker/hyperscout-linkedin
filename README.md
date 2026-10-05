# Hyperscout LinkedIn studio

The LinkedIn tool for Jan Brabers and the Hyperscout page. One goal: get fashion brand owners and wholesale directors engaged with Hyperscout.

## What it does

- **Drafts and fixes posts** in Jan's blueprint, built from his own best posts of the past year.
- **Two-week post plan** every other Monday at 10:00: first asks Jan's goal and target group for the next two weeks, then proposes post concepts from LinkedIn and 30 fashion business sites (fashion wholesale, business development, fashion AI). After Jan approves, it writes the posts, makes an image or short video for each, and after a final yes per post schedules them on LinkedIn.
- **Voices to watch**: refreshed with the first radar of each month.
- **End-of-month review**: which posts by Jan and the Hyperscout page worked or flopped, fixes for drafts that repeat a poor pattern, and five new ideas from what worked.

Plans, posts and reviews land in the shared Claude Doc "LinkedIn Voices & Post Playbook". Jan gets a short message each time.

## Ask for something

Open this repository in Claude Code and ask, for example:

- "Draft a post on the Galeria insolvency for brand owners"
- "Fix this post: [paste]"
- "Start a new two-week post plan"
- "What worked this month?"
- "Turn radar topic 3 into a buyer's chair post"

## Set up

1. In Claude Code (desktop, web or phone), open `janbrabers-maker/hyperscout-linkedin`.
2. LinkedIn reading needs Claude in Chrome in your own Chrome. Drafting works without it.

Team members can be added later: invite them to this repository, share the playbook doc, and add them to the review in `references/review.md`.

## What is in here

- `.claude/skills/hyperscout-linkedin/SKILL.md`: the four jobs and the hard rules
- `references/blueprint.md`: Jan's voice, the four formats, benchmarks and checklist
- `references/voices.md`: who to watch and which searches to run
- `references/sources.md`: the 30 fashion business sites for the radar
- `references/review.md`: how the end-of-month review judges posts
- `CLAUDE.md`: standing instructions for Claude in this repository

No client data or private analytics exports are stored here.
