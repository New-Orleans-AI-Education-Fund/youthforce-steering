# YouthForce NOLA visit to Carver

A short prep site for the YouthForce NOLA Steering Committee's visit to G.W. Carver High School (Collegiate
Academies) on Wednesday, November 18, 2026. Kate asked the Fund for prep materials; the planning notes are in
Notion.

Live at https://YouthForce-Steering.vercel.app (web addresses ignore capitals).

- `index.html` is the whole site, with three pages: Welcome, About the Fund (the check-in site's About text and
  a link to the Year One Impact Report) and Coursemojo (what it is, Lamar's two videos, who uses it in New
  Orleans, the Collegiate quote and the CBS Evening News story).
- `images/` holds the photos and logos.
- Saving a change to `main` here puts it live within a minute (Vercel project `youthforce-steering`).

## Making changes

The words are in `index.html`, not Notion. Two ways to change them:

1. **On GitHub.** Open `index.html` in this repository, click the pencil (Edit this file), press Ctrl+F (Cmd+F on
   a Mac) to find the words, change them, then click **Commit changes** and **Commit changes** again in the box
   that opens. The site updates in about a minute; reload it to check. Change only the words between the tags,
   and leave anything inside `<` and `>` alone.
2. **With Claude.** Ask Claude Code to edit `index.html` in this repository and describe the change.

Every saved change is kept in the repository's history, so any change can be undone.

## Notes

The Coursemojo counts (17 schools, about 90 teachers, about 5,000 students, about 300 at Carver) are estimates
from the weekly usage data in "CourseMojo Trends", August to October 2026, all four networks including KIPP:
each school and grade counted at its busiest week, then summed.

The Vercel project was first called `carver-visit`, and carver-visit.vercel.app still reaches it. That address
was never shared and can be removed under the project's Settings, Domains in Vercel.
