# Obsidian Recommended Setup

This is an implementation recipe, not a requirement of the 12 Week Year.

Use it if you want a simple markdown vault structure that works with links, history, and weekly review.

## Recommended Folder

```text
12WY/
  00-Start-Here.md
  Vision.md
  Cycle-Charter.md
  12W-Plan.md
  Model-Work-Week.md
  Commitment.md
  1-12W-Plan.md
  1-12W-Score.md
  past-weeks/
```

## Why `12W-Plan.md`, Not `00-12wy-plan.md`

Use:

```text
12W-Plan.md
```

Reason:

- It matches the concept: 12 Week Plan.
- It is semantic, short, and recognizable.
- `00-` should be reserved for overview or index files.

Use `00-Start-Here.md` for the entrypoint.

If you strongly prefer sorted numeric files, use:

```text
00-Start-Here.md
01-Vision.md
02-Cycle-Charter.md
03-12W-Plan.md
04-Model-Work-Week.md
05-Commitment.md
1-12W-Plan.md
1-12W-Score.md
```

But the default recommendation is semantic names.

## File Roles

| File | Role |
| --- | --- |
| `00-Start-Here.md` | index and current cycle links |
| `Vision.md` | canonical vision |
| `Cycle-Charter.md` | intentional imbalance, maintenance, parked work |
| `12W-Plan.md` | goals and tactics |
| `Model-Work-Week.md` | time-block template |
| `Commitment.md` | keystone actions and costs |
| `1-12W-Plan.md` | current weekly slice |
| `1-12W-Score.md` | current weekly scorecard |
| `past-weeks/` | history; do not delete |

## Weekly Rotation

At the start of week 2:

```text
Move 1-12W-Plan.md -> past-weeks/1-12W-Plan.md
Move 1-12W-Score.md -> past-weeks/1-12W-Score.md
Create 2-12W-Plan.md
Create 2-12W-Score.md
```

Keep the current week easy to find.

## Wikilinks

Wikilinks are useful but optional.

Recommended:

```text
[[Vision#Business]]
[[12W-Plan]]
[[1-12W-Plan]]
```

If you move this system outside Obsidian, replace wikilinks with relative markdown links.

## Print Anchors

Recommended printouts:

- Vision
- Weekly Plan
- Model Work Week
- Commitment

Keep editable truth in markdown. Use paper for attention and daily reconnection.
