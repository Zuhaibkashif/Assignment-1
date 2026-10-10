# Verification record — updated October 9, 2026

## Checks actually performed
- Parsed all four HTML files locally: one h1 each, header/nav/main/footer present, four navigation links each.
- Verified local href/src references resolve, including the supplied personal introduction video.
- Confirmed no Flexbox declarations in the three stylesheets.
- Reviewed markup for labels, native constraint attributes, viewport metadata, responsive image sizing, skip link and current-page navigation.
- October 9: verified unique IDs and matching field labels; tested phone pattern examples locally. 39 local references resolve.

These checks passed. They are not W3C validation or a WAVE report.

## Browser check limitation
An automated browser check was attempted, but no Chromium executable was available. Responsive rendering, keyboard behaviour, native form errors, mail-client handoff and visual appearance remain unverified in a browser. A browser installation retry on October 9 failed to download a usable executable. No screenshot or browser pass is claimed.

## Required before submission
Record date, page/file, result, fixes and evidence for each check below. Keep genuine evidence in a testing-evidence folder after performing the checks.

| Check | How to perform | Current status |
| --- | --- | --- |
| HTML | Upload each HTML file to https://validator.w3.org/; fix errors and recheck | Pending |
| CSS | Upload each stylesheet to https://jigsaw.w3.org/css-validator/ | Pending |
| Links | Run https://validator.w3.org/checklink on the live GitHub Pages URL | Pending deployment |
| Spelling | Review every visible paragraph and run an editor spell checker | Manual review done; tool check pending |
| Accessibility | Run https://wave.webaim.org/ on each live page and investigate all findings | Pending deployment |
| Responsive | Inspect all pages at 390px, 768px and 1366px; ensure no clipping/horizontal scroll | Pending browser |
| Keyboard | Tab through links/form, activate skip link, verify visible focus | Pending browser |
| Contact | Empty fields rejected; bad email rejected; invalid phone characters rejected; valid data opens mail app | Pending browser |
| Personal media | Own photo loads, video plays for 45–60 seconds, controls and poster work | Media added; browser playback pending |
| Deployment | Open public repository and live pages signed out; check every navigation link | Pending GitHub |

## Known limitations
The package is a learning draft. Email, photo, video poster and a 50-second introduction video have been added; project summaries need confirmation. The form uses mailto and has no server delivery. Phone validation requires 10–15 digits with an optional leading plus; it does not verify the number exists. No public repository or deployment exists from this workflow. External-service validation is not claimed. See README for authorship and the assignment's outside-code limit.

Video metadata check: supplied MP4 is 50.00 seconds, H.264/AAC, 852 × 480. All HTML local file references now resolve. Browser playback and speech content remain unverified.
