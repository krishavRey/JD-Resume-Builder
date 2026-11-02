# Resume Tailor

Free, open-source tool that rewrites your resume to match a job description and gives you an ATS-friendly Word file.

1. Paste the job description (left).
2. Upload your resume as PDF, DOCX or TXT (right).
3. Click **Generate**, review the result, then click **Download** to get a `.docx`.

## Bring your own key
The AI step needs an API key. Paste one into the app:
- **Free:** a Gemini key from https://aistudio.google.com (no card needed; free-tier limits apply and may change).
- **Claude:** a key from https://console.anthropic.com (billed to your own account).

The key is stored only in your browser (if you tick "Remember") and is sent only to Google or Anthropic.

## Privacy
There is no server. Your resume and job description go from your browser directly to the AI provider you chose. Nothing is stored or collected by this project. Note that Google states free-tier Gemini data may be used to improve its products; use a paid Gemini key or a Claude key if that is a concern.

## Honesty rule
The AI is told to use only facts from your original resume. Always review the output. Keywords your CV doesn't support are listed separately instead of being added.

## Limits
- Scanned (image-only) PDFs can't be read; use a text-based PDF or a DOCX.
- The output is a plain single-column format, not a designed template.

## Run it
Host the files with GitHub Pages, or open `index.html` through any static server. On a phone, open the site and use "Add to Home Screen" to install it as an app.

## License
MIT
