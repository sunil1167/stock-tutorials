# Trading Study Course — GitHub Pages (offline-ready)

## Publish

1. Extract this ZIP and upload **the extracted contents** to the root of your GitHub repository (or its configured publishing folder).
2. Go to **Settings → Pages → Build and deployment** and choose **Deploy from a branch**, then select your branch and `/ (root)` or the matching configured folder.
3. Open the GitHub Pages URL. The home page automatically loads the root `index.html`.

## Structure

- `index.html` — full course home page
- `<original-lesson-file-name-without-.html>/index.html` — one folder per lesson (19 lessons, episodes 02–20)
- `course-nav.css` — shared course navigation CSS
- `.nojekyll` — serve files directly (no Jekyll processing)

Links are relative, so the site also works from a subpath like `username.github.io/repository-name/` and works offline when you open the extracted root `index.html`. Episode 01 was not included in the source ZIP and remains marked unavailable.

The HTML lessons' original content, CSS, JavaScript, charts and quizzes are not changed; only previously-added course navigation paths and the shared nav stylesheet path were updated.
