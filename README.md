# Frictions

The GitHub Pages site for the Frictions 2027 Symposium, built with Jekyll.

The symposium takes place Monday–Friday, 1–5 March 2027. The schedule is a
preview: session times and event details are placeholders.
Edit the files in `_events/` to update the programme. Each event's front matter
sets its title, category, day, display time, calendar slot and length (in hours),
venue (with an optional `map_url` Google Maps link, shown as a 📍 pin), session organizer, speakers, participants and respondents. Enter people
as YAML lists; empty fields are hidden on the event page. For example `speakers: [Name One, Name Two]`. Write the abstract
in the Markdown body below the front matter. The event detail page renders these
fields from the same file. Set `slot` to the event's start hour in 24-hour time
(for example, `9` for 09:00 or `13` for 13:00 / 1 p.m.). The calendar shows
10:00–19:00, so events are clipped to those visible hours. `length` is the event's
duration in hours. Replace the conference abstract on the home page when it is
ready. Add approved supporter logos to the home page when available.

The call pages are placeholders; edit the files under `calls/` when the call
details are ready. The landing-page background can be changed using the
`--hero-background` CSS variable; the previous green is `var(--accent)`.

To preview the site locally, install Jekyll and run `jekyll serve` from the
repository root. GitHub Pages builds the site from the repository.
