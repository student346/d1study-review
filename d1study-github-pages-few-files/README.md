# D1STUDY — GitHub Pages Ready Package (Few Files Version)

GitHub web upload-এ “Yowza, that’s a lot of files. Try uploading fewer than 100 at a time.” error এড়ানোর জন্য এই package বানানো হয়েছে।

## কী আছে

- `index.html` — মূল website
- `assets/img-data-01.js` থেকে `assets/img-data-09.js` — image data chunks
- `.nojekyll` — GitHub Pages static serve support

## Image size/quality

Image গুলো **resize/compress করা হয়নি**। আগের embedded base64 image data 그대로 রাখা হয়েছে, শুধু এক বড় HTML file থেকে কয়েকটি JS chunk file-এ ভাগ করা হয়েছে। তাই image dimensions/quality একই থাকবে।

## GitHub-এ Upload

1. `D1STUDY_GitHub_Pages_Ready_FEW_FILES.zip` extract করুন।
2. Extract করা folder-এর ভিতরের সব files/folder একসাথে drag করুন GitHub upload page-এ।
3. মোট file সংখ্যা 100-এর অনেক কম, তাই “Yowza” error আসার কথা না।
4. Commit করুন।
5. Repository → Settings → Pages → Deploy from a branch → `main` / `/root` → Save।

> ZIP file সরাসরি repository-তে upload করবেন না। ZIP extract করে ভিতরের files upload করবেন।
