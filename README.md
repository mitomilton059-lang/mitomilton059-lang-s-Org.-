# INDUSTEL 3D Platform — primeira versão

Primeira versão do site público + estrutura de painel administrativo.

## Executar

```bash
npm install
npm run dev
```

## O que já existe

- Home 3D com cena CSS 3D e animação
- Catálogo de 21 formações identificadas no material fornecido
- Pesquisa e filtro
- Página individual de curso
- Formulário de inscrição persistido localmente para protótipo
- Notícias
- Contactos
- Academia / Sobre
- Área administrativa com dashboard, cursos, inscrições, notícias e módulos preparados
- Layout responsivo
- Reduced motion
- SEO básico
- Botão WhatsApp

## Produção

O login atual é apenas protótipo local. Antes de aceitar dados reais, ligar:

- Supabase Auth
- PostgreSQL
- RLS em todas as tabelas sensíveis
- RBAC: super_admin, admin, editor
- Auditoria
- Storage para galeria
- Validação servidor/cliente
- Rate limiting e proteção anti-spam

Não foram inventados preços, durações, horários, requisitos ou endereço completo. Esses campos aparecem como “A confirmar”.
