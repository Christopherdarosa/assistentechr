
# Sistema Simulado Mercos

Este projeto é um MVP (Produto Mínimo Viável) desenvolvido com **Next.js + React**, com o objetivo de demonstrar funcionalidades automatizadas de atendimento comercial para representantes que utilizam o sistema **Mercos**.

## 🚀 Funcionalidades do MVP

- Login protegido por e-mail e senha
- Painel com KPIs de:
  - Clientes ativos e inativos
  - Pedidos do mês
  - Boletos próximos do vencimento
  - Produtos mais vendidos
  - Clientes inativos
- Mensagens automáticas geradas para:
  - Aniversariantes do dia
  - Sugestões de recompra
  - Avisos de vencimento de boletos
  - Resumo do pedido com espaço para colar o link do PDF
- Exportação de mensagens para `.txt`
- Filtros por data para boletos

## 📦 Tecnologias utilizadas

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide Icons](https://lucide.dev/icons)

## 🧭 Como rodar

1. Instale as dependências:
   ```bash
   npm install
   ```

2. Rode o servidor local:
   ```bash
   npm run dev
   ```

3. Acesse `http://localhost:3000`

## 🔐 Login de acesso

- **E-mail**: vendas@chrrepresentacao.com  
- **Senha**: @Chr5204

---

> Este projeto está pronto para ser publicado na [Vercel](https://vercel.com/) e adaptado com API oficial do Mercos e integração ao WhatsApp via 360dialog ou alternativa (AiSensy, Interakt, etc.).

## 📌 Observações

- Todos os dados utilizados são simulados a partir de planilhas reais (.xlsx).
- A lógica de automações já está aplicada — apenas as integrações ainda são feitas manualmente neste MVP.
