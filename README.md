# Okeke Samson Michael — Premium Portfolio

UX Pilot-inspired, responsive static HTML/CSS/JavaScript website with 12 project case-study pages. No build step required.

## Preview locally

Extract the ZIP. Double-click `index.html` or run `python -m http.server 8000` from the extracted folder and visit http://localhost:8000. Keep all files and folders together.

## Deploy to Vercel

Upload the extracted folder to a GitHub repository, import the repository into Vercel, choose Framework Preset **Other**, leave Build Command empty, and deploy. Or use Vercel CLI `vercel --prod`.

## Before publishing

1. Open `config.js` and enter your real email, GitHub, LinkedIn, resume URL, and optionally a working form endpoint (such as Formspree). Missing links are deliberately disabled.
2. Replace `assets/portrait.png` with an original high-resolution photo if desired.
3. Add actual GitHub repositories, live demos, project datasets, evaluation metrics, screenshots and results to the project pages.
4. Verify certification titles and experience before publishing.
5. Some additional projects are labeled concepts/prototypes until you confirm their implementation status.

## Files

- `index.html`: homepage
- `projects/*.html`: project case studies
- `styles.css`: responsive design system
- `script.js`: mobile menu, animations, filters, contact form
- `config.js`: links and contact integration
- `assets/portrait.png`: existing portfolio photograph

No invented professional statistics, employment dates, or model results are included.

## October 2026 revision
- Replaced the hero and About photographs with the original user-supplied `assets/my-pics.jpeg`.
- All twelve project detail-page hero images now reuse the exact representative photo URLs shown on the corresponding homepage cards. These are remotely hosted and require internet connectivity.
- Evaluation sections now include verified GitHub README results and labelled charts for available repositories, or honest evaluation status for projects without published figures. No fabricated metrics.
- The contact form uses FormSubmit AJAX, with spam honeypot and success/error feedback. **IMPORTANT: First verify ownership of okekesam01@gmail.com by following the activation link sent by FormSubmit after the first test submission.** The form is not guaranteed to deliver mail until verification. Test on the deployed HTTPS site and check inbox/spam. FormSubmit is a third-party provider; do not use this form for sensitive data.

## Latest requested changes (23 October 2026)
- ONLY the homepage hero framed image was changed to `assets/hero-working-at-computer.png`. The About portrait remains unchanged.
- All 12 case studies now have brief, tailored methodology descriptions. For concept projects, the text explicitly describes a proposed approach; other summaries describe suitable methods without inventing performance claims.
- Replaced decorative icons in existing homepage icon containers with standard vector line icons, preserving the design. Lucide-style SVGs follow the community icon design system: https://lucide.dev/license
- Replaced typographic em and en dashes in HTML content with standard punctuation.
- CV button now points to `assets/resume.pdf`. **To activate it**, copy your genuine PDF resume into the `assets` folder and rename it `resume.pdf`, then redeploy. A helpful notice appears if no resume has been supplied. The website cannot accept owner-only uploads securely without a login and backend.
- The contact form continues to require FormSubmit activation and a successful test before email delivery can be confirmed.
