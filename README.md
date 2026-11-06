# Hi, I'm Ganesh

Computer Science student in Copenhagen (graduating 2027) and solo founder of **KitchenHand**, a SaaS for professional kitchens in Denmark. I build full-stack products end to end and run them in production.

Open to student developer (studiejob) roles in Copenhagen.

## What I'm building

### KitchenHand · [kitchen-saas-six.vercel.app](https://kitchen-saas-six.vercel.app)

The head chef's app for running a kitchen in Denmark. Multi-tenant, with a working restaurant as its first tenant.

- Daily checklists, supplier orders with generated supplier emails, recipes with EU allergen tags, egenkontrol (food-safety) records, staff training, team chat and a social feed
- Stripe subscription billing on nine Cloud Functions (Node 24, europe-west1), secrets in Google Cloud Secret Manager
- Migration scripts that moved a live restaurant's checklists, orders, recipes and staff accounts from its previous app
- Automated Firestore backups with point-in-time recovery, added after recovering from a production incident
- AI photo import on the Anthropic API with a per-tenant daily usage cap

`React` `Vite` `Firebase` `Cloud Functions` `Stripe` `Cloudinary` `Vercel`

*Source is private because it is a commercial product. Happy to walk through the code in an interview.*

### Cholon Staff App

The staff app I built for Cholon, the Vietnamese restaurant in Copenhagen where I work. Group chat, DMs with audio calls and voice notes, push notifications, kitchen tools and a four-level permission model, in English, Danish and Nepali. It became the prototype for KitchenHand.

### [Hello Babe](https://github.com/guruparsadkandel-ops/hello-babe)

My first React project: a private real-time messaging PWA with chat, voice notes and WebRTC calls through Agora.

## Stack

**Front end:** JavaScript, React, Vite, PWAs
**Back end:** Firebase (Firestore, Auth, Cloud Functions, Cloud Messaging), Node.js, Express, Deno
**Integrations:** Stripe, Agora RTC, Cloudinary, Anthropic API
**Also:** C# / ASP.NET Core, SQL Server, Git, Jira, Scrum

## Contact

guruparsadkandel@gmail.com · Copenhagen, Denmark
