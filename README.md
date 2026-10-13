# Waiting, by Design

An interactive guide to the psychology behind loading patterns.

Two screens can load in exactly the same time, yet one feels instant and the other feels broken. This page explores why, with live demos you can replay and compare.

## What's inside

- **The thresholds of patience**: feel the difference between 100ms, 400ms, 1s, 3s and 6s waits with no loading indicator.
- **Six loading patterns**, each with a live demo, the psychology behind it, and when to use or avoid it:
  1. Spinner (indeterminate)
  2. Progress bar, with four curves to compare (linear, speeds up, slows down, backward ripples)
  3. Skeleton screen
  4. Step-by-step status (the labor illusion)
  5. Optimistic UI, with simulated server failure and rollback
  6. Progressive loading (blur-up images)
- **The race**: four loading patterns that all finish at exactly 3 seconds. Vote on which felt fastest.
- **Six design principles** adapted from David Maister's *The Psychology of Waiting Lines*.

## Built with

Plain HTML, CSS and JavaScript in a single file. No frameworks, no build step.

- Light and dark themes (follows system preference, with a manual toggle)
- Respects `prefers-reduced-motion`
- Keyboard accessible, responsive down to phone width

## Run it

Open `index.html` in a browser, or view it live with GitHub Pages:

1. Go to **Settings → Pages** in this repo
2. Under **Source**, choose **Deploy from a branch**, select `main` and `/ (root)`
3. Your page will be live at `https://<your-username>.github.io/<repo-name>/`

## References

- Maister, D. H. (1985). *The Psychology of Waiting Lines.*
- Doherty, W. J. & Thadani, A. J. (1982). *The Economic Value of Rapid Response Time.* IBM.
- Nielsen, J. (1993). *Usability Engineering.*
- Myers, B. A. (1985). The importance of percent-done progress indicators. *CHI '85.*
- Harrison, C. et al. (2007). Rethinking the progress bar. *UIST '07.*
- Harrison, C., Yeo, Z. & Hudson, S. E. (2010). Faster progress bars. *CHI '10.*
- Buell, R. W. & Norton, M. I. (2011). The labor illusion. *Management Science.*
- Kahneman, D. et al. (1993). When more pain is preferred to less. *Psychological Science.*
