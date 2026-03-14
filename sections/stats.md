# 📊 GitHub Stats & Widgets

All widgets update **automatically** — no manual work needed after setup.

> ⚠️ Replace `YOUR_USERNAME` with your actual GitHub username in every URL.

---

## 1. GitHub Stats Card

Shows your total stars, commits, PRs, issues, and contribution streak.

```markdown
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true)
```

**Optional parameters you can add:**

| Parameter | Effect |
|-----------|--------|
| `&count_private=true` | Include private repo contributions |
| `&include_all_commits=true` | Count all commits, not just current year |
| `&hide=issues` | Hide specific stats (issues, prs, contribs, stars) |
| `&show=reviews` | Show extra stats |

---

## 2. Top Languages Card

Shows which programming languages you use most.

```markdown
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true)
```

**Layout options:**

```markdown
&layout=compact       ← Clean compact view (recommended)
&layout=donut         ← Donut chart
&layout=pie           ← Pie chart
&layout=donut-vertical
```

**Hide a language** (e.g., if HTML inflates your stats):

```markdown
&hide=html,css,jupyter%20notebook
```

---

## 3. GitHub Streak

Shows your current streak, longest streak, and total contributions.

```markdown
![GitHub Streak](https://streak-stats.demolab.com/?user=YOUR_USERNAME&theme=tokyonight&hide_border=true)
```

---

## 4. Activity Graph

A full contribution graph with a clean visual style.

```markdown
![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=tokyo-night&hide_border=true)
```

**Theme options:** `tokyo-night`, `github`, `github-compact`, `dracula`, `nord`, `minimal`

---

## 5. GitHub Trophies

Gamified achievement badges based on your GitHub stats.

```markdown
![Trophies](https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=darkhub&no-frame=true&row=1&column=7)
```

**Column options:** Change `column=7` to `column=4` or `column=6` based on your layout.

---

## 6. Pinned Repository Cards

Show individual repo cards inside your README.

```markdown
[![Repo Card](https://github-readme-stats.vercel.app/api/pin/?username=YOUR_USERNAME&repo=REPO_NAME&theme=tokyonight&hide_border=true)](https://github.com/YOUR_USERNAME/REPO_NAME)
```

---

## 7. Visitor Counter

Counts how many people have visited your profile.

```markdown
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=YOUR_USERNAME.YOUR_USERNAME)
```

---

## 🎨 Available Themes

Use `&theme=THEME_NAME` on any stat card:

| Theme Name | Style |
|------------|-------|
| `tokyonight` | Dark blue/purple |
| `radical` | Pink/purple gradient |
| `merko` | Green terminal |
| `gruvbox` | Warm brown/orange |
| `dracula` | Classic dark |
| `nord` | Cool blue-grey |
| `github_dark` | GitHub dark mode |
| `dark` | Simple dark |
| `default` | GitHub light |
| `highcontrast` | High contrast dark |
| `cobalt` | Deep blue |
| `synthwave` | Retro neon |

---

## 💡 Pro Layout Tips

### Side by Side Stats (Recommended)

```markdown
<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true" height="170" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true" height="170" />

</div>
```

### Full Width Streak Below

```markdown
<div align="center">

![Streak](https://streak-stats.demolab.com/?user=YOUR_USERNAME&theme=tokyonight&hide_border=true&card_width=700)

</div>
```

---

## ⚠️ Common Mistakes

- ❌ Forgetting to replace `YOUR_USERNAME`
- ❌ Using `count_private=true` when your private repos are empty
- ❌ Adding too many stat cards — 2-3 is enough
- ❌ Mismatching themes between different cards (keep them consistent)
