# UNITED website

The public website for UNITED (*Using a National, Interdisciplinary Team to Enhance Drug and alcohol treatment data*), an NIHR Team Science Award project (NIHR306655).

The site is built by GitHub Pages using Jekyll. You don't need to install anything: edit files on github.com and the site rebuilds itself within a minute or two.

## Common tasks

### Add a new output

1. Open [`_data/outputs.yml`](_data/outputs.yml) and click the pencil icon (**Edit this file**).
2. Copy an existing entry (from `- type:` down to `status:`) and paste it at the top of the list.
3. Change the details. Put the web address in `link:` and set `status: available`.
4. Click **Commit changes**.

To announce something before it's out, add it with `status: coming-soon`. When it's published, add the `link:` and change the status to `available`.

### Add the recording, slides or sign-up form links

Open [`_config.yml`](_config.yml) and fill in `recording_url`, `slides_url` or `signup_form_url`. For OneDrive files, use a sharing link set to **Anyone with the link can view**, and test it in a private browser window first.

While `signup_form_url` is blank, the "Stay in touch" section shows the project email address instead.

### Update the team

Edit [`_data/team.yml`](_data/team.yml). Photos go in `assets/team/` as square images (around 320 × 320 pixels).

### Change the page text

All the page text is in [`index.html`](index.html). Each section is marked with a comment such as `<!-- ===== ABOUT ===== -->`.

## Files

| File | What it does |
| --- | --- |
| `_config.yml` | Site title, contact email, and links for the recording, slides and form |
| `_data/outputs.yml` | The list of outputs |
| `_data/team.yml` | Team members and partners |
| `index.html` | The page itself |
| `_layouts/default.html` | Header, footer and page frame |
| `assets/style.css` | Colours, fonts and layout |
