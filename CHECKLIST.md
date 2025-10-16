# Regression Checklist

## Before commit (local)
- [ ] Page loads with **no console errors** (open DevTools → Console)
- [ ] All **internal links** work and route correctly
- [ ] External links open and are correct
- [ ] Images load; each has **alt** text; no layout shift
- [ ] Forms (if any) validate and submit as expected
- [ ] Keyboard navigation works (Tab/Shift+Tab); visible focus states
- [ ] Titles (`<title>`) and meta description set on each page
- [ ] Mobile viewport meta tag present (`<meta name="viewport" ...>`)
- [ ] Basic accessibility: landmark tags (`<header> <main> <nav> <footer>`), labels, aria where needed
- [ ] Responsive at common widths: **320px**, **768px**, **1024px**, **1440px**
- [ ] Lighthouse (local): **≥95** for Performance, Accessibility, Best Practices, SEO

## Pre-release (staging/local server)
- [ ] CSS/JS load from the correct paths (no 404s)
- [ ] Favicon loads
- [ ] No mixed content (all HTTPS)
- [ ] Image sizes reasonable (no multi-MB assets)

## Post-deploy (GitHub Pages)
- [ ] Site loads at `https://<username>.github.io/<repo>/`
- [ ] No console errors; no broken links
- [ ] Lighthouse (production) **≥95** all categories
- [ ] If using a custom domain: `CNAME` file present; HTTPS enforced
