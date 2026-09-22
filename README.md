Generative AI Declaration & Reflection

1. Tools Used
- GitHub Copilot / ChatGPT: Used as a coding assistant for code completion, DOM syntax lookup, and CSS layout structuring in `T01(a)`.
- KNIME K-AI (Optional): Used for node recommendations during data cleaning in `T01(b)`.

2. Specific Applications & Workflow Integration
- JavaScript Navigation (`js/nav.js`): Generated initial boilerplate for `document.addEventListener("DOMContentLoaded")` and the `window.location.pathname` string manipulation to detect the current HTML page.
- CSS Styling (`css/style.css`): Suggested CSS root custom variables (`:root`) and hover transition effects matching the power logo color palette.
- HTML Footer Integration:** Assisted in formatting the global footer template across `index.html`, `televisions.html`, and `about.html`.

3. Manual Adjustments & Code Verification
- Path Detection Correction: The initial AI-generated script for active link highlighting failed on root URLs (e.g., `/`). I manually modified the code to default to `index.html` when `pathname` returned empty or `/`.
- Removal of Excessive Comments: Trimmed redundant AI-generated inline comments to ensure clean code readability and avoid over-reliance on comments during live demonstrations.
- Cross-Browser & Deployment Testing: Tested all JS functions locally in Visual Studio Code and verified active page styling on the live Vercel deployment.

4. Critical Reflection & Academic Integrity
- Learning Impact: Using Generative AI accelerated boilerplate code generation, allowing more time to focus on responsive layout design and data transformation logic.
- Verification & Code Mastery:** Every line of generated JavaScript and CSS was systematically reviewed and tested. I possess a complete understanding of the underlying logic and am fully prepared to explain or modify any part of the codebase during tutor oral evaluations without referring to inline comments.
