# Trail Docs Marketplace Example

This marketplace fixture contains a real-world plugin that combines the
AllTrails and Notion apps. It helps a hiker research a trail, compare options,
and turn the selected hike into a shareable Notion planning page.

## Example Prompt

> Find an easy-to-moderate AllTrails hike near San Francisco for this Saturday.
> Prefer a route under 6 miles with scenic views. Compare the top three options,
> recommend one, and create a Notion page for the selected trail with route
> details, a packing checklist, and a meetup plan.

## Plugin Contents

- `plugins/trail-docs/.app.json` declares the AllTrails and Notion app
  dependencies.
- `plugins/trail-docs/skills/trail-docs/SKILL.md` defines the trail-guide
  workflow.
