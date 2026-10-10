# Zuhaib Kashif — Portfolio learning draft

INFR3120 Assignment 1, Fall 2026. Due October 9, 2026 at 11:59 p.m., per supplied PDF. The PDF totals 60 marks and requires GitHub Pages; Canvas's displayed category weights differ. Follow the instructor's current directions.



## Files
- `index.html`: home, navigation and focus areas.
- `about.html`: introduction, image and HTML5 video.
- `projects.html`: five coursework summaries to verify against actual work.
- `contact.html`: labelled contact fields and native HTML validation.
- `css/mobile.css`: shared styles and mobile layout.
- `css/tablet.css`: tablet overrides.
- `css/laptop.css`: laptop overrides.
- `assets/`: original generated SVG favicon and clearly labelled media placeholders.
- `PRESENTATION-GUIDE.md`: 18-minute explanation plan with demo cues.
- `TESTING.md`: actual local results and external checks still required.

## Required personal changes
1. Replace `your-email@example.com` everywhere with your actual contact email, including the contact form action. Do not publish personal information you do not want public.
2. Put your own photo in `assets/`, update the About image path and alt text, and remove the placeholder caption.
3. Record a 45–60 second introduction; save it as `assets/introduction.mp4`. The video markup already has `controls` and `poster`. Replace the poster text with a finished poster and add a transcript (and preferably captions). Remove the missing-video note only after playback works.
4. Confirm the five project descriptions, remove the draft notice, and use only projects you actually completed. Add real screenshots or links if available.
5. Complete the external validation checks and retain evidence.
6. Publish your own public repository with real incremental commits. No repository, commit history or live URL is included or claimed in this draft.

## Layout and viewport decisions
The base layout is fluid: `.wrap` uses 90% width with an 1180px maximum. Images, video and fields scale to available width. Mobile is below 600px, with a single reading column. Tablet begins at 600px and uses two-column CSS Grid where space permits. Laptop begins at 1024px with a three-card Home layout and two-column contact layout. The link `media` conditions and matching `@media` rules keep the separate stylesheet roles explicit. These thresholds provide readable space for content rather than targeting a particular phone brand. No Flexbox is used. Grid and inline-block provide layout; verify Grid is permitted by your instructor.

## Gradients and colour scheme
`mobile.css` gives `.page-heading` a straight `linear-gradient(to right, ...)` on About, Projects and Contact. `.video-section` on About uses `linear-gradient(135deg, ...)`, the angled gradient.

Palette: navy #142B3B (header, footer and main text), deep teal #075B60 (links and buttons), mint #9CE3DB (dark-background accents), pale mint #DFF1ED (heading areas), off-white #F5F7F8 (page background). This is a blue/green analogous-inspired palette with neutral backgrounds. Enter these colours in https://color.adobe.com/create/color-wheel and save a palette screenshot for rubric evidence; no Adobe palette creation is claimed here.

## Semantic HTML and accessibility
Every page has `header`, labelled `nav`, `main` and `footer`. Project and focus cards are `article` elements; the contact sidebar is `aside`; the photo has `figure` and `figcaption`. There is one h1 per page and logical h2/h3 headings. A keyboard skip link, focus outlines, descriptive navigation with `aria-current`, labelled fields and appropriate autocomplete tokens support accessibility. SVG placeholders are explicitly identified, not passed off as personal media.

## Contact validation and delivery
Name: required, 2–80 characters. Email: required, type=email, maximum 150 characters. Phone: required, pattern permits an optional leading plus followed by 10–15 digits. Spaces, parentheses and hyphens are rejected. This checks format, not whether the number exists. Comments: required, 10–2000 characters. Native browser validation runs without JavaScript. The static `mailto:` action depends on a configured email application and does not guarantee delivery; the visitor must send the generated draft. GitHub Pages does not execute a server form handler. If your instructor expects server receipt, clarify the approved handler before adding a service.

## Local preview
Open `index.html` directly, or from this folder run:

```sh
python3 -m http.server 8000
```

Visit http://localhost:8000 and navigate all pages. Stop with Ctrl+C.

## GitHub workflow (terminal commands)
Create an empty PUBLIC repository called `Assignment-1` in your own GitHub account. Do not initialise it with a remote README if using this sequence. Run in your own project folder after adapting the draft. Replace Zuhaibkashif in the remote URL.

```sh
git init
git branch -M main
git add index.html about.html projects.html contact.html assets

git commit -m "Create semantic portfolio pages and navigation"
git add css
git commit -m "Add responsive viewport styles and gradients"
git add README.md TESTING.md PRESENTATION-GUIDE.md
git commit -m "Document design and verification steps"
git remote add origin https://github.com/Zuhaibkashif/Assignment-1.git
git push -u origin main
```

These are commands to run as you actually develop your own implementation, not a substitute for genuine development history. Commit real edits at each major stage, including adding personal media and fixing validation findings. Do not fabricate dates or authors. The PDF's phrase 'Any code posted on GitHub other than commands' is ambiguous; ask the TA what it means. This draft includes terminal instructions but does not resolve that wording.

## GitHub Pages
In repository Settings → Pages, choose Deploy from a branch, branch `main`, folder `/ (root)`, then Save. Wait for successful deployment and open the URL displayed by GitHub. Normally the URL is `https://Zuhaibkashif.github.io/Assignment-1/`; this template is not a live link. Relative paths support the repository subdirectory. Verify navigation and media again from the live URL. Record your actual public repository URL and live URL in this README.

## Submission
After approved personal implementation and successful checks, ZIP the final project (exclude .git and temporary files). Submit that ZIP to Canvas, plus the real GitHub Pages URL, public repository URL and your own 15–20 minute code/deployment video. Webcam must stay on throughout that recording. Rehearse using PRESENTATION-GUIDE.md. The website's short introduction video is a separate requirement from the explanation video.

## Personalisation update — October 9
Contact email added: Zuhaib.kashif@ontariotechu.net. Outdoor photo and video poster supplied by Zuhaib. Repository supplied by Zuhaib: https://github.com/Zuhaibkashif/Assignment-1 . Expected Pages address: https://zuhaibkashif.github.io/Assignment-1/ (deployment not verified). The actual introduction.mp4 is still missing. Earlier checklist steps are instructions; the email, photo and poster steps are now complete.

## Video update
Zuhaib supplied intro.mp4, copied to assets/introduction.mp4. ffprobe reports 50.00 seconds, 852 × 480 pixels, H.264 video and AAC audio. Duration meets the 45–60 second requirement. Controls and a supplied poster are present. Playback and spoken content have not been verified in a browser; a transcript/captions remain to be added after reviewing the actual audio.
