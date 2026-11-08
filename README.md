# Frictions

The GitHub Pages site for the Frictions 2027 Symposium, built with Jekyll.

The symposium takes place Monday–Friday, 1–5 March 2027. The schedule is a
preview: session times and event details are placeholders.
Edit the files in `_events/` to update the programme. Each event's front matter
sets its title, category, day, display time, calendar slot and length (in hours).
Slots start at 1 for 09:00; the calendar runs from 09:00 to 17:00. Add a
`speaker` and `participants` in the front matter and an abstract in the file
body when available. Replace the conference abstract on the home page when it
is ready. Add approved supporter logos to the home page when available.

The call pages are placeholders; edit the files under `calls/` when the call
details are ready. The landing-page background can be changed using the
`--hero-background` CSS variable; the previous green is `var(--accent)`.

To preview the site locally, install Jekyll and run `jekyll serve` from the
repository root. GitHub Pages builds the site from the repository.