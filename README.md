# Página de Cordel Moderno

Página editorial que apresenta o cordel "Cordel Moderno", de Milton Duarte, alternando blocos com
imagem fixa ao fundo e blocos claros, com tipografia pensada para leitura longa.

[![Demo](https://img.shields.io/badge/demo-online-22d3ee?style=flat-square)](https://nicolasmoreiraferreira.github.io/projeto-cordel/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**[Acessar a demonstração](https://nicolasmoreiraferreira.github.io/projeto-cordel/)**

---

## Sobre o projeto

O desafio deste projeto não é de layout, e sim de **leitura**. Texto poético em blocos alternados
precisa ser agradável de percorrer: contraste adequado, largura de linha controlada, entrelinha
generosa e um efeito de profundidade que não atrapalhe o texto.

As estrofes aparecem intercaladas entre seções com imagem de fundo fixa e seções de fundo claro,
criando um ritmo visual ao longo da página.

## Decisões técnicas

- **Efeito parallax apenas com CSS**, usando imagem de fundo fixa. Isso evita JavaScript e o custo
  de performance de reposicionar elementos a cada evento de rolagem.
- **Blocos sem altura fixa.** A altura é definida pelo conteúdo, de modo que a página continua
  legível se o texto for editado ou se a fonte carregar com largura diferente.
- **Largura de linha limitada.** Linhas muito longas cansam a leitura; o texto é mantido em uma
  medida confortável, com largura máxima.
- **Contraste controlado** entre as estrofes e os fundos, alternando texto claro sobre imagem e
  texto escuro sobre fundo claro.
- **Tipografia com peso e estilo distintos** para destacar os versos em relação ao título.

## Estrutura

```
projeto-cordel/
├── index.html          # Estrutura das estrofes e seções
├── estilo/
│   └── style.css       # Tipografia, seções e efeito parallax
├── imagens/            # Imagens de fundo das seções
└── cordel-moderno.txt  # Texto original utilizado
```

## Como executar

```bash
git clone https://github.com/nicolasmoreiraferreira/projeto-cordel.git
cd projeto-cordel
# Abra o arquivo index.html no navegador
```

Ou acesse a [demonstração publicada](https://nicolasmoreiraferreira.github.io/projeto-cordel/).

## O que pratiquei

- Efeito parallax com `background-attachment`
- Tipografia aplicada à legibilidade de texto longo
- Composição editorial com alternância de fundos
- Publicação no GitHub Pages

## Licença

Distribuído sob a licença MIT. Consulte [LICENSE](LICENSE).
