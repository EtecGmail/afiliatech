

```markdown
# AfiliaTech

AfiliaTech é um micro SaaS open-source, criada exclusivamente para curadoria e recomendação personalizada de produtos digitais de tecnologia, afiliados à Hotmart (E talvez outras plataformas do mesmo serviço).

> **Este projeto é voltado exclusivamente para fins estudantis particulares, desenvolvido por mim para praticar e aprimorar conhecimentos em análise, arquitetura e desenvolvimento de software.**

## 🎯 Objetivo do Projeto

O objetivo do projeto é permitir ao usuário encontrar rapidamente cursos, e-books, softwares e outros produtos digitais tecnológicos afiliados à Hotmart, oferecendo recomendações personalizadas baseadas nos interesses individuais dos usuários, garantindo uma experiência altamente eficaz e otimizada para conversão.

## 📚 Motivações e Objetivos

- Praticar habilidades técnicas em **análise e desenvolvimento de software**.
- Aprofundar conhecimentos em **Next.js, React, Tailwind CSS, Node.js e Serverless**.
- Explorar integração eficiente com APIs externas (Hotmart e Supabase).
- Melhorar o entendimento sobre estratégias avançadas de **Conversion Rate Optimization (CRO)**.

## 🚀 Principais Funcionalidades

- 🔹 **Catálogo interativo e responsivo** com filtros inteligentes.
- 🔹 **Integração direta com Hotmart** (API/Webhooks).
- 🔹 **Sistema avançado de recomendação personalizada** baseado nos interesses do usuário.
- 🔹 **Testes A/B, heatmaps e técnicas de copywriting** para otimizar conversões.
- 🔹 Monitoramento completo com **Google Analytics 4, Hotjar e Mixpanel**.

## ⚙️ Stack Tecnológica

- **Front-end**: Next.js, React e Tailwind CSS
- **Back-end/API**: Node.js, Serverless (AWS Lambda, Vercel Functions)
- **Banco de Dados:** PostgreSQL via Supabase
- **Deploy:** Vercel, CI/CD via GitHub Actions
- **Análise e Monitoramento:** Google Analytics 4, Hotjar, Mixpanel/Amplitude

## 🗂️ Estrutura do Projeto

```bash
afiliatech/
├── public/                # Arquivos estáticos (imagens, assets)
├── src/
│   ├── components/        # Componentes React reutilizáveis
│   ├── pages/             # Páginas do Next.js
│   └── styles/            # Estilos e configuração do Tailwind CSS
├── .github/workflows      # Workflows do GitHub Actions
├── next.config.js         # Configuração do Next.js
├── package.json
├── .gitignore
├── LICENSE
└── README.md
```

## ⚙️ Como executar localmente

Clone o projeto:

```bash
git clone https://github.com/EtecGmail/afiliatech.git
cd afiliatech
```

Instale dependências:

```bash
npm install
```

Configure suas variáveis de ambiente criando o arquivo `.env.local`:

```env
HOTMART_API_KEY=sua-chave-api-hotmart
SUPABASE_URL=sua-url-supabase
SUPABASE_ANON_KEY=sua-chave-supabase
```

Rode o projeto localmente:

```bash
npm run dev
```

Abra [http://localhost:3000](http://localhost:3000) no navegador.

## 🚀 CI/CD

Este projeto usa **GitHub Actions** para garantir integração contínua (CI) e deployment contínuo (CD). O workflow automatiza linting, testes, build e deploy (opcional via Vercel):

- Workflow disponível em: [ci-cd.yml](.github/workflows/ci-cd.yml)

## 📌 Infraestrutura, Performance e Segurança

- **Desempenho:** CDN (Vercel/Cloudflare), Lazy loading, compressão Brotli/Gzip
- **SEO Técnico:** Next.js com renderização SSR/ISR, meta tags otimizadas
- **Segurança:** HTTPS com SSL (Let's Encrypt), WAF e proteção DDoS via Cloudflare

## 🤝 Como contribuir

Este projeto é totalmente open source. Para contribuir:

1. Faça um fork do projeto.
2. Crie uma branch específica (`feature/sua-funcionalidade`):
   ```bash
   git checkout -b feature/sua-funcionalidade
   ```
3. Realize commits com seu codinome (ex: `Yuzlkk`):
   ```bash
   git commit -m "Yuzlkk: Descrição da funcionalidade"
   ```
4. Faça push para sua branch:
   ```bash
   git push origin feature/sua-funcionalidade
   ```
4. Abra uma Pull Request no GitHub para revisão.

## 📜 Licença

Este projeto está sob a licença [MIT](LICENSE).


## 🚀 Autor

- **Yuzlkk (Yuri Garcia Pardinho)**
- 📧 Contato: [yurietecg@gmail.com](mailto:yurietecg@gmail.com)


**Disclaimer:** Este projeto foi desenvolvido exclusivamente para prática e aprendizado pessoal em análise e desenvolvimento de software, não possuindo finalidade comercial direta.
```
