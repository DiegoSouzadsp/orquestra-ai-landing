
# 🧩 Infraestrutura da Orquestra AI – Mapa de Configurações

## 🔗 Domínio Principal
- **Domínio**: `orquestraai.com`
- **Registrado em**: [Squarespace Domains](https://domains.squarespace.com)
- **Gerenciamento de DNS**: Squarespace  
- **E-mail Corporativo (em progresso)**: via Google Workspace  
  > Exemplo: `diegoprado@orquestraai.com` (a ser ativado quando possível)

---

## 🌐 Landing Page do Jarvis
- **Projeto GitHub**: [`orquestra-ai-landing`](https://github.com/DiegoSouzadsp/orquestra-ai-landing)
- **Deploy Vercel**:  
  - Link atual: [https://orquestraai.com](https://orquestraai.com)  
  - Gerenciado diretamente pela Vercel
- **Formulário de captura**:
  - Envia dados para o **Pipedream Webhook**
  - Os dados capturados são redirecionados para o **banco de leads no Notion**

---

## 🧠 Webhook + Integração com Notion
- **Plataforma usada**: [Pipedream](https://pipedream.com)
- **Webhook**: Recebe e processa os dados do formulário da landing
- **Integração ativa com Notion**:
  - Os dados são registrados na sua tabela personalizada no Notion
  - Integração devidamente autorizada e compartilhada com o banco de dados correto

---

## 🎨 Logo
- Arquivo da logo com fundo transparente: `logo_orquestra_nome.png`
- Local de uso: na landing e para futuros materiais institucionais
- Dimensões otimizadas para web: aprox. 400px de largura, mantendo proporção

---

## 💻 Hospedagem e Deploy
- **Plataforma de deploy**: [Vercel](https://vercel.com)
- Projeto principal: `orquestra-ai-landing`
- Conectado ao domínio oficial via DNS

---

## 📌 Checklist Futuro
- [ ] Finalizar ativação do Google Workspace (aguardando CNPJ)
- [ ] Criar site institucional completo com portfólio e serviços
- [ ] Registrar subdomínio para separar projetos (ex: `app.orquestraai.com`)
- [ ] Ativar sistemas de notificação automática (email ou WhatsApp)
- [ ] Criar área administrativa / interna (monitoramento de leads e uso da IA)
