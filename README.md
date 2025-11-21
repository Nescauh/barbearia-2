# BarberSaaS

Sistema completo de agendamento para barbearias.

## Funcionalidades

- **Painel do Barbeiro**: Gestão de serviços, horários e agendamentos.
- **Agendamento Online**: Link público para clientes agendarem.
- **Bloqueio Automático**: Impede agendamentos duplicados.
- **Design Moderno**: Interface Neon/Dark responsiva.

## Como Rodar

1.  Instale as dependências:
    ```bash
    npm install
    ```

2.  Configure o Banco de Dados:
    ```bash
    npx prisma migrate dev --name init
    ```

3.  Rode o servidor de desenvolvimento:
    ```bash
    npm run dev
    ```

4.  Acesse `http://localhost:3000`.

## Tecnologias

- Next.js 14 (App Router)
- Prisma (SQLite)
- Tailwind CSS (via Global CSS variables)
- Lucide React (Ícones)
