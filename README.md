# Git Workflow Guide

An interactive Git cheat sheet built with HTML, CSS, and JavaScript — designed to demonstrate proper Git workflow practices.

## 🔗 Live Demo

[View Live](https://maitrip482.github.io/git-workflow-guide/)

## About This Project

This project serves two purposes:

1. **A useful reference** — Interactive guide covering Git basics, branching, remotes, and undoing changes
2. **A Git workflow demonstration** — The repository itself showcases proper version control practices

## Git Workflow Used

This project was built using a **feature branch workflow**:

```
main ── initial commit ──── merge ──── merge ──── merge ──── merge ──►
              \             /     \       /    \       /    \       /
               basics-section      branching    remotes      undo
```

### Practices Demonstrated

- **Feature branches** — Each section built on a dedicated branch (`feature/basics-section`, `feature/branching-section`, etc.)
- **Meaningful commit messages** — Descriptive, concise messages explaining what changed
- **No-fast-forward merges** — `--no-ff` preserves branch history in the commit graph
- **Clean history** — Logical, atomic commits (one purpose per commit)

## Project Structure

```
git-workflow-guide/
├── index.html      # Main page with tabbed sections
├── style.css       # GitHub-dark themed styling
├── script.js       # Tab navigation logic
├── .gitignore      # Ignored files
└── README.md       # This file
```

## Sections Covered

| Tab | Commands |
|-----|----------|
| Basics | `init`, `status`, `add`, `commit`, `log` |
| Branching | `branch`, `switch`, `merge`, `branch -d` |
| Remotes | `remote add`, `push`, `pull`, `fetch`, `clone` |
| Undo | `restore`, `revert`, `reset`, `stash` |

## Tech Stack

- HTML5
- CSS3 (GitHub-dark theme)
- Vanilla JavaScript

## Author

**Maitri Patel** — [GitHub](https://github.com/maitrip482)
