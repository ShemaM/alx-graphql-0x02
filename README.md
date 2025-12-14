# ALX Rick and Morty App (GraphQL)

This project is part of the ALX Software Engineering curriculum (`alx-graphql-0x02`). It demonstrates how to integrate Apollo Client with Next.js to query the Rick and Morty GraphQL API, focusing on data fetching, strong typing with TypeScript, and pagination.

## 📂 Project Structure

```bash
alx-rick-and-morty-app/
├── components/
│   └── common/
│       └── EpisodeCard.tsx    # Reusable component to display episode info
├── interfaces/
│   └── index.ts               # TypeScript interfaces (EpisodeProps, InfoProps)
├── pages/
│   └── index.tsx              # Main page logic (Query, State, Pagination)
├── graphql/
│   └── queries.ts             # GraphQL queries definitions
└── README.md
