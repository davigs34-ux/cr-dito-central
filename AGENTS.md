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

## Project rules
- External agents (e.g. ChatGPT) queue work in `INSTRUCOES.md`; when the user says "siga as instruções", execute pending items and mark them done — keeps one shared task inbox.
- Routing is TanStack Router file routes in `src/routes`; never add react-router or edit `src/routeTree.gen.ts` (generated).
- Styling uses semantic tokens in `src/styles.css` (Tailwind v4); no hardcoded color utilities — keeps theming consistent.
- Push only to the synced main branch and keep it building — other branches don't reach Lovable.
