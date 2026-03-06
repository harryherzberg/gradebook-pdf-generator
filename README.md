# Gradebook PDF Generator MVP

A single HTML file that generates PDF report cards from a CSV gradebook.

## Features
- Upload CSV: `student_id,name,subject1,grade1,subject2,grade2,...`
- Parses dynamic subjects & grades
- Computes average grade & pass/fail (avg &gt; 60%)
- Generates beautiful PDF report cards per student with teacher comment
- Download individual PDF or ZIP of all
- Free trial: up to 5 students
- Pro: Unlimited for $19 (Gumroad link in app)

## How to Run
1. Download `index.html` (and `sample.csv` for testing)
2. Open `index.html` in any modern browser (Chrome/Firefox/Safari)
3. Upload your CSV
4. Click Parse CSV
5. Download singles or ZIP all!

No install, no server needed. Pure client-side.

## CSV Format
```
student_id,name,subject1,grade1,subject2,grade2,...
001,John Doe,Math,85,English,90,Science,78
```
- Header row optional (auto-skips if second column = 'name')
- student_id optional
- Pairs: subject,grade after name

## Pro Version
$19 one-time → Unlimited students  
[Buy on Gumroad](https://gumroad.com/l/gradebook-pdf-pro)

## GitHub
Coming soon: https://github.com/clawd-ai/gradebook-pdf-generator

## License
MIT for personal use. Commercial: Pro license required.