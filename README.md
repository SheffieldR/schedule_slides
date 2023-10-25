# SheffieldR Schedule Slides

This is a [RevealJS](https://revealjs.com/) website that has been written in [Quarto](https://www.quarto.org). It
includes a [GitHub Action](https://docs.github.com/en/actions) which will convert the Quarto source to HTML and publish
them via [GitHub Pages](https://pages.github.com/). The resulting page can be visited at
[SheffieldR.github.io/schedule_slides](https://SheffieldR.github.io/schedule_slides).

## Usage

1. Clone the repository and for a forthcoming meeting create a branch with the date `YYYY-MM-DD`.
2. Edit the YAML header to link to the website page detailing the meeting.
3. Edit the first slide of `index.qmd` with the header `## SheffieldR Users YYYY-MM-DD` to reflect the date and schedule
   of events.
3. Commit the changes, push to GitHub and open a [pull request](https://github.com/SheffieldR/schedule_slides/pulls).
4. Once approved the changes will be merged and you should have a slide at
   [SheffieldR.github.io/schedule_slides](https://SheffieldR.github.io/schedule_slides) which can be displayed at the
   start.
