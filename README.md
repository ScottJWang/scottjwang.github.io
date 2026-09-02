# Scott Jinzhiyang Wang Personal Website

This is a static academic website for Scott Jinzhiyang Wang's accounting PhD rookie job market profile.

## Public Site Checklist

1. Review `index.html` and adjust paper descriptions as working abstracts become available.
2. Export the CV as a PDF and upload it at `assets/Scott_Jinzhiyang_Wang_CV.pdf`.
3. Replace `assets/profile-mark.svg` with a professional headshot when ready, or keep the current initials mark temporarily.
4. Add paper PDFs under `papers/` using the filenames listed below.
5. Add presentation videos or video embeds to each paper page when they are ready.
6. Create a GitHub repository named `<your-github-username>.github.io`.
7. Upload the public website files to the repository root.
8. In GitHub, open Settings > Pages and publish from the main branch.

## Manual GitHub Upload

Upload the website files only. Do not upload local zip archives, the local `.git` folder, or the Word version of the CV.

Recommended upload set:

- `index.html`
- `styles.css`
- `script.js`
- `README.md`
- `.gitignore`
- `assets/profile-mark.svg`
- `assets/Scott_Jinzhiyang_Wang_CV.pdf` after you export it
- paper PDFs and slides when they are ready

## Paper Pages

Each main paper has a dedicated reading page. Put PDFs at these paths:

- `papers/behind-closed-doors.pdf`
- `papers/audit-quality.pdf`
- `papers/knightian-uncertainty.pdf`
- `papers/pcaob-inspection-reports.pdf`
- `papers/climate-risk-green-innovation.pdf`

Each paper page also has a `Video` section. When a talk video is ready, replace the `Video coming soon` block in that paper's `.html` file with either:

```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" title="Paper video" allowfullscreen></iframe>
```

or:

```html
<video controls src="../videos/your-video-file.mp4"></video>
```

## Suggested Content for the Job Market

- A clear headline: name, accounting PhD candidate, university, rookie job market year.
- One concise research paragraph that states your field and research identity.
- Job market paper or selected working papers with status, coauthors, and paper links.
- Teaching experience.
- CV download link.
- Email, department, Google Scholar, LinkedIn, and GitHub links when available.

## File Structure

```text
.
|-- index.html
|-- styles.css
|-- script.js
|-- README.md
|-- .gitignore
|-- assets/
|   |-- profile-mark.svg
|   `-- Scott_Jinzhiyang_Wang_CV.pdf
|-- papers/
|   |-- behind-closed-doors.html
|   |-- behind-closed-doors.pdf
|   |-- audit-quality.html
|   |-- audit-quality.pdf
|   |-- knightian-uncertainty.html
|   |-- knightian-uncertainty.pdf
|   |-- pcaob-inspection-reports.html
|   |-- pcaob-inspection-reports.pdf
|   |-- climate-risk-green-innovation.html
|   `-- climate-risk-green-innovation.pdf
|-- slides/
|   `-- job-market-paper-slides.pdf
`-- videos/
    `-- your-video-file.mp4
```
