<h2 align="center">Alexandre Aloesode — Développeur Full-Stack</h2>
<p align="center">PHP · TypeScript · Python — APIs, applications métier et outils internes en production</p>

Développeur full-stack à **[La Plateforme](https://laplateforme.io)** (Marseille) depuis 2023, je conçois et maintiens l'écosystème applicatif interne de l'école : une API centrale, plusieurs intranets et portails, et les services qui les relient. Ancien commercial reconverti, j'aime traduire un besoin métier en outil simple, fiable et utilisé au quotidien.

**En chiffres (dépôts pro privés) :** ~2 400 commits et ~600 pull requests mergées sur une quinzaine de services en production.

---

### 🏢 Projets professionnels

> Code propriétaire hébergé dans l'organisation privée `laplateformeio` — détails et démo sur demande.

| Projet | Rôle & réalisations | Stack |
|---|---|---|
| **API LaPlateforme** | API REST centrale consommée par tous les services : ~660 commits, 130+ PR. Contrôle d'accès par rôle (11 rôles), audit log, imports de masse, optimisation de requêtes sur tables de plusieurs millions de lignes. | PHP 8.3, CodeIgniter 4, MariaDB |
| **Authentication** | Service d'authentification SSO : Google OAuth, émission et rotation de JWT partagés entre services. | PHP, CodeIgniter 4, JWT |
| **Intranet administratif** | SPA de gestion pédagogique (étudiants, promotions, unités, compétences, alternances, assiduité, dashboards). ~600 commits, 150+ PR. | PHP, JavaScript, jQuery |
| **Intranet étudiant** | Portail étudiant : projets, compétences, absences, logtime. | PHP, JavaScript |
| **La Hanse** | Plateforme d'enchères en ligne et en live (maisons de vente, acheteurs, adjudications) : 440+ commits, ~200 PR en 6 mois. Temps réel WebSocket, paiements Stripe / SEPA, audit de sécurité (CSP, rotation des refresh tokens, rate limiting, secrets). | TypeScript, React, Hono, Prisma, PostgreSQL |
| **Technicert (soft skills)** | Plateforme d'évaluation des soft skills ; migration d'un backend Hono/Prisma vers l'API centrale. Tests E2E Cypress + Cucumber. | React, TypeScript, Vite |
| **Plateforme Connect** | Portail tuteurs / entreprises pour le suivi des alternants (absences, projets, rendez-vous). | React, TypeScript, Hono, Prisma |
| **Atlas interne** | Base de connaissances interne avec CMS headless. | Next.js, Strapi, TailwindCSS |
| **Assistant RAG intranet** | Microservice de questions-réponses sur la documentation interne : embeddings locaux (bge-m3), pgvector, filtrage des sources par rôle, LLM via OpenRouter avec citations. | Python, FastAPI, pgvector |
| **Synchronisation Filiz** | Scripts cron de synchronisation des contrats d'alternance depuis une API partenaire, idempotents, avec rapport mail. | PHP, Docker |
| **Infra** | Monorepo Docker Compose (8 services), chart Helm, secrets chiffrés (SOPS), Vault. | Docker, Helm, Kubernetes |

### 🧪 Projets personnels et de formation

| Projet | Description | Stack |
|---|---|---|
| **SchoolTool** | Application mobile d'intranet scolaire (emplois du temps, notes, absences) avec API et service d'auth OAuth2 séparés. | React Native (Expo), CodeIgniter, MariaDB, Docker |
| **Covertech** | Boutique e-commerce (catalogue, fiches produit, gestion des commandes) réalisée en équipe lors du hackathon La Plateforme 2023. | JavaScript, PHP |
| **[Tarot Next.js](https://github.com/alexandre-aloesode/tarot-nextjs)** | Jeu de tarot en ligne. | Next.js, TailwindCSS |

### 🛠️ Stack

**Back-end :** PHP (CodeIgniter 4), Node.js / TypeScript (Hono, Prisma), Python (FastAPI)  
**Front-end :** React, Next.js, React Native, Vite, TailwindCSS, jQuery  
**Données :** MariaDB / MySQL, PostgreSQL, pgvector  
**DevOps :** Docker, Docker Compose, Helm, GitHub Actions, SOPS, Vault  
**Qualité & méthode :** PHPUnit, Vitest, Jest, Cypress, revue de code par PR, suivi de tickets

<p>
<img src="https://skillicons.dev/icons?i=php,ts,js,python,react,nextjs,nodejs,mysql,postgres,docker,kubernetes,githubactions,tailwind,linux" />
</p>

### 📫 Contact

- LinkedIn : [alexandre-aloesode](https://linkedin.com/in/alexandre-aloesode-29501694)
- Email : alexandrealoesode@gmail.com
