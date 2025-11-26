GITHUB PAGES DEPLOY INSTRUCTIONS
1. Create a new GitHub repository (public).
2. Upload BOTH files into the repository root:
   - index.html
   - Record_2025-11-25-23-13-34_40deb401b9ffe8e1df2f1cc5ba480b12.mp4
3. Commit the files.
4. In the repository Settings -> Pages, under 'Build and deployment', select 'Deploy from a branch' and choose the main branch and root folder.
5. Save. GitHub will provide a Pages URL like: https://<your-username>.github.io/<repo-name>/
6. Open that URL — your site will use the video as background and show the birthday page.

NOTE: GitHub has a 100MB file limit for files in the repository. If your MP4 is larger, use GitHub Releases, an external host for the video (Cloudinary, S3), or Netlify Drop which supports direct file upload.
