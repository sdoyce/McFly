# McFly Resources

This repository is a public collection for TrueType font (.ttf) files used for the McFly project.

Folder structure:
- fonts/ — place .ttf font files here. A `.gitkeep` file is included so Git keeps the empty folder.

How to upload fonts:
- Web: Go to https://github.com/sdoyce/McFly-Resources -> Add file -> Upload files and put `.ttf` files into the `fonts/` directory.
- Git:
  ```bash
  git clone https://github.com/sdoyce/McFly-Resources.git
  cd McFly-Resources
  cp /path/to/font.ttf fonts/
  git add fonts/font.ttf
  git commit -m 'Add font: font.ttf'
  git push
  ```

Notes:
- Git LFS is not enabled. If you plan to add files >100MB, enable Git LFS or configure it before pushing.
- Keep licenses for fonts; only upload fonts you have rights to redistribute.
