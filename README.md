# The Comeback — GitHub Pages edition

A 26-week meal and bodyweight fitness planner. Plain HTML, CSS and JavaScript: no installation, build step, API keys or server required.

## Publish with GitHub Pages

1. Extract this ZIP on your computer.
2. Create a GitHub repository, for example `comeback`. GitHub Free requires a public repository for Pages.
3. Upload the extracted files directly to the repository root using **Add file → Upload files**, and commit to `main`. Do not upload the ZIP itself or put the files inside another folder. `index.html` must be visible at the top level alongside `style.css`, `plan.js` and `app.js`.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select **main** and **/ (root)**, then **Save**.
7. Wait for deployment, then use the **Visit site** link on the Pages settings screen. Publishing can take up to 10 minutes.

The included `.nojekyll` file disables Jekyll processing. It is safe to include it; the four website files also work with GitHub's default static processing.

Official setup guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## What is included

- `index.html`: layout, personal measurements and explanatory text.
- `style.css`: phone and desktop styling.
- `plan.js`: recipes, ingredient quantities, shopping totals and workouts.
- `app.js`: navigation, completion ticks, rest timer, start date and backups.
- `.nojekyll`: static hosting configuration.
- `.gitignore`: keeps progress backups and OS metadata out of Git commits.

Keep the four website files together. All asset links are relative, so this works under a repository subpath without changing URLs.

## Progress and backups

Progress is stored only in the current browser for this site's origin. It does not sync across devices. Moving from the original private planner to GitHub Pages does not automatically move your ticks.

To transfer progress: open **Start date & settings → Download backup** on the original planner. Open the GitHub Pages version, then **Start date & settings → Import backup**. Importing replaces the progress in that browser. Keep backup JSON files off GitHub.

Changing the start date keeps completion ticks attached to their week numbers. The default start is Monday 26 October 2026; choose any Monday in settings.

## Visibility

This standalone edition has no login or access control. Standard GitHub Pages hosting is public, even when the source repository is private. The page currently includes Gareth's first name, age, height and starting weight. Edit the HTML before publishing if you do not want those details visible. Progress ticks are browser-local and are not uploaded by this app.

## Editing

Change meals and workout data in `plan.js`, page text in `index.html`, and styling in `style.css`. Commit your changes to `main` to update the hosted site. No build command is needed.

The menu excludes fish, yoghurt, oats and tomatoes. Its approximately 2,300 kcal / 160 g protein daily starting aim varies with products and portions. Training progresses gradually and includes recovery weeks. The planner contains progression and safety guidance.
