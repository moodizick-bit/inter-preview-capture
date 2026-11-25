# How to tear this down

Do not delete until Roi has checked the preview on his phone.

1. Delete this GitHub repository:
   `gh repo delete moodizick-bit/inter-preview-capture --yes`
   (or GitHub → the repo → Settings → Delete this repository)
2. Delete the local copies on the box, if they are still there:
   `rm -rf /workspace/inter_preview_capture /workspace/inter_preview_pages`
3. Do not touch: the live Inter site, branch `main`, PR #30 (`task33-capture-frame`), the production database, Railway projects `rare-perfection` or `inter-task01-staging`, or the secret `inter_2026_11`.
