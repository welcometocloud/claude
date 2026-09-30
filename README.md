# CCAR-F iPad Practice App

This app is tied to the public repository:
https://github.com/paullarionov/claude-certified-architect

It loads the current `practical_test_en.html` question bank from the repository at runtime.

## Publish with GitHub Pages

1. Create a new GitHub repository (or use your existing practice repository).
2. Upload `index.html`.
3. Repository → Settings → Pages.
4. Source: Deploy from a branch.
5. Branch: `main`, folder `/ (root)`.
6. Save.
7. Open the generated `https://YOUR-USER.github.io/YOUR-REPO/` URL in Safari.
8. Safari → Share → Add to Home Screen.

## Features

- 60-question randomized mock
- 60-minute timer
- Previous/Next
- Question navigator
- Flag questions
- Answers hidden until submission
- Full review with source explanations
- Local attempt history
- Weak-question practice based on previously missed source question IDs
- Automatically loads the current GitHub question bank when the app starts

The question bank is not copied into this app; it is fetched from the repository.
