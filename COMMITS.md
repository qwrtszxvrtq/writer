# Commit map — easy to rework by topic

Each row is one logical point. Use the hash to inspect, revert, or cherry-pick.

| Topic | Hash | Message |
|-------|------|---------|
| Styles moved to external CSS | `0db9ea1` | chore: move styles to style.css |
| Single page + stylesheet (x2/style-x2 removed) | (this commit) | chore: suppress x2.html, style-x2.css; keep x.html, style.css |
| JS readability + faster logic | `15f4e30` | refactor(js): readability and faster logic |
| Responsive layout | `82f3ab3` | Responsive layout: viewport meta, fluid width/height |
| Encrypt on Tab/Enter, slice not substr | `cd63aba` | fix: persist encrypted content on Tab/Enter |
| Checkpoint (x2, remove x_) | `584b82a` | Checkpoint: writer app state |
| Scroll-to-caret | `fefd23f` | scroll issue halfly working — viewer follows caret |

**Rework a point:**  
`git show 15f4e30` — view that commit  
`git checkout 82f3ab3 -- x.html` — restore a file from that commit
