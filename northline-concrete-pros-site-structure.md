# Northline Concrete Pros — Estrutura do Site & Brief de Conteúdo

**Domínio:** northlineconcretepros.com
**Objetivo:** SEO local para serviços de concreto em Davenport / Quad Cities (IA/IL)
**Stack sugerida:** Astro (static export) — leve, rápido, ótimo para SEO, fácil de hospedar no Cloudflare Pages
**Hospedagem:** Cloudflare Pages (grátis) | **Domínio:** Namecheap → nameservers Cloudflare
**Formulário:** Formspree (free tier) ou Basin

---

## 1. Sitemap

```
/                                    Home
/about/                              About
/services/                           Services (hub)
  /services/concrete-driveways/
  /services/concrete-patios/
  /services/concrete-repair/
  /services/stamped-concrete/
  /services/sidewalk-installation/
/service-areas/                      Service Areas (hub)
  /service-areas/davenport/
  /service-areas/bettendorf/
  /service-areas/moline/
  /service-areas/rock-island/
/contact/
```

Sugestões opcionais (não obrigatórias no MVP):
- `/gallery/` — fotos antes/depois de projetos
- Seção de depoimentos na Home (evita criar página nova)
- `/blog/` — só se houver disposição de publicar com regularidade (bom para SEO a médio prazo)

---

## 2. Estrutura de conteúdo por página

Cada página abaixo segue o padrão: **Title Tag | Meta Description | H1 | Seções | Palavras-chave locais**

