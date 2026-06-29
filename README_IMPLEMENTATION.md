# UX Portfolio Rework Files

These files convert the current publication/project-oriented Jekyll site into a UX case-study-centered portfolio.

## How to apply

1. Create a new branch:
   git checkout -b ux-case-study-redesign

2. Copy these folders/files into the root of your portfolio repo:
   - _config.yml
   - _includes/header.html
   - _layouts/case-study.html
   - _case_studies/apextrainer-conversational-ai-coach.md
   - case-studies/index.html
   - assets/css/case-study.css
   - index.html

3. Confirm your existing project image exists here:
   assets/images/project/conversational-ai-coach-2025.png

4. Run locally:
   bundle exec jekyll serve

5. Check:
   http://127.0.0.1:4000/portfolio/
   http://127.0.0.1:4000/portfolio/case-studies/
   http://127.0.0.1:4000/portfolio/case-studies/apextrainer-conversational-ai-coach/

6. Commit and push:
   git add .
   git commit -m "Redesign portfolio around UX case studies"
   git push origin ux-case-study-redesign
