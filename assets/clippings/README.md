# Original magazine clipping images

This folder is where licensed or otherwise authorized original Popular Mechanics page scans are stored for display inside the scrapbook.

**Important:** This repository and its GitHub Pages site are public. Do not upload copyrighted magazine page scans unless their reproduction/public distribution is authorized or a qualified public-domain exception applies. Having purchased a magazine or being able to view its pages on Google Books does not by itself authorize republishing scans.

## Upload workflow

1. Obtain permission or confirm a valid reproduction license for the intended pages. Keep a record of that authorization.
2. Prepare one image per page as **JPEG, PNG, or WEBP**, preferably readable at 1200–1800 pixels wide and optimized for the web. Don't crop away article credit or printed page numbers unless approved.
3. Upload the file(s) here in GitHub using **Add file → Upload files**.
4. In the root `projects.json`, find the project by `id` and list the images in reading order:

```json
"sourceImages": [
  "assets/clippings/PM-1978-OCT-65-01.jpg",
  "assets/clippings/PM-1978-OCT-65-02.jpg"
],
"imageRights": {
  "status": "cleared",
  "basis": "Written permission from rights holder, dated YYYY-MM-DD",
  "attribution": "Popular Mechanics / licensed source"
}
```

The sample paths above are **illustrative only**, not actual images present in this folder. Do not set `status` to `cleared` until you have documentation. For other projects, use their ID and sequential page numbers.

5. Commit the project catalog update. The scrapbook automatically displays the images as the original clipped pages, in order, upon the next GitHub Pages deployment. Each modern engineering note stays separate on the facing page.

Without approved images, the website intentionally shows the magazine's cover as a source reference and a link to the Google Books article, instead of leaving a broken or blank viewer.

## Notes

- The `sourceImages` field supports multiple page images per project.
- Original page images are **not** generated, reformatted as if original, or reconstructed by OpenAI.
- If the original is supplied as a PDF with proper rights, convert the authorized pages to web images for best inline results before updating `projects.json`.
