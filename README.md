# mega-s01e03-what-it-shows

Public deliverable for MEGA.dev challenge **S01E03 · what it shows**.

Support ticket **#4471** merged 412 date reports and marked them known as one bug.
The kb export’s cause logic shows **two** problems:

| cause | reports | outcome (desk · closed 05 Oct) |
| --- | ---: | --- |
| `parser` | 379 | FIXED — `fix(dates): parse dd/mm for eu locales` |
| `hint` | 33 | WON'T FIX — booking-v3 form retired |

## Deliverables

- **Tickets:** GitHub issues #1 (`parser`, completed) and #2 (`hint`, not planned)
- **Page (source):** [`src/routes/kb/incidents/4471-problems/+page.svx`](src/routes/kb/incidents/4471-problems/+page.svx)
- **Page (as the desk sees it):** [`src/routes/kb/incidents/4471-problems/as-the-desk-sees-it.html`](src/routes/kb/incidents/4471-problems/as-the-desk-sees-it.html)

This repo is the kb export (`apps/kb` → `src/`) plus the signed page and desk render above.
