# Migration Notes

## Completed

- Converted the repository from generated static HTML output to Jekyll source.
- Configured the site for `https://minglics.github.io`.
- Added a GitHub Actions workflow to build and deploy the Jekyll site.
- Removed generated/cache folders from the migrated source:
  - `_site/`
  - `vendor/bundle/`
  - `.jekyll-cache/`
  - `.sass-cache/`
  - `.bundle/`
  - `.vs/`
  - `.DS_Store`
- Replaced old `ranger.uta.edu/~mingli` local asset links with site-local paths.
- Removed the unused 166 MB `videos/tile_based_vr_demo.mp4`, which exceeds GitHub's normal file size limit. The page references the smaller `videos/tile_based_vr_demo (2).mp4`.

## Still Needs Review

- `_pages/biography.md` had a placeholder CV link to `https://google.com`; no CV file was present in the uploaded website archive, so the link was removed.
- `_posts/publications/2023-1-02-SoundLock.md` referenced `/publications/SoundLock.pdf`, but that PDF was not present in the uploaded archive, so the PDF field was commented out.
- `_posts/publications/2022-11-01-SpeechQoE.md` referenced `/dataset/SpeechQoE/`; the dataset folder was not present in the uploaded archive, so the dataset field was commented out.
- The local build could not be verified on this Mac because the system Ruby environment cannot compile native gem dependencies. The GitHub Actions workflow uses Ruby 3.3 on Ubuntu, which should be the deployment build path.
