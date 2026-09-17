# JP Construção

Site profissional, moderno e responsivo para a empresa de construção civil e acabamento JP Construção.

## Como executar localmente

O site é um arquivo HTML completo (index.html). Abra diretamente no navegador:

```bash
# Linux / Mac
open index.html
# ou
python3 -m http.server 8000
```

Depois acesse `http://localhost:8000/`.

## Como publicar

- Copie o arquivo `index.html` para qualquer hospedagem estática (Netlify, Vercel, GitHub Pages, etc.).
- Atualize `COMPANY` no script do `index.html` ou edite `src/config/company.ts` se for integrar em uma build futura.

## Configuração central

Edite a variável `COMPANY` dentro do `<script>` do `index.html` (linha ~678) para alterar:
- WhatsApp, telefone, e-mail, Instagram
- Cidade, área de atendimento, endereço
- Horário de atendimento

Esse é o único local que precisa ser alterado para atualizar os dados da empresa.

## Seções do site

- Header fixo com menu mobile e botão de orçamento
- Hero com imagem de fundo e CTA duplo
- Serviços (8 cards)
- Diferenciais (6 pontos)
- Sobre a empresa
- Como funciona (timeline)
- Portfólio com filtros e lightbox
- Antes e depois (slider interativo)
- Depoimentos
- Formulário de orçamento (gera mensagem WhatsApp)
- FAQ (acordeão)
- Contato
- Rodapé profissional
- Botão flutuante do WhatsApp
- Barra inferior de conversão mobile

## Otimizações inclusas

- Design responsivo (320px até 1920px)
- Lazy loading de imagens
- Fontes modernas (Inter + Playfair Display)
- Acessibilidade básica (aria, labels, contraste)
- SEO básico (title, meta description, OG, headings)
- Animation respeita `prefers-reduced-motion`
