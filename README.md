# Engenhub – site (Linha C · Zirconium)

Site estático multipágina:

| Arquivo | Conteúdo |
|---|---|
| `index.html` | Página inicial: plataformas, IA, BI, nuvem, preços, simulador e contato |
| `aras.html` | Detalhamento Aras Innovator (PLM) |
| `dolibarr.html` | Detalhamento Dolibarr (ERP) |
| `espocrm.html` | Detalhamento EspoCRM (CRM) |
| `openproject.html` | Detalhamento OpenProject (Projetos) |
| `assets/engenhub.css` | Estilos compartilhados |
| `img/` | Telas das plataformas (créditos nas legendas) |

Cada página de sistema traz: para quem é, módulos, processo de ponta a ponta, telas, integrações, IA e BI, infraestrutura recomendada, cronograma de implantação, investimento e dúvidas. Os botões "Agendar diagnóstico" abrem o formulário da página inicial com o interesse já selecionado (`index.html?interesse=…#orcamento`).

## Publicar no GitHub Pages
1. Envie todo o conteúdo desta pasta para a raiz de um repositório (ex.: `engenhub-site`).
2. Em **Settings › Pages**, escolha *Deploy from a branch*, branch `main`, pasta `/ (root)`.
3. Domínio próprio (opcional): arquivo `CNAME` com `engenhub.com.br`.

## Formulário
FormSubmit → **contato@zirconiumlabs.com** (POST multipart; anexos compactados em .zip, limite de 10 MB). No primeiro envio do domínio publicado, confirme o e-mail de ativação do FormSubmit.

Aras Innovator, Dolibarr, EspoCRM e OpenProject são marcas de seus titulares; as telas são ilustrativas.
