# Engineering Portfolio Website

A clean, responsive personal portfolio built for GitHub Pages.

## Files

- `index.html` — main website
- `style.css` — styling
- `script.js` — mobile menu and automatic copyright year
- `resume.pdf` — replace this placeholder with your actual résumé
- `images/` — put your project photos/screenshots here

## How to customize

### 1. Change your information

Open `index.html` and replace:

- Anthony Hernandez
- Baton Rouge, Louisiana
- Mechanical Engineering
- `your-email@example.com`
- LinkedIn link
- GitHub link
- project descriptions
- experience information
- skills

### 2. Add your résumé

Delete the placeholder `resume.pdf` and replace it with your actual résumé.

Keep the filename exactly:

`resume.pdf`

### 3. Add project images

Put your images inside the `images` folder.

Example:

`images/project1.jpg`

Then replace this:

```html
<div class="project-image placeholder">
  <span>Project Image</span>
</div>
```

with:

```html
<div class="project-image">
  <img src="images/project1.jpg" alt="Description of project">
</div>
```

You may also want to add this to `style.css`:

```css
.project-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```

## Publish with GitHub Pages

### Option A: Personal website

Create a repository named:

`YOURUSERNAME.github.io`

Upload all files from this folder directly into the repository.

Your website will appear at:

`https://YOURUSERNAME.github.io`

### Option B: Normal repository

If the repository is named something like:

`engineering-portfolio`

Go to:

Settings → Pages → Build and deployment

Choose:

- Source: Deploy from a branch
- Branch: main
- Folder: /root

Your website will usually appear at:

`https://YOURUSERNAME.github.io/engineering-portfolio/`

## Recommended project format

For each project, explain:

1. Problem
2. Goal
3. Your role
4. Design or analysis process
5. Tools/software
6. Challenges
7. Final result
8. What you learned

Engineering recruiters usually benefit more from seeing your process and results than a long paragraph of general description.
