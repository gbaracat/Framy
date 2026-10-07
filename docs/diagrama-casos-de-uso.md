# Diagrama de Casos de Uso — Framy

```mermaid
flowchart LR
    U((Usuário))

    U --> A[Criar conta / Login]
    U --> B[Explorar filmes e séries]
    U --> C[Pesquisar títulos]
    U --> D[Visualizar detalhes]
    U --> E[Avaliar filme ou série]
    U --> F[Escrever review]
    U --> G[Adicionar aos favoritos]
    U --> H[Adicionar à lista]
    U --> I[Visualizar perfil]
    U --> J[Seguir usuários]
    U --> K[Visualizar atividade]
    U --> L[Usar Match]
    U --> M[Criar listas]

    L --> N[Calcular compatibilidade]
    N --> O[Mostrar gostos em comum]
    N --> P[Gerar recomendações]
