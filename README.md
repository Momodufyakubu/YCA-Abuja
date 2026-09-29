# Yazz Communication Academy — GitHub Pages V6 Production

## GitHub Pages upload structure

Upload the **contents of this folder** to the root of your GitHub repository — not the ZIP file itself.

The most important directory is:

```text
programmes/
└── index.html
```

This makes the following URL work on GitHub Pages:

**https://yca-abuja.com/programmes/**

The eight SEO programme URLs are also real directory pages:

- /programmes/computer-literacy/
- /programmes/data-analysis-python/
- /programmes/web-development/
- /programmes/software-engineering/
- /programmes/cybersecurity/
- /programmes/processing-java-python/
- /programmes/design-animation/
- /programmes/corporate-training/

Other SEO landing pages remain intact.

## Important for phone uploads

If GitHub's mobile upload screen only lets you select files, do **not** upload only the HTML files from the root. The `programmes` folder and all of its subfolders must also be present in the repository.

If your phone cannot upload folders, extract this ZIP on your phone with a file manager that supports ZIP extraction, then use GitHub's web upload/file creation workflow or a Git client that preserves the directory structure.

## Custom domain

The root `CNAME` file contains only:

yca-abuja.com

Keep that file in the repository root.
