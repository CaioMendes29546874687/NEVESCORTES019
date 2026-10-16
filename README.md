# NEVESCORTES019

Site de agendamento e painel privado para uma única barbearia/salão, com identidade preta e dourada.

## Tecnologias
- Node.js 20+, Express e PostgreSQL
- Site responsivo em `public/`
- Agendamento com verificação de conflitos no servidor
- Painel em `/admin` para agenda, status, serviços, despesas e faturamento

## Publicação
1. Crie um banco PostgreSQL gerenciado.
2. Configure `DATABASE_URL`, `JWT_SECRET` (32+ caracteres), `ADMIN_USER`, `ADMIN_PASSWORD` e `NODE_ENV=production` no host.
3. Use `npm install` e `npm start`.
4. Abra `/` para o site e `/admin` para o painel.

## Antes de publicar
- Use uma senha forte e exclusiva para o proprietário.
- Ajuste preços, endereço, expediente e duração dos serviços.
- Expediente inicial de exemplo: segunda a sábado, 09h–18h, com pausa 12h–13h; domingo fechado.
- Os valores dos serviços são exemplos iniciais.
- Agendamentos ficam pendentes até confirmação do profissional.
- Não há envio automático de WhatsApp/e-mail nem pagamento online nesta versão.
- Teste com PostgreSQL real e configure backups antes de divulgar o site.
