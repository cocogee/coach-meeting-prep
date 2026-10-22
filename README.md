# Coach Meeting Prep

A one-page agenda builder for TE598 teams preparing for follow-up meetings with their coach.

- **Interactive tool:** https://cocogee.github.io/coach-meeting-prep/ fills in a short form and produces a one-page agenda to save as a PDF or paste into an email. Answers are saved in the browser.
- **Paper handout:** [coach-meeting-prep-handout.pdf](coach-meeting-prep-handout.pdf), the same agenda as a printable worksheet.

## The agenda

1. **Since our last meeting:** wins, setbacks
2. **Where we want your help:** one problem to work through together, quick questions, asks
3. **Next steps:** what we'll do, who owns it, by when

## Files

- `index.html`: the interactive tool (single file, no build step)
- `handout.html`: source for the handout; regenerate the PDF with headless Chrome:
  `"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless --no-pdf-header-footer --print-to-pdf=coach-meeting-prep-handout.pdf handout.html`
