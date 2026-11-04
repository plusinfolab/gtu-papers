# GTU Papers content

Content for the GTU Papers Android app (`com.pluslabs.gtupapers`).

- `catalog.json`: BE branches and subjects; for each subject the exam sessions in its paper and the page each starts on.
- Release `papers`: one PDF per subject (`<subject code>.pdf`), every session's paper merged, newest first.

Papers come from Gujarat Technological University's public question paper repository. Built with
`tool/build_content.py` in the app repo. Not affiliated with GTU.
