FIRST ANNIVERSARY SURPRISE WEBSITE
===================================

WHAT'S INCLUDED
- 18 separate surprise pages with Previous / Next navigation.
- Password entry screen before the first page.
- Password: HAPPY MARRAIGE ANNIVERSARY
  (The spelling is kept exactly as requested.)
- The six photos you uploaded are already placed in decorative frames.
- Floating sparkle/heart effects, page transitions, responsive mobile layout,
  stylish headings, Hindi/Hinglish anniversary poetry.
- Eight extra memory slots are prepared.

HOW TO PUBLISH ON GITHUB PAGES
1. Extract this ZIP on your phone/computer.
2. Open your GitHub repository and upload ALL files and folders from inside
   this extracted folder. Keep index.html at the repository root.
3. Commit the upload.
4. In GitHub open Settings -> Pages.
5. Under Build and deployment choose "Deploy from a branch".
6. Select branch "main" and folder "/ (root)", then Save.
7. Wait for GitHub Pages to publish. Open the website URL shown in Settings -> Pages.

HOW TO ADD YOUR OWN MEMORIES
1. Open assets/memories.
2. Add up to eight images named exactly:
   memory-01.jpg, memory-02.jpg, memory-03.jpg, memory-04.jpg,
   memory-05.jpg, memory-06.jpg, memory-07.jpg, memory-08.jpg
3. The prepared memory gallery currently shows labelled empty frames.
   To show added files as photos, replace the memory-slots section in index.html
   with <img> tags using paths such as:
   <img src="assets/memories/memory-01.jpg" alt="Our memory">
   The supplied six photos are already visible in the other framed sections.

IMPORTANT PASSWORD NOTE
This is a front-end surprise gate, not secure authentication. The password is
stored in the website's JavaScript, so a visitor with technical knowledge can
inspect the source. Do not use it to protect private or sensitive information.

EDITING
- Main website: index.html
- Uploaded couple photos: assets/photos/
- Extra memory photos: assets/memories/
- All files must keep their folder structure when uploaded to GitHub.
