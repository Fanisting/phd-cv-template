# CV Templates

This repository contains a LaTeX CV template derived from my local academic CV workflow, plus anonymous public versions suitable for sharing on GitHub.

## Repo Layout

- `public/cv-anonymous-en.tex`: anonymous English CV
- `public/cv-anonymous-zh.tex`: anonymous Chinese CV
- `phd-cv-xuhang.tex`: private English CV for local use
- `phd-cv-xuhang-chn.tex`: private Chinese CV for local use

The private files are ignored by `.gitignore` so the repository can stay public without exposing personal details.

## Compile

English:

```powershell
pdflatex public/cv-anonymous-en.tex
```

Chinese:

```powershell
xelatex public/cv-anonymous-zh.tex
```

Local private versions:

```powershell
pdflatex phd-cv-xuhang.tex
xelatex phd-cv-xuhang-chn.tex
```

## Notes

- The Chinese version uses `xeCJK`, so compile it with `xelatex`.
- The anonymous files are intended as public-safe examples and can be adapted into a reusable CV template.

