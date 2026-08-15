```
░██       ░██            ░██                                                      
░██       ░██            ░██                                                      
░██  ░██  ░██  ░███████  ░██  ░███████   ░███████  ░█████████████   ░███████      
░██ ░████ ░██ ░██    ░██ ░██ ░██    ░██ ░██    ░██ ░██   ░██   ░██ ░██    ░██     
░██░██ ░██░██ ░█████████ ░██ ░██        ░██    ░██ ░██   ░██   ░██ ░█████████     
░████   ░████ ░██        ░██ ░██    ░██ ░██    ░██ ░██   ░██   ░██ ░██            
░███     ░███  ░███████  ░██  ░███████   ░███████  ░██   ░██   ░██  ░███████  ░██ 
                                                                               ░█                                                                                                                 
```
## Hi, I'm Kyle
I build small web tools for students — the kind that do one thing, load fast, and don't
ask you to make an account first. Mostly vanilla JavaScript, Node, and Supabase. No
framework unless the project actually needs one.

### What I've built

**[Studs](https://github.com/kkyleee23/Studs)** — a configurable classroom grading system.
Teachers define their own grading categories and weights per class instead of picking from
a fixed list; students join by class code and log their own scores. The grade engine is a
set of pure functions with no I/O, covered by 15 tests, and handles weighted averages,
drop-lowest-N, and extra credit that adds to the numerator without inflating the
denominator. Postgres schema is six ordered migrations with row-level security.
*Vanilla JS, Vite, Supabase.*

**[PrintScreen](https://github.com/kkyleee23/PrintScreen)** — upload a PDF, DOCX, XLSX,
PPTX, or a photo of your notes and get back a study set: a summary, 8–15 key terms, 10–15
flashcards, and 15 multiple-choice questions with explanations. The prompt is built to
extract rather than invent — every answer has to come from the document you uploaded, not
from the model's general knowledge. *Node, Express, Groq (Llama 3.3 70B).*
[Live](https://printscreen.onrender.com)

**[Planora](https://github.com/kkyleee23/Planora-Official)** — a task manager for Android
and web. Tasks, notes, goals, and an assistant called Nora, in under 5MB, no account
required. *HTML, CSS, vanilla JS — no build step, no dependencies.*
[Live](https://planora-official.vercel.app)

### Reach me

kkyleplayz@gmail.com

<!--
Optional GitHub stats card — uncomment if you want it:
![](https://github-readme-stats.vercel.app/api?username=kkyleee23&show_icons=true&hide_border=true)
-->
