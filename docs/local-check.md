# Local check summary

- Theme: Xcode · Prism 0.1.1
- Manifest SHA-256: `30249e2ee837316aea81051680356308857781dc8124bffd67207b95dac86b51`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 14.74:1, title 14.74:1, link 5.57:1, tag 9.8:1, code 13.52:1, mark 13.01:1, chosen 13.43:1.
  - Dark: body 12.32:1, title 16.41:1, link 5.91:1, tag 6.78:1, code 8.57:1, mark 6.15:1, chosen 9.64:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
