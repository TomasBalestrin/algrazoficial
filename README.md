# Algraz Engenharia

Site institucional de página única. HTML, CSS e JavaScript puros, sem dependências
e sem etapa de build: basta servir a pasta.

## Rodar localmente

```sh
python3 -m http.server 8899
```

Abra <http://localhost:8899>.

## Estrutura

| Arquivo | Conteúdo |
|---|---|
| `index.html` | Todas as seções da página |
| `styles.css` | Estilos e paleta (variáveis CSS no `:root`) |
| `script.js` | Menu mobile, lightbox, accordion do FAQ e envio do formulário |
| `assets/hero-algraz/` | Banner do primeiro bloco (JPEG + WebP) |
| `assets/projetos-algraz/` | Fotos do portfólio, organizadas por projeto (WebP) |
| `assets/logo*.png`, `assets/marca*.png` | Herdados do template original — ainda não há logo da Algraz |
| `projetos/` | Fotos originais enviadas pelo cliente (fonte, não usadas diretamente pelo site) |

## Ainda a preencher / revisar

- **Logo da Algraz** — hoje o cabeçalho usa só o nome em texto; falta o logo real
- **Foto do Caio Grotti** — não incluída; a seção "Quem somos" está sem retrato
- **Imagem de hero** — usando `banner.png` (fornecido) como referência de ambiente de alto padrão; confirmar se é o hero definitivo
- **Textos de depoimentos, FAQ e pacotes** — vieram da copy fornecida pelo cliente; revisar preços e condições reais dos pacotes (Starter/Smart/Handover/Premium) antes de publicar
- **CAU / CNPJ / endereço** — usando os dados da copy (CAU A53718-7, CNPJ 61.508.199/0001-58, Av. dos Parques 252, Alphaville); confirmar

O WhatsApp já está configurado: `5511999034048`, definido em `script.js` e nos
links do `index.html`.

## Formulário de contato

Não envia e-mail. Ele monta a mensagem e abre o WhatsApp com o texto pronto,
por isso não exige servidor. Para receber por e-mail, seria preciso plugar um
serviço externo.
