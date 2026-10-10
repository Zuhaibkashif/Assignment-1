# 18-minute presentation and demonstration guide

Keep your webcam on throughout. Record your own explanation of your final code and your actual deployment. This guide is a rehearsal plan, not a claim that a recording exists. Aim for 15–20 minutes; use a timer. Explain your own revised code accurately and disclose permitted assistance. Have the site, editor, repository and Pages settings ready before recording.

## 0:00–1:00 — Introduce the assignment
Suggested opening: “Hi, my name is Zuhaib Kashif. This is my portfolio for INFR3120. I'll explain the four HTML pages, how my styles adapt to different screens, the form validation, my testing, and how I deployed the site using GitHub Pages.”
Show all four pages and point out that they are separate files. State what you actually implemented and the purpose of the portfolio.

## 1:00–3:00 — Structure and navigation
Open index.html in your editor. Explain the doctype, lang, charset, viewport, page title and description. Show the three stylesheet links and their media conditions. Explain relative file paths using a navigation link. Point out header, nav, main, section, article and footer and why each is appropriate. Show the skip link and its target. Explain aria-current and demonstrate navigation in both directions. Show how the footer email becomes a mailto link.

## 3:00–4:30 — Home page
Explain the hero heading, focus cards and links to About and Projects. Show class attributes and find the corresponding selectors in mobile.css. Explain why one h1 represents the page's main subject and h2/h3 create a hierarchy. Show how the same stylesheet gives consistent visual appearance across four different documents.

## 4:30–6:30 — About page and media
Explain the personal introduction in your own words. Show your real photo, its src, meaningful alt text and width/height. Explain figure and figcaption. Play the actual 45–60 second recording (allow this time inside the presentation). Explain video controls, preload, poster, source and MIME type. Show any transcript/captions you added and how they help visitors. Describe the difference between this short embedded video and the assignment explanation recording.

## 6:30–8:00 — Projects
Show the five articles. For each, briefly explain what you actually did, the skill you learned, and any evidence you added. Explain why article is suitable for a self-contained project summary. Show headings and the two-column grid at larger sizes. Do not describe features or accomplishments you did not implement.

## 8:00–10:30 — Contact form
Explain form action, method and enctype. State that mailto opens an email application and requires the visitor to send the draft. Explain the absence of a server on a static GitHub Pages site. Show each label's for attribute matching the input id. Explain required, minlength, maxlength, type=email, type=tel, pattern, autocomplete and aria-describedby. Try submitting an empty form and a malformed email. Fill valid information and show the next step without emailing anyone during the demo. Explain the phone pattern: an optional leading plus and 10–15 digits, without separators. It validates format rather than verifying that the number exists. Explain textarea and why comments have minimum and maximum lengths.

## 10:30–13:30 — Responsive CSS and visual design
Open mobile.css, tablet.css and laptop.css. Explain the cascade and why base styles remain active at larger widths. Show box-sizing: border-box and discuss how padding/borders fit inside widths. Explain the 90% wrapper and 1180px maximum. Demonstrate 390px, 768px and 1366px widths in browser developer tools. Describe what changes at 600px and 1024px. Explain CSS Grid columns, minmax(0, 1fr), gap and inline-block navigation. State that no Flexbox is used. Show each gradient and explain to right versus 135deg. Explain the navy/teal/mint palette and show your Adobe palette evidence. Show hover and keyboard focus states.

## 13:30–15:30 — Testing and validation
Use your actual results and screenshots. Explain W3C HTML, CSS and link checks, spelling review and WAVE. Discuss any errors you found, the source changes used to fix them, and the retest outcome. Demonstrate keyboard tabbing and the skip link. Confirm personal media works on the published site. Do not claim passes for checks you have not performed. Explain why local checks complement but do not replace the named services.

## 15:30–17:30 — GitHub and deployment
Show the public repository and real incremental commits. Explain git add, commit, remote and push in your own words. Show Pages settings (main branch, root folder), successful deployment, and actual live URL. Navigate to About and Contact from the live version to demonstrate relative paths. Explain what you would do to publish a later fix: edit, test, commit, push and wait for deployment. Show that the repository is public by checking it while signed out.

## 17:30–18:00 — Finish
Show the final ZIP and identify the four submission items: ZIP, live site link, public repository link and webcam explanation video. Briefly describe one lesson learned and a realistic future improvement.

## Optional 45–60 second introduction script
“Hi, I'm Zuhaib Kashif, a cybersecurity student at Ontario Tech University. I'm interested in how networks connect people and how security keeps information safe. Through my coursework, I've been learning networking fundamentals, Python programming, and web development. Outside class, I work as a sales representative, which has helped me become more confident communicating and listening to different people. I also enjoy basketball and chess. Basketball teaches me teamwork, while chess encourages me to think ahead and solve problems. My goal is to build a career in networking or cybersecurity. This portfolio shares some of the work I'm learning from as I develop those skills. Thanks for visiting.”

Rehearse at a natural speed and time your recording; adjust to stay within 45–60 seconds. Correct any personal details that are no longer accurate.
