# VocabQuest Web App (Windows-friendly)

This is a home-screen web app version of VocabQuest, built for Safari on iPhone. It includes the 299 GRE words from the supplied PDF, meanings, examples, level practice, daily newly-mastered count, and quick tests.

## Publish free with GitHub Pages
1. Create/sign in to a GitHub account at https://github.com.
2. Create a new public repository named `vocabquest`.
3. Click **Add file → Upload files** and upload all files in this folder (index.html, app.js, style.css, words.json, manifest.json, icon.svg, sw.js, README.md). Upload the files themselves, not the containing folder.
4. Click **Commit changes**.
5. Open the repository's **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
7. Wait for GitHub Pages to publish and open the displayed website URL. It will look like `https://YOUR-USERNAME.github.io/vocabquest/`.
8. On iPhone, open that URL in **Safari**, tap Share, choose **Add to Home Screen**, leave **Open as Web App** enabled if shown, then tap Add.

## Important privacy note
Learning state is stored in the browser's local storage on the device. The static files are hosted publicly, so anyone with the site URL can access the vocabulary content. Your personal quiz progress is not uploaded to GitHub. Avoid entering sensitive information (this app does not ask for any).

## Rules
- 10 words per level, with a final level of 9 words because the PDF contains 299 words.
- Each word needs 3 correct answers to count as mastered.
- An incorrect answer queues that word for at least 5 extra questions.
- Quick Test covers words already mastered.
