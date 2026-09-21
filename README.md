# PR Practice (Class 2, pairs)

You'll each make a change on a branch, open a pull request, review your
partner's PR, and merge. Ten minutes, both directions.

## Setup (Partner A only, ~2 min)

1. Click **Use this template** → create the repo under YOUR account (public).
2. Repo → Settings → Collaborators → **Add people** → invite Partner B.
3. Partner B: accept the invite (check email), then clone the new repo.
   Partner A: clone it too.

## The exercise (both partners, at the same time)

Each of you owns one section of `about_us.md`. Fill in YOURS only:

1. `git checkout -b add-<yourname>`
2. Edit your section of `about_us.md` (name + one sentence + favorite tool so far)
3. `git add about_us.md` → `git commit -m "add <yourname>"` → `git push -u origin add-<yourname>`
4. On GitHub: **Compare & pull request** → write one sentence describing the change → Create PR
5. **Review your partner's PR** (Files changed tab):
   - Leave one comment on a line
   - Click **Request changes** with a small, real ask (fix a typo, add a word)
   - Partner: make the fix on the same branch, commit, push — watch the PR update
   - **Approve**, then **Merge**
6. Both: `git checkout main` → `git pull` — you now have each other's work

## Done when

`about_us.md` on main has both sections filled in, and the repo shows two
merged PRs — one authored by each of you, one reviewed by each of you.

This is the exact loop your team repo homework requires this week
(one merged PR per member), and the loop your team uses all semester.
