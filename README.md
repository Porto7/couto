# 📸 Renzo Couto Photography - Plataforma Audiovisual Profissional

Uma plataforma moderna e completa para apresentar, divulgar e gerenciar os trabalhos de **Renzo Couto e Souza**, fotógrafo, filmmaker e produtor audiovisual reconhecido por seu trabalho com grandes marcas e forte presença nas áreas de vídeo institucional, imobiliário e captação com drone.

---

## 🎯 Objetivo do Projeto

Criar um sistema completo em **Next.js 15** com foco em:

- Exibir o **portfólio audiovisual de Renzo Couto**
- Disponibilizar informações sobre seus serviços e trajetória
- Permitir a **gestão completa e autônoma** de fotos, textos e conteúdos via **painel administrativo**
- Estimular o contato e conversão de leads
- Integrar sistemas de **cursos** e vídeos educacionais no futuro

---

## 🧑‍💼 Sobre Renzo Couto e Souza

**Renzo Couto e Souza** é:

- Formado em Rádio, TV e Internet pela Universidade Anhembi/Morumbi
- Tecnólogo em Marketing e Vendas (ETEC - Instituto Paula Souza)
- **Filmmaker, fotógrafo, operador de drone, guimbal, técnico de iluminação e editor**
- Fundador da **Renzo Filmes**, produtora audiovisual especializada
- Apresentador do podcast [**Falte In English**](https://www.youtube.com/@falteinoingles)
- Trabalhou com marcas como **LG**, **GR6 Filmes**, **OGGI Sorvetes**, **Canal OFF/GloboPlay**, entre outras

---

## 📌 Áreas de Atuação

- **📷 Imobiliário**: Vídeos e fotos de alto padrão para locações, vendas e plataformas como Airbnb
- **🚁 Drone**: Captações aéreas para elevar o nível das produções visuais
- **🏢 Institucional**: Materiais promocionais para empresas, produtos e serviços
- **🎞️ Eventos & Casamentos**: Cobertura completa com entrega digital de material editado

---

## 🖥️ Funcionalidades da Plataforma

### 🔓 Área Pública (Website)

- Homepage institucional: Apresentação, missão e destaques do portfólio
- Galeria de Fotos/Vídeos: Com categorias, títulos e descrições customizáveis
- Sobre Renzo: Página dedicada com sua história e áreas de atuação
- Contato: Página com WhatsApp direto, telefone e mapa
- Blog / Propostas (futuro): Publicações, propostas personalizadas, orçamentos

### 🛠️ Painel Administrativo (Admin)

- Login com autenticação (JWT + role admin)
- Gerenciamento completo da galeria
  - Upload de fotos
  - Editar título, descrição, categoria
  - Remover conteúdo
- Gerenciamento de páginas institucionais:
  - Sobre
  - Contato
  - Missão/Valores
- Visualização e organização do portfólio
- (Futuro): Agendamento de sessões, cursos e uploads de vídeos

---

## 📐 Tarefas de Desenvolvimento

### Etapa 1: Estrutura Inicial

- Criar estrutura Next.js 15 com App Router
- Configurar Tailwind, Framer Motion, Radix UI
- Montar layout base com Light/Dark Theme

### Etapa 2: Área Pública

- Criar homepage com chamada e texto institucional
- Criar galeria pública
- Criar página "Sobre" com conteúdo completo sobre Renzo
- Criar página de contato com formulário e botão WhatsApp

### Etapa 3: Painel Admin

- Criar login seguro com role de admin
- Criar CRUD completo de galeria (upload, editar, deletar)
- Criar editor simples para conteúdo das páginas institucionais
- Adicionar dashboard com estatísticas básicas

### Etapa 4: Integrações e Extras

- Implementar sistema de cursos (versão futura)
- Integração com MercadoPago (para orçamentos ou cursos)
- SEO otimizado para nome "Renzo Couto" + termos como "fotografia em São Sebastião"

---

## 🗂️ Estrutura de Galeria (Admin)

Cada item da galeria terá:

| Campo           | Tipo         | Exemplo                                      |
|------------------|--------------|----------------------------------------------|
| Imagem          | Upload       | `/uploads/portfolio1.jpg`                    |
| Título          | Texto        | "Casa Alto Padrão em Maresias"               |
| Descrição       | Texto longo  | "Projeto de captação imobiliária..."         |
| Categoria       | Seleção      | `["Imobiliário", "Drone", "Institucional"]`  |
| Data Publicação | Data         | `2025-07-18`                                 |

---

## 📍 Localização e Contato

📍 Rua Nossa Senhora da Paz, 183c, Centro de São Sebastião – SP  
📞 (11) 93739-4807  
🌐 [YouTube - Falte In English](https://www.youtube.com/@falteinoingles)

---

## ✨ Exemplo Real de Proposta

> “Fotografia de Casamento – 4h de trabalho, captação e edição, entrega digital.  
Valor: R$ 1200,00”  
→ Sistema incluirá futuramente **emissão de propostas e recibos automatizados**.

---

## 📦 Tecnologias Base

| Tecnologia    | Uso                                           |
|---------------|-----------------------------------------------|
| Next.js 15    | Framework principal                           |
| Tailwind CSS  | Estilização responsiva e moderna              |
| Framer Motion | Animações suaves                             |
| Radix UI      | Componentes de UI acessíveis                 |
| JWT + Bcrypt  | Autenticação segura                          |
| SQLite        | Banco de dados leve (pode migrar p/ PostgreSQL) |
| MercadoPago   | Integração de pagamentos PIX                 |

---

## 🧪 Testes & Deploy

- Testes unitários com Jest
- Deploy para Vercel com preview automático
- Integração contínua com GitHub Actions (futuro)

---

## 📝 Conclusão

Este projeto visa consolidar a **identidade digital do Renzo Couto** em uma plataforma moderna, responsiva e completa, valorizando sua trajetória, ampliando seu alcance, profissionalizando seu portfólio e permitindo **gestão autônoma de conteúdos** e **vendas futuras de serviços e cursos**.

---

**🚀 Pronto para elevar sua presença digital com profissionalismo e estilo!**
# couto
