# HS World History: Enlightenment to Present (Spring) -- Lesson Pages

GitHub Pages-hosted lesson, primary-source, module-map, capstone, syllabus, and
teacher-facing pages for Optima Academy Online's HS World History: Enlightenment to
Present (Mississippi standards), Spring semester, iframed into Canvas.

## Structure

- `modules/m11/` onward -- one folder per module (Spring numbering continues from
  Fall's Module 10). Each holds that module's lessons, primary sources, module
  map, and capstone reading page, named by their `{module}.{order}` ordinal.
- `frontmatter/`, `downloads/` -- syllabus and teacher-facing pages (not yet authored).

Reading quizzes, Critical Questions, Primary Source Exercises, VR Activities,
module discussions, quarterly exams, and the semester final are Canvas-native
objects (per `CLAUDE.md`'s deployment split) and are not hosted in this repo.

Source of truth: `03_Build/week-NN/*.md` in the course folder, rendered through
`03_Build/md_reader.py`. Never hand-edit the generated HTML in this repo --
change the source and redeploy.
