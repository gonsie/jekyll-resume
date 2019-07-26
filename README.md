# Jekyll Resume

This resume is a reimplementation of  [gonsie/cthulu-resume](https://github.com/gonsie/cthulu-resume) for Jekyll.

## Usage

Install the following 2 files into an existing Jekyll project.

- `resume.md`: Markdown resume. See details below for formatting.
- `_layouts/resume.html`: This file includes CSS styles for the resume.

## Resume Markup

This resume assumes the following markdown / html:

- Name at the top is a top-level heading (`#` / `<h1>`)
- The objective statement is a block quote (`>` / `<blockquote>`)
- Sections of the resume should 2nd level headings (`##` / `<h2>`)
- Job titles should be 3rd level headings (`###` / `<h3>`), which can be combined with bold text (`**` / `<bold>`).
- Dates can be added to 3rd level headings by directly using the html `<span>` tag.
