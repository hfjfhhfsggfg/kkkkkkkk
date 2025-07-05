# 🛍️ Lojinha Online - Netlify

Uma loja online completa e responsiva, otimizada para hospedagem no Netlify.

## 🚀 Deploy no Netlify

### Opção 1: Deploy Automático
1. Faça fork deste repositório
2. Conecte sua conta do Netlify ao GitHub
3. Selecione este repositório
4. O Netlify detectará automaticamente as configurações

### Opção 2: Deploy Manual
1. Execute `npm run build` localmente
2. Faça upload da pasta `out` no Netlify
3. Configure redirects para SPA

## 📁 Estrutura do Projeto

\`\`\`
├── components/          # Componentes React
├── lib/                # Utilitários e stores
├── app/                # Páginas Next.js
├── public/             # Arquivos estáticos
├── netlify.toml        # Configuração Netlify
└── next.config.js      # Configuração Next.js
\`\`\`

## ✨ Funcionalidades

- 🛒 **Carrinho de Compras** - Adicionar/remover produtos
- 💬 **Chat de Suporte** - Sistema de chat local
- 📱 **WhatsApp Integration** - Finalização via WhatsApp
- 🎨 **Admin Panel** - Gerenciamento completo
- 📊 **Analytics** - Relatórios de vendas
- 🎯 **Banners** - Carrossel promocional
- 📱 **Responsivo** - Mobile-first design

## 🔧 Configuração

### Dados Locais
- Todos os dados são salvos no localStorage
- Não requer banco de dados
- Funciona 100% offline

### WhatsApp
Configure o número no painel admin:
- Formato: `5511999999999` (país + DDD + número)

## 🎨 Personalização

### Cores
- Primária: Amarelo/Dourado
- Secundária: Verde (WhatsApp)
- Acentos: Configuráveis no admin

### Logo e Branding
- Upload via URL no painel admin
- Suporte a imagens externas
- Favicon personalizável

## 📱 Mobile

- Design mobile-first
- Touch-friendly
- PWA ready
- Otimizado para conversão

## 🔒 Segurança

- Dados locais apenas
- Sem exposição de APIs
- Validação client-side
- Sanitização de inputs

## 📈 Performance

- Build estático
- Imagens otimizadas
- Lazy loading
- Cache agressivo

## 🆘 Suporte

Para dúvidas ou problemas:
1. Verifique a documentação
2. Teste em modo desenvolvimento
3. Verifique o console do navegador
