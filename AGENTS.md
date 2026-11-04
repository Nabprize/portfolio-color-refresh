<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

<!-- PROJECT:BEGIN -->
# Project decisions

- The portfolio code was imported from github.com/launchpadsolutionstech-sys/hassan-wali-portfolio; the portrait is stored as a real file (src/assets/hassan-wali-portrait.png) with a direct ES6 import, not a lovable-assets pointer — the original pointer 404s outside its source project.
