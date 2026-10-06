# BBJ / Bijo B James

Static responsive portfolio inspired by the sparse archive and drawing-first navigation of cochincreativecollective.com. Original BBJ page structure and copy; no reference biographies, awards or projects are claimed as Bijo's.

## Preview
Run `node serve.js` or `python -m http.server 8000` in this folder. Open http://localhost:8000. No build or dependencies required. HTML also works directly from disk.

## Pages
Home archive (drawing / pictorial / index views), Info, Bijo profile, Drawing as practice, Contact, eight project detail pages, Privacy, Project terms, and 404. Project pages include image enlargement, previous/next navigation and a drawing/image slider where paired images exist.

## Content to finish before public release
The eight drawing files are identical samples. Replace them with your own project assets and update each project page with titles, descriptions and credits. No fabricated location, qualification, awards or client claims have been added. The supplied about image remains a sample.

Set your real email in `content.js` (`profile.email`). The contact form then opens an addressed email draft. Without an email it downloads an enquiry text file and clearly reports that it has not sent anything. No server backend or analytics is included.

Edit the page HTML for copy and the central `style.css` for design. `content.js` records the project inventory and contact configuration. The archive and project detail content are populated from content.js. Add projects there; use project.html?id=YOUR-ID. Existing numbered HTML links remain supported. See EDITING-GUIDE.md.

## Deploy
Upload this folder to Netlify or Vercel. Host configurations preserve real file routes and missing-page responses. Confirm asset ownership, project credits and contact details before publishing.
