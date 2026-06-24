# Frontend BOLD Preservation Manifest

This manifest tracks the relevant folders discovered in the workspace, their classification, current GitHub/Vercel state, and preservation status.

| Local source path | Classification | GitHub destination | Final commit | Vercel URL | Preservation status |
| --- | --- | --- | --- | --- | --- |
| `01_projects/gabyherbstein` | Independent website | `ignacioperezroca/gabyherbstein` | `7577e0a1e0b589d3a768dd0b7aff0c1d87958f18` | `https://gabyherbstein.vercel.app` | Preserved and published |
| `01_projects/cerro-castor` | Independent website | `ignacioperezroca/cerro-castor` | `765f060250dfc248364973853175bedd7efbd9fc` | `https://cerro-castor.vercel.app` | Preserved and published |
| `02_portfolio/g7` | Independent website | `ignacioperezroca/g7-portfolio` | `34828a443cbe468f6a4c23740bd5a3c8c55061b8` | `https://g7-blue.vercel.app` | Preserved and published |
| `01_projects/nina pulenta/www/tether-1.1.1` | Independent application / docs site | `ignacioperezroca/tether-website` | `05f29cf3733144f0429a67a485c6f9d8d08c937a` | `https://tether-111.vercel.app` | Preserved and published |
| `01_projects/nina pulenta/www` | Independent website | `ignacioperezroca/tether-website` | see nested project above | `https://tether-111.vercel.app` | Parent folder preserved; nested docs project published |
| `01_projects/web kibind/www` | Independent website | `ignacioperezroca/web-kibind` | `e76ac681bec4562cacbf27de900bcbc5eead9d9c` | `https://www-nu-two.vercel.app` | Preserved and published |
| `02_portfolio/porsche/porsche` | Independent website | `ignacioperezroca/porsche-portfolio` | `a2f0b5a` (see GitHub repo history) | `https://porsche-hazel.vercel.app` | Preserved and published |
| `01_projects/2091/soundboard-website` | Independent website | `ignacioperezroca/soundboard-website` | `7f37081e5ac8df6f2e7a0c941cad6278b2bc6e6d` | `https://soundboard-website.vercel.app` | Preserved and published |
| `01_projects/boulevard58/wwww` | Independent website | `ignacioperezroca/boulevard58` | `b5bf134ad35e641d7c8d5e8df77e593c0bf1975d` | `https://wwww-taupe.vercel.app` | Preserved and published |
| `03_reference/bold www/www` | Independent website / legacy archive | `pending` (`ignacioperezroca/bold-studio` was attempted but could not be created/pushed in this session) | `e1d4c00` | `https://www-nu-two.vercel.app` | Locally preserved, migration blocked by GitHub auth |
| `03_reference/bold www/www` | Independent website / legacy archive | `ignacioperezroca/bold-studio` | `4eb58fc7a549092f76174bf14627daab44d33454` | `https://bold-studio.vercel.app` | Preserved and published |
| `01_projects/thet/_newletters/...` | Banner or campaign collection | `pending archive repo` | n/a | n/a | Classified as creative exports |
| `01_projects/thet/banners/...` | Banner or campaign collection | `pending archive repo` | n/a | n/a | Classified as creative exports |
| `03_reference/bold www/www/css/*`, `fonts/*`, `img/*`, `js/*` | Source asset archive | same as `03_reference/bold www/www` | n/a | n/a | Preserved as valuable original assets |
| `node_modules`, `.vercel`, caches, build artifacts, OS metadata` | Dependency/build artifact | excluded | n/a | n/a | Safe to exclude |

## Notes

- The GitHub CLI is now installed and authenticated in this environment.
- Terminal GitHub HTTPS pushes now work for authenticated repos.
- The built-in browser session was not needed once `gh` auth succeeded.
- Vercel authentication is available in the terminal (`bold-npr`).
- The creative/banner trees contain hundreds of ad-format HTML files and are best handled as archive material, not standalone websites.
