# Week 44 - The conflict and the card

**Svenska:** Vecka 44 - Krocken och kortet

## Question 1 - Agile

**English:** Agile, briefly, and the benefit: the line you moved, the sentence that remained.

**Svenska:** Agil, kort, och fördelen: raden ni flyttade, meningen som låg kvar.

**Answer:** Agil utveckling är att arbeta i korta rundor där teamet levererar en liten, testbar del i taget och justerar planen efter feedback. I vår sprint flyttade vi raden för rabattkoden från backloggen till en färdig funktion, men sprintmålet låg kvar oförändrat: kunden skulle kunna ange en kod i kassan. Fördelen var att vi kunde visa en fungerande del tidigt och bara ändra detaljerna som kunden faktiskt reagerade på.

## Question 2 - Scrum

**English:** Scrum with at least two concepts or roles you wrote, and how you used them.

**Svenska:** Scrum med minst två begrepp eller roller ni skrivit, och hur ni använde dem.

**Answer:** Vi använde rollerna Product Owner och Scrum Master. Filip Lind som Product Owner ägde kraven och skrev acceptanskriterierna för US-1 till US-4, medan Sara Viberg som Scrum Master höll i Daily Standup och höll ordning på sprinttavlan. Vi arbetade också med sprintmål och produktbacklog: varje User Story bröts ner till en rad i backloggen och flyttades från In Progress till In Review och Done.

## Question 3 - Git and GitHub

**English:** Git and GitHub with an example: a feature branch, an approval, the conflict.

**Svenska:** Git och GitHub med ett exempel: ett sidofack, en Approve, krocken.

**Answer:** Vi arbetade med ett gemensamt repo på GitHub. Jag skapade sidofacket `feature/erik` från `main`, ändrade bara raden i `statusFrakt()` och pushade branchen. Sara öppnade en Pull Request, läste `Files changed` och gav Approve innan vi mergade. När två sidofack hade ändrat samma `return`-rad i `hamtaNamn` uppstod en krock; vi behöll namnet från sprintmålet, tog bort markörerna och lät någon annan godkänna igen.

## Reflection

**English:** Reflection, 3-5 sentences. One sentence you changed, if you used AI.

**Svenska:** Reflektion, 3–5 meningar. En mening ni ändrade, om ni använde AI.

**Answer:** Det svåraste var krocken i `hamtaNamn`, eftersom båda sidofacken hade ändrat exakt samma rad. Vi förstod först inte varför den andra Pull Requesten stannade, men teoriguiden hjälpte oss att se att HEAD var raden som redan låg i `main`. Vi valde namnet som sprintmålet angav i stället för att bara ta den övre raden. En mening vi ändrade innan den stämde var att krocken inte "löstes automatiskt" – vi valde raden och lät en annan godkänna den.
