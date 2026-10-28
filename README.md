# mega-s01e03-what-it-shows

Public deliverable for MEGA.dev challenge **S01E03 · what it shows**.

Support ticket **#4471** merged 412 date reports and marked them known as one bug.
The kb export’s cause logic shows **two** problems:

| cause | reports | what |
| --- | ---: | --- |
| `parser` | 379 | shared parser reads month-first; day-first tenants flip |
| `hint` | 33 | booking-v3 shows `MM/DD/YYYY`; form still reads day-first |

## Deliverables

- **Tickets:** GitHub issues in this repo — one per cause, with report counts
- **Page (source):** `support-kb/src/routes/kb/incidents/4471-problems/+page.svx`
- **Page (as the desk sees it):** [`rendered/4471-problems.html`](rendered/4471-problems.html)

The `support-kb/` tree is the challenge kb export, plus the signed page above.
