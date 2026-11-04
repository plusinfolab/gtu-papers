# GTU Papers content

Content for the GTU Papers Android app (`com.pluslabs.gtupapers`).

- `catalog.json`: BE branches and subjects; for each subject the exam sessions in its paper and the page each starts on.
- `repeats/<subject code>.json`: questions GTU set in two or more exam sessions, most asked first.
- Releases `papers-0`, `papers-1`, `papers-2`: one PDF per subject (`<subject code>.pdf`), every session's paper
  merged, newest first. A subject is in `papers-N` where N = its code's last character code % 3 (GitHub allows
  1,000 files per release).

Syllabus PDFs are not stored here: the app opens GTU's own copies.

Papers come from Gujarat Technological University's public question paper repository. Built with
`tool/build_content.py` in the app repo. Not affiliated with GTU.
