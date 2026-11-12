# Nexo Público

**Acompanhamento dos projetos de lei da Câmara Municipal de Florianópolis, em linguagem simples.**

[Abrir o painel](https://gustavo-marques-da-silva.github.io/nexo-publico/) | [Portfólio](https://gustavo-marques-da-silva.github.io/Portfolio/)

> **Versão de demonstração.** Os projetos, vereadores e datas do painel são fictícios. Servem para validar a experiência antes da integração com os dados reais da Câmara.

---

## O problema

Acompanhar o que a Câmara Municipal decide exige ler documentos longos, espalhados em sistemas diferentes e escritos em linguagem técnica. Por isso, cidadãos, jornalistas, organizações da sociedade civil e empresas raramente sabem o que está em votação e como isso afeta a cidade.

## A solução

Um painel que mostra, para cada projeto de lei:

- **Em que etapa está:** protocolado, em comissão, pronto para plenário, aprovado ou arquivado.
- **Há quanto tempo tramita**, em dias.
- **O que muda na cidade**, em um resumo curto em linguagem simples.
- **A linha do tempo da tramitação.**

Também traz uma visão geral, com projetos por etapa, por tema e tempo médio até a decisão, e filtros por tema, etapa, autor e busca por palavra.

## Status

| Versão | O que tem | Situação |
|---|---|---|
| v0.1 | Painel com 24 projetos fictícios, filtros, gráficos e linha do tempo | Publicada |
| v0.2 | Dados reais coletados do site da Câmara Municipal de Florianópolis | Próxima |
| v0.3 | Resumos gerados por IA a partir do texto integral de cada projeto | Planejada |
| v0.4 | Perguntas em linguagem natural ("o que foi aprovado sobre mobilidade este ano?") | Planejada |
| v0.5 | Alertas por tema ou bairro | Planejada |

## Onde entra a IA

- **Resumo:** transforma o texto do projeto em duas ou três frases em linguagem simples.
- **Classificação:** identifica o tema e os bairros afetados.
- **Perguntas e respostas:** responde perguntas sobre os projetos, sempre com link para o documento original.

Princípio: **todo resumo aponta para a fonte oficial.** A IA facilita a leitura, mas não substitui o documento.

## Tecnologia

Um único `index.html` com HTML, CSS e JavaScript, sem dependências e sem servidor. Publicado com GitHub Pages. Os dados fictícios estão no próprio arquivo, na constante `PLS`.

Para rodar localmente, basta abrir o `index.html` no navegador.

## Autor

**Gustavo Marques**, administrador pela UFSC.
[Portfólio](https://gustavo-marques-da-silva.github.io/Portfolio/) | [GitHub](https://github.com/gustavo-marques-da-silva)

## Licença

[MIT](LICENSE)
