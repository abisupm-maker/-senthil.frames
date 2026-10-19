SENTHIL.FRAMES — Vercel-ready static website

FILES
- index.html: main portfolio homepage (Vercel default entry file)
- works.html: separate manually editable work-list page
- senthil-portrait.jpg: portrait asset referenced by the homepage

DEPLOY WITH GITHUB + VERCEL
1. Extract this ZIP.
2. Upload these files to the ROOT of the GitHub repository connected to Vercel.
3. In Vercel > Project Settings > Build and Deployment, use Framework Preset: Other.
4. If files are in the repository root, leave Root Directory as ./ and use no build command.
5. Make sure the output directory setting does not point to a folder that does not exist. For a simple static HTML repo, deploy the root files; if your project requires an Output Directory field, set it to the directory containing index.html.
6. Commit/push and redeploy. Test / and /works.html.

IMPORTANT
The work list uses browser localStorage. Items added on the manager page are saved only in that browser/device and do not automatically appear for other website visitors. The Export button saves a JSON backup; a shared database or updating the published page/data is needed for globally shared work entries.
