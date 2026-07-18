You are an expert in academic poster design, UI/UX design, and research communication.

Your task is to create a professional graduation thesis poster from the materials I provide.

I will provide:
1. A complete graduation thesis report.
2. A sample poster that should ONLY be used as a reference for layout, visual style, typography, spacing, color palette, and overall organization.

## IMPORTANT

- The final poster MUST be written entirely in Vietnamese.
- Do NOT use English in the poster content.
- The thesis report is the ONLY source of truth for all content.
- The sample poster is ONLY for design inspiration. Never copy its text or structure exactly.
- Do NOT invent or hallucinate any information that does not exist in the report.

## Your responsibilities

- Read and understand the entire thesis report.
- Identify the core problem, objectives, methodology, proposed system, experiments, contributions, conclusions, and any other important information.
- Decide which sections should appear on the poster based on the report.
- Extract only the most important information.
- Rewrite everything into concise, academic, and poster-friendly Vietnamese.
- Remove unnecessary details, repetitive explanations, and lengthy paragraphs.
- Organize the poster into a logical flow suitable for a 5–10 minute graduation thesis defense.

For every section:
- Decide what should be included.
- Decide what should be omitted.
- Determine which figures, diagrams, screenshots, charts, or tables from the report should be displayed.
- Clearly indicate where each visual element should be placed.

## Design Requirements

Design the poster as if it were for an academic conference.

The poster should:
- Look modern, clean, and professional.
- Have strong visual hierarchy.
- Be easy to read from a distance.
- Balance text and visuals.
- Use cards, icons, separators, and whitespace appropriately.
- Highlight the most important contributions.
- Make important numbers and results stand out.
- Follow current UI/UX best practices.
- Be suitable for high-quality A0 printing.

## HTML Requirements

Generate the poster as a SINGLE self-contained HTML file.

Requirements:

- Everything must be contained inside one HTML file.
- Embed CSS inside a <style> tag.
- Embed JavaScript inside a <script> tag.
- Do NOT create additional files.
- The HTML must be ready to open directly in any modern browser.

Use:

- Tailwind CSS via CDN
- Lucide Icons via CDN
- html2pdf.js via CDN

Do not require any build tools or installation.

## PDF Export

Add a floating button in the top-right corner:

"Tải xuống PDF"

When clicked:

- Export the poster as a high-quality PDF.
- Prefer using html2pdf.js.
- If html2pdf.js cannot be loaded, gracefully fall back to window.print().

The exported PDF must be suitable for professional A0 printing.

## Print CSS

Include print styles:

- @page { size: A0 portrait; margin: 0; }
- Hide the download button while printing.
- Preserve background colors when printing.
- Preserve typography.
- Avoid breaking sections across pages.
- Ensure layouts remain aligned after export.

## Responsive Behavior

The poster should:

- Display correctly in desktop browsers.
- Scale proportionally on smaller screens.
- Always maintain the A0 layout when exported to PDF.

## Images

Whenever the report contains:

- Architecture diagrams
- Workflow diagrams
- System flowcharts
- UI screenshots
- Charts
- Tables

Reserve appropriate placeholders and indicate clearly where each image should be inserted.

Example:

[Đặt Hình 3.2 - Kiến trúc hệ thống]

or

[Đặt biểu đồ đánh giá thực nghiệm]

Do not recreate figures unless explicitly requested.

## Writing Style

Use formal academic Vietnamese.

Content should be concise.

Each section should contain only essential information.

Prefer bullet points over long paragraphs.

Avoid repeating information.

Focus on readability.

## Final Output

Return ONLY the complete HTML source code.

Do not include explanations.

Do not wrap the HTML inside Markdown code blocks.

The generated HTML should be production-ready and require minimal manual editing before printing or presenting.