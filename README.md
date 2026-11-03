# SGCC — Gestão de Carregamentos

MVP de interface do Sistema de Gestão de Carregamentos, desenvolvido em React + TypeScript + Vite e preparado para publicação estática no Netlify.

## Funcionalidades demonstrativas
- Dashboard operacional com indicadores.
- Consulta e filtro de carregamentos por placa, cliente, motorista e ID.
- Detalhes da programação e confirmação manual simulada.
- Central de confirmações.
- Cadastro demonstrativo de 12 destinatários.
- Área de notificações SMS e integrações.
- Documentação e impressão A4 pelo navegador.
- Interface responsiva para computador e celular.

## Executar localmente
Requer Node.js 20 ou superior.

```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

Netlify: comando `npm run build`, diretório `dist`, diretório base na raiz.

## Limites desta versão
Os dados são fictícios e mantidos apenas no estado da interface. Não há integração real com WhatsApp, Google Sheets, SMS, autenticação ou PostgreSQL. A integração ao grupo atual do WhatsApp depende de prova de conceito com meio oficialmente autorizado. Não cadastrar credenciais ou chaves privadas no frontend.

## Próximas etapas
1. Backend/API e PostgreSQL.
2. Autenticação, perfis e auditoria.
3. Sincronização Google Sheets.
4. Prova de conceito de captura do grupo WhatsApp.
5. Fila de SMS, webhooks de entrega e idempotência.
6. PDFs operacionais e testes de implantação.
