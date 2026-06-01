# Tonello &amp; Siqueira — Site institucional

Landing page da **Tonello &amp; Siqueira**, boutique brasileira de _valuation_ para pequenas e médias empresas — laudos técnicos, assessoria na venda de empresas, diagnóstico de valor e perícia judicial.

🔗 **Site:** https://www.tonelloesiqueira.com.br

---

## Sobre o projeto

Página única (`index.html`), estática, sem dependências de build. Todo o conteúdo — HTML, CSS e a foto do sócio — está embutido em um único arquivo, o que torna o site rápido, portátil e fácil de hospedar.

- **Tipografia:** Georgia (serifada), com rótulos em sans-serif do sistema
- **Paleta:** branco, azul `#194E7C` (estrutura) e dourado `#B0863C` (destaques)
- **Seções:** serviços, processo de valuation, sócios, conteúdo (blog), FAQ e contato

---

## Estrutura

```
.
├── index.html      # a página inteira (HTML + CSS + imagem embutidos)
├── CNAME           # domínio customizado (www.tonelloesiqueira.com.br)
├── .nojekyll       # desativa o processamento Jekyll do GitHub Pages
└── README.md       # este arquivo
```

---

## Hospedagem

O site é publicado via **GitHub Pages** com domínio próprio gerenciado pelo **Cloudflare** (DNS + Email Routing).

| Camada | Serviço |
|--------|---------|
| Registro do domínio | Registro.br |
| DNS | Cloudflare |
| Hospedagem | GitHub Pages |
| E-mail | Cloudflare Email Routing |

### Publicação

Qualquer alteração enviada (_commit / push_) para a branch `main` é publicada automaticamente pelo GitHub Pages em poucos minutos.

---

## Editar o site

1. Abra o `index.html`
2. Faça as alterações desejadas (textos, contatos, serviços)
3. Faça _commit_ na branch `main`
4. Aguarde alguns minutos — a alteração entra no ar sozinha

> O endereço de e-mail é montado em tempo de execução (via JavaScript) para evitar coleta automática por _spam bots_. Para alterá-lo, procure os atributos `data-u` (usuário) e `data-d` (domínio) no final do arquivo.

---

## Contato

- **Site:** https://www.tonelloesiqueira.com.br
- **Blog:** https://compraevendadeempresas.wordpress.com
- **E-mail:** contato@tonelloesiqueira.com.br

---

© Tonello &amp; Siqueira. Todos os direitos reservados.
