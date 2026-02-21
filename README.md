# playground

A minimal personal site showcasing projects and experiments.

🔗 [giorgiana.li](https://giorgiana.li)

---

## projects

| Name  | Stack                          | Status |
| ----- | ------------------------------ | ------ |
| Yolde | Angular 21, NestJS, PostgreSQL | Live   |

---

## about the site

A single-page HTML/CSS site. No frameworks, no build step — just a file.

## run locally

```bash
open index.html
```

Or just drag the file into your browser.

## add a new project

In `index.html`, find the `.grid` section and copy a card block:

```html
<a class="card" href="#">
  <div class="card-name">Project Name</div>
  <div class="card-desc">Short description.</div>
  <div class="card-meta">type · status</div>
  <div class="card-meta" style="margin-top:0.3rem; color:#ccc;">
    Stack · Here
  </div>
</a>
```

---

_Always building something._
