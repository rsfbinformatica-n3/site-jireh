# 🌐 HotSite Jireh — Captação de Leads

Projeto **Site Jireh** desenvolvido pela **RSFB Informática** para o cliente
**Judson Valentim** (empresa de TI / consultoria). É um **HotSite de captação de
leads** focado em conversão, alimentado por **Google Ads**.

> Não é um site institucional. O objetivo é transformar visitantes de anúncios
> em **leads qualificados** (contatos via WhatsApp + formulário de cadastro) e
> acompanhar o cliente pelos dados captados.

---

## 🎯 Objetivo

1. **Google Ads** convida a pessoa a visitar o HotSite.
2. No HotSite, o visitante pode:
   - **Contratar** → enviar mensagem **via WhatsApp** com o problema que está passando.
   - **Conhecer a estrutura** da empresa.
3. **Planos de serviço / contrato mensal** visíveis para contratação.
4. **Capturar dados** do visitante (formulário cadastral) e
   **acompanhar o cliente** com base nesses dados.

---

## 🧰 O que será usado

### Frontend
- **HotSite de página única** (mobile-first, foco em conversão)
- Base visual **RSFB Informática**, adaptada ao estilo do cliente:
  - Paleta sóbria: **cinza, grafite, preto, cinza claro**
  - Tipografia: **Space Grotesk** + **Manrope**
- Instalação como **PWA** (opcional, para acesso rápido)

### Conversão & Captação
- **Botão / CTA para WhatsApp** (mensagem pré-preenchida)
- **Formulário de captação de leads** (nome, empresa, e-mail, WhatsApp, problema)
- **Plano de contrato mensal** e **planos de serviço**

### Backend & Dados
- **Banco de dados PostgreSQL** para armazenar os leads
- **API** (padrão Supabase: GoTrue + PostgREST) para gravar e consultar leads
- **Acompanhamento de clientes** pelos dados captados (dashboard/consulta)
- **Integração Google Ads** (tag de conversão para medir campanhas)

### Infraestrutura
- **Publicação:** domínio próprio + HTTPS (via VPS/host com Let's Encrypt)
- **GitHub** para versionamento e histórico do projeto
- Serviços críticos (banco/API) **privados**, não expostos diretamente à internet

---

## 🛠 Stack técnica

| Camada | Tecnologia |
| --- | --- |
| Frontend | HTML/CSS/JS ou Next.js (estático) — mobile-first |
| Backend/API | PostgREST + GoTrue (padrão Supabase) |
| Banco | PostgreSQL |
| Auth | Login/formulário próprio + integrações |
| Publicação | Domínio próprio + HTTPS (Let's Encrypt) |
| Versão | Git + GitHub |

---

## 📦 Serviços da empresa (conteúdo do site)

- **Consultoria e treinamento de sistema** — ir até o cliente, entender o cenário
  e treinar a equipe para usar o sistema da melhor forma
- **Consultoria de banco de dados**, relatórios, processos e rotina
- **Quality Assurance (QA)** — analista de testes (validar entrada de dados,
  pagamento, entrega, mudanças de status)
- **Suporte e atendimento**
- **Conserto de placas, eletrônica e recuperação de carcaça**

---

## 🚧 Status

- [x] Entendimento do escopo (áudios do cliente)
- [ ] Aprovação do visual (HotSite em tons de cinza/grafite)
- [ ] Protótipo da página única
- [ ] Formulário + integração WhatsApp
- [ ] Banco de dados e API
- [ ] Integração Google Ads
- [ ] Publicação no domínio
- [ ] Entrega final

---

## 👤 Cliente

- **Dono:** Judson Valentim
- **Perfil:** empresa de TI / consultoria (serviços de sistema, QA, suporte)
- **Necessidade:** captação de leads via Google Ads + acompanhamento pelo dados

---

## 👥 Desenvolvido por

**RSFB Informática** — desenvolvimento, infraestrutura e suporte técnico.

Repositório privado de documentação do projeto. Publicação sujeita a
auditoria de conteúdo (sem segredos / sem dados sensíveis).