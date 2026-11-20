# Biblioteca Digital UniFECAF

Primeira interface web da Biblioteca Digital da UniFECAF, desenvolvida para a disciplina **Design Web** a partir do protótipo de baixa fidelidade fornecido pela instituição. O site é feito **somente com HTML e CSS**, é responsivo e segue a identidade visual da UniFECAF.

- **Site publicado:** https://samuel-s-n.github.io/lib_fecaf/biblioteca-unifecaf/
- **Vídeo pitch:** https://youtu.be/rSE7WdbQpEo
- **Relatório:** [relatorio/Relatorio-Biblioteca-Digital-UniFECAF.pdf](relatorio/Relatorio-Biblioteca-Digital-UniFECAF.pdf)

## Seções

Menu · Banner · Sobre a nossa biblioteca · Citação · Nossos livros · As unidades · Contatos · Rodapé

## Destaques

- **Mobile first:** layout com CSS Grid e Flexbox, adaptado para celular, tablet e computador.
- **Filtro de categorias sem JavaScript:** radio buttons + seletor `:has()`.
- **Sinopse expansível** com `<details>` e **item ativo do menu** com `:target`.
- **Acessibilidade:** HTML semântico, contraste WCAG AA, foco visível e link "Pular para o conteúdo".
- **Validação:** W3C sem erros; Lighthouse 100 em Acessibilidade, Boas Práticas e SEO.

## Estrutura

```
biblioteca-unifecaf/
├── index.html
├── css/
│   └── style.css
└── assets/
    └── imagens/
```

## Como rodar localmente

Basta abrir `biblioteca-unifecaf/index.html` no navegador. Para servir como no GitHub Pages:

```bash
python3 -m http.server 8000 --directory biblioteca-unifecaf
```

Depois acesse http://localhost:8000.

## Créditos

- Capas dos livros: [Open Library](https://openlibrary.org)
- Fotos de domínio público: [Openverse](https://openverse.org)
- Fotos das unidades: [UniFECAF](https://www.unifecaf.com.br/post/campus-da-unifecaf-em-taboao-da-serra) e [O Taboanense](https://otaboanense.com.br/evento-inspira-odonto-conecta-alunos-da-unifecaf-a-realidade-do-mercado-odontologico-em-taboao-da-serra/)
- Fontes: Zalando Sans e Roboto ([Google Fonts](https://fonts.google.com))

---

Samuel Solano Neres · R.A. 96037 · CDC 6NA · UniFECAF · Projeto acadêmico
