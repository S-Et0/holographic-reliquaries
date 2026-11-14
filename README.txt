HOLOGRAPHIC RELIQUARIES — SIMPLE EXHIBITION VIDEO PAGES

FILES
  index.html       optional main gallery page
  avatar.html      Reliquary of Avatar
  intimacy.html    Reliquary of Intimacy
  memory.html      Reliquary of Memory
  style.css        shared design
  videos/          put original and mirrored MP4 videos here

1. Add your finished videos to the 'videos' folder, named exactly:
   avatar.mp4
   intimacy.mp4
   memory.mp4
   avatar-mirrored.mp4
   intimacy-mirrored.mp4
   memory-mirrored.mp4

2. Test locally by opening an HTML file in your browser.
   (If browser security interferes, run a local server such as
   'python -m http.server 8000' from this folder.)

3. Publish with GitHub Pages:
   - Make a NEW PUBLIC GitHub repository, e.g. holographic-reliquaries
   - Upload index.html, avatar.html, intimacy.html, memory.html,
     style.css and the videos folder.
   - Go to repository Settings > Pages > Build and deployment.
   - Choose Deploy from a branch, main branch, /(root), then Save.
   - Once published, typical page URLs look like:
       https://YOUR-USERNAME.github.io/holographic-reliquaries/avatar.html
       https://YOUR-USERNAME.github.io/holographic-reliquaries/intimacy.html
       https://YOUR-USERNAME.github.io/holographic-reliquaries/memory.html
   - The specific live URLs depend on your GitHub username and repo name.

IMPORTANT VIDEO HOSTING NOTE
   GitHub may reject ordinary file uploads above 25 MB through the browser,
   and regular GitHub files cannot exceed 100 MB. GitHub Pages has a 1 GB
   published-site size limit and is not ideal for hosting large videos.
   Six videos may add up quickly. If your videos are large, host them separately (e.g. Vimeo or another
   stable video host) and update each <video> source or use an embed.
   MP4 encoded with H.264 video is the most broadly compatible choice.

4. Once the live pages work on your phone, make 3 QR codes, each pointing
   to the exact live URL of avatar.html, intimacy.html and memory.html.
   Print each QR code beside its corresponding sculpture.

5. Scan and test each printed QR code on iPhone and Android, over cellular
   data as well as Wi-Fi. Check that videos play and text is legible.

EDITING
   All descriptive copy is editable directly in its HTML file.
   Pages intentionally require a tap to play so mobile browsers behave
   reliably and visitors control their data usage.

VIDEO VARIANTS
  Each reliquary page contains two independent video players:
  - Original video, for direct viewing
  - Mirrored video, for setups that require a horizontally reversed image
  Upload BOTH files to the videos/ folder. The mirrored file must actually
  be reversed in the exported MP4; the webpage does not flip it automatically.
  If you are using a different optical arrangement, test the orientation
  with your acrylic/reflection setup before printing QR labels.

ARTIST STATEMENTS
  Each individual HTML page includes a short, editable artwork statement
  in the 'About the artwork' section after the two videos.