### Home (`/`)
- **Title:** Concrete Contractor Davenport IA | Northline Concrete Pros
- **Meta description:** Connect with local concrete professionals serving Davenport, Bettendorf, Moline & Rock Island. Driveways, patios, stamped concrete & repair. Free estimates.
- **H1:** Quad Cities' Trusted Concrete Contractor
- **Seções:**
  1. Hero com CTA (telefone + "Get a Free Quote")
  2. Faixa de confiança (licenciado, segurado, anos de experiência, área atendida)
  3. Serviços em destaque (cards linkando para /services/*)
  4. Como funciona o matching service (solicitação, encaminhamento e contato do profissional)
  5. Áreas atendidas (mapa ou lista linkando para /service-areas/*)
  6. Depoimentos de clientes
  7. Galeria rápida (3-6 fotos de projetos, se houver)
  8. CTA final + formulário de contato resumido
- **Palavras-chave:** concrete contractor Davenport IA, Quad Cities concrete company, concrete driveway installation

### About (`/about/`)
- **Title:** About Northline Concrete Pros | Quad Cities Concrete Experts
- **Meta description:** Learn how Northline Concrete Pros helps Quad Cities homeowners connect with local concrete professionals for free estimates.
- **H1:** About Northline Concrete Pros
- **Seções:** Objetivo do serviço, processo de matching, regiões atendidas, ausência de custo e obrigação para solicitar uma estimativa
- **Nota importante:** descreva a Northline de forma transparente como um matching service. Não atribua à Northline equipe de obra, licenças, seguro, experiência, garantias, avaliações ou projetos executados.

### Services — Hub (`/services/`)
- **Title:** Concrete Services in Davenport & Quad Cities | Northline
- **H1:** Our Concrete Services
- **Seções:** Grid com os 5 serviços, cada card linkando para a página específica, com 1-2 linhas de descrição

#### Concrete Driveways (`/services/concrete-driveways/`)
- **Title:** Concrete Driveway Installation Davenport IA | Northline Concrete Pros
- **Meta description:** Durable, custom concrete driveways built to last Iowa winters. Serving Davenport, Bettendorf & the Quad Cities. Get a free estimate today.
- **H1:** Concrete Driveway Installation
- **Seções:** Benefícios do concreto vs asfalto, processo de instalação, opções de acabamento, FAQ (custo médio, tempo de cura, manutenção no clima de Iowa), CTA
- **Palavras-chave:** concrete driveway Davenport, driveway contractor Quad Cities, concrete driveway installation cost

#### Concrete Patios (`/services/concrete-patios/`)
- **Title:** Concrete Patio Installation Quad Cities | Northline Concrete Pros
- **H1:** Custom Concrete Patios
- **Seções:** Estilos disponíveis, integração com paisagismo, processo, FAQ, CTA
- **Palavras-chave:** concrete patio installation Davenport, backyard patio contractor Quad Cities

#### Concrete Repair (`/services/concrete-repair/`)
- **Title:** Concrete Repair & Resurfacing Davenport IA | Northline
- **H1:** Concrete Repair & Resurfacing
- **Seções:** Sinais de que o concreto precisa de reparo, tipos de reparo (rachaduras, desnível, lascas), diferença entre reparo e substituição, FAQ, CTA
- **Palavras-chave:** concrete repair Davenport, concrete crack repair Quad Cities, driveway resurfacing

#### Stamped Concrete (`/services/stamped-concrete/`)
- **Title:** Stamped Concrete Contractor Davenport IA | Northline Concrete Pros
- **H1:** Stamped & Decorative Concrete
- **Seções:** Padrões e cores disponíveis, comparação com pedra natural (custo), casos de uso (patio, calçada, entrada), galeria de padrões, CTA
- **Palavras-chave:** stamped concrete Davenport, decorative concrete Quad Cities

#### Sidewalk Installation (`/services/sidewalk-installation/`)
- **Title:** Concrete Sidewalk Installation Davenport IA | Northline
- **H1:** Sidewalk & Walkway Installation
- **Seções:** Residencial vs comercial, requisitos municipais (se aplicável em Davenport/Bettendorf), processo, CTA
- **Palavras-chave:** concrete sidewalk installation Quad Cities, walkway contractor Davenport

### Service Areas — Hub (`/service-areas/`)
- **Title:** Concrete Contractor Service Areas | Quad Cities
- **H1:** Proudly Serving the Quad Cities
- **Seções:** Mapa da região, lista das 4 cidades linkando para páginas próprias, nota sobre outras cidades próximas atendidas mediante contato

#### Páginas de cidade (Davenport, Bettendorf, Moline, Rock Island)
Mesma estrutura para as 4, adaptando nome da cidade:
- **Title:** Concrete Contractor in [Cidade], IA/IL | Northline Concrete Pros
- **Meta description:** Connect with local concrete professionals serving [Cidade]. Driveways, patios, repair & more. Free estimates.
- **H1:** Concrete Contractor in [Cidade]
- **Seções:** Breve intro local (bairros/pontos de referência, se souber), lista de serviços oferecidos ali com links, depoimento de cliente local (se houver), CTA
- **Nota SEO:** Essas páginas precisam ter conteúdo genuinamente diferente entre si (não apenas trocar o nome da cidade) — mencione detalhes reais de cada cidade para evitar penalização por conteúdo duplicado.
- **Palavras-chave:** concrete contractor [Cidade], [Cidade] driveway installation

### Contact (`/contact/`)
- **Title:** Contact Northline Concrete Pros | Free Estimate
- **Meta description:** Get a free concrete estimate in the Quad Cities. Call, email, or fill out our contact form — Northline Concrete Pros responds fast.
- **H1:** Get Your Free Estimate
- **Seções:** Formulário (nome, telefone, e-mail, cidade, tipo de serviço, mensagem), telefone clicável, e-mail, horário de atendimento, área de cobertura, mapa incorporado (opcional)

---

## 3. Checklist técnico de implementação

### Estrutura do projeto (Claude Code)
- [ ] Inicializar projeto Astro (`npm create astro@latest`)
- [ ] Configurar layout base compartilhado (header, footer, nav)
- [ ] Criar componentes reutilizáveis: Hero, ServiceCard, Testimonial, CTA, ContactForm
- [ ] Implementar as 12 páginas listadas acima
- [ ] Adicionar sitemap.xml e robots.txt (Astro tem integração `@astrojs/sitemap`)
- [ ] Adicionar schema.org markup (LocalBusiness) na Home e páginas de cidade
- [ ] Otimizar imagens (formato WebP, lazy loading)
- [ ] Testar responsividade mobile (a maioria das buscas locais é via celular)

### GitHub
- [ ] Criar repositório (público ou privado)
- [ ] Subir o código do projeto Astro

### Cloudflare Pages
- [ ] Criar/entrar na conta Cloudflare
- [ ] Conectar o repositório GitHub
- [ ] Configurar build command (`npm run build`) e output dir (`dist`)
- [ ] Fazer o primeiro deploy e validar preview URL

### Domínio (Namecheap → Cloudflare)
- [ ] Adicionar o site no Cloudflare (isso gera os nameservers do Cloudflare)
- [ ] Trocar os nameservers na Namecheap para os da Cloudflare
- [ ] Aguardar propagação DNS (pode levar algumas horas)
- [ ] Adicionar northlineconcretepros.com como custom domain no Cloudflare Pages

### HTTPS
- [ ] Confirmar SSL/HTTPS ativo automaticamente (gratuito via Cloudflare)

### Formulário de contato
- [ ] Criar conta no Formspree (ou Basin)
- [ ] Conectar o endpoint do formulário na página /contact/
- [ ] Testar envio e confirmar recebimento do e-mail
- [ ] MVP alternativo: botão de ligar + mailto: + formulário simples

---

## 4. Observações para evitar "cara de site genérico de leads"
- Use imagens com licença adequada e não apresente fotos de banco como projetos realizados pela Northline
- Escreva conteúdo específico para cada cidade, não apenas find-and-replace do nome
- Inclua somente informações verificadas sobre o funcionamento do matching service
- Evite textos de stock tipo "we are the best concrete company in town" sem sustentação
- Adicione número de telefone e CTA visíveis em todas as páginas
