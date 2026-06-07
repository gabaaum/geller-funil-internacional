# Geller Group — Funil Internacional

Landing page de captação para o serviço de **Expansão Internacional** da Geller Group:
estruturação completa de operação para infoprodutores venderem em mercados de moeda forte
(dólar e euro).

## Identidade visual

- Azul-marinho (`#040C20` → `#1E3D96`) e dourado (`#C49A3C`)
- Tipografia: Playfair Display (títulos) + DM Sans (texto)

## Destaques

- **Hero com slideshow** de cidades internacionais (Nova York, Londres, Paris, Barcelona)
  ocupando todo o lado direito, com transição automática e blend no fundo navy.
- Seções: Problema, Solução, Credibilidade, Para quem é, FAQ (accordion) e Formulário de lead.
- Formulário em React com estado de envio e tela de sucesso.
- Totalmente responsivo (desktop e mobile).

## Estrutura

```
index.html              ← página completa (React via CDN + Babel standalone)
funil-assets/           ← imagens do slideshow do hero (otimizadas)
  hero-newyork.jpg
  hero-london.jpg
  hero-paris.jpg
  hero-barcelona.jpg
```

## Como visualizar

Abra `index.html` no navegador, ou sirva via qualquer servidor estático:

```bash
python3 -m http.server 8000
```

---

© Geller Group · Estratégia Digital e Coprodução
