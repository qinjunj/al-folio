# Migration notes

Migrated from `qinjunj/qinjunj.github.io` at commit `f699e6d`.

- Preserved biography, research interests, profile photo, email, GitHub, LinkedIn, and Google Scholar links.
- Preserved the complete CV text, including all education, four publications, four talks, teaching, awards, skills, and the request to email for a PDF. Dates and status wording were not updated.
- Added all four CV publications to al-folio’s BibTeX bibliography. The three newer entries retain the abbreviated author names from the original CV; the 2023 entry uses the existing complete BibTeX citation. No new metadata was guessed.
- Retained the real publication/teaching legacy routes and all original `images/` and `files/` assets.
- Removed demo content, sample CV download, example news/projects/blog posts, external example feeds, and upstream maintenance workflows.
- Uses published al-folio runtime packages. No layout, Sass, or JavaScript overrides. The dependency set is reduced to the features used by this site and uses Ruby 3.3 or newer.
- The Markdown CV intentionally preserves the original content exactly. Structured CV data is also included as a foundation for a later switch to the native CV layout.
