# 🦎 Camaleão Brazuca

> Jogo de dedução social inspirado em *The Chameleon* (Big Potato Games), totalmente adaptado para a cultura brasileira — com tópicos, palavras e referências do Brasil.

![Camaleão Brazuca](https://img.shields.io/badge/jogo-dedu%C3%A7%C3%A3o%20social-1b6b3a?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHRleHQgeT0iMjAiIGZvbnQtc2l6ZT0iMjAiPvCfpq48L3RleHQ+PC9zdmc+)
![Jogadores](https://img.shields.io/badge/jogadores-3%20a%208-f5c800?style=for-the-badge)
![Idioma](https://img.shields.io/badge/idioma-Portugu%C3%AAs%20(BR)-009c3b?style=for-the-badge)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue?style=for-the-badge)

---

## 📖 Sobre o Jogo

**Camaleão Brazuca** é uma versão brasileira do jogo de dedução social *The Chameleon*. Um jogador secreto — o **Camaleão** — não sabe a palavra secreta da rodada e precisa se disfarçar entre os outros jogadores, dizendo uma palavra convincente sem se trair.

Os demais jogadores precisam descobrir quem é o Camaleão antes que ele adivinhe a palavra secreta e escape!

---

## 🎮 Como Jogar

### Preparação
1. Embaralhe os **cartões de código** (incluindo o cartão do Camaleão 🦎) e distribua um para cada jogador, **virados para baixo**
2. Vire uma **carta de tópico** no centro da mesa
3. Um jogador (o dealer) **rola os dois dados de 12 faces**

### Descobrindo a Palavra Secreta
- Todos os jogadores (exceto o Camaleão) consultam seu **cartão de código**
- Use o **Dado 1 → Linha** e o **Dado 2 → Coluna** para encontrar um número na grade 12×12
- Esse número corresponde a uma das **16 palavras** da carta de tópico — essa é a palavra secreta!
- O **Camaleão** não sabe a palavra secreta e precisa blefar

### A Rodada
- Começando pelo dealer, cada jogador diz **uma única palavra** relacionada à palavra secreta
- O Camaleão deve inventar algo convincente sem revelar que não sabe a palavra

### Votação
- Após todos falarem, os jogadores discutem brevemente
- **Todos apontam simultaneamente** para quem acham que é o Camaleão
- O jogador mais votado revela sua carta

### Resultado
| Situação | Resultado |
|----------|-----------|
| Camaleão **não é descoberto** | 🦎 Camaleão ganha **2 pontos** |
| Camaleão é descoberto e **adivinha** a palavra | 🦎 Camaleão ganha **1 ponto** |
| Camaleão é descoberto e **erra** a palavra | 👥 Cada outro jogador ganha **2 pontos** |

### Vitória
O primeiro jogador a atingir **5 pontos** vence o jogo!

---

## 🃏 Componentes

| Componente | Quantidade | Descrição |
|---|---|---|
| 🗂️ Cartas de Tópico | 40 | Cada carta tem 16 palavras numeradas de 1 a 16 |
| 🔢 Cartões de Código | 7 | Grade 12×12 com números 1–16, idênticos entre si |
| 🦎 Cartão do Camaleão | 1 | Igual aos de código, mas com 🦎 cobrindo o centro |
| 📖 Carta de Regras | 1 | Resumo das regras para consulta rápida |
| 🎲 Dados | 2 | Dados de 12 faces (d12) |

> **Dica:** Os cartões de código e o cartão do Camaleão têm o **verso idêntico** — impossível distingui-los virados para baixo. As cartas de tópico têm verso **azul escuro** (bandeira brasileira), enquanto os cartões de código têm verso **verde escuro**.

---

## 🗂️ Tópicos Incluídos

O jogo conta com **40 tópicos** cuidadosamente selecionados, equilibrando cultura brasileira e temas universais:

**🇧🇷 Cultura Brasileira**
Comidas Brasileiras · Frutas Tropicais · Bebidas · Fast Food · Esportes Brasileiros · Jogadores de Futebol · Times de Futebol · Gêneros Musicais · Artistas Brasileiros · Novelas Brasileiras · Personagens de Novela · Filmes Brasileiros · Shows Infantis Clássicos · Estados Brasileiros · Cidades Famosas · Pontos Turísticos · Biomas Brasileiros · Festas Populares · Lendas e Folclore · Animais do Brasil · Datas Comemorativas · Turma da Mônica · Brincadeiras de Infância

**🌍 Temas Universais**
Doces & Sobremesas · Jogos de Tabuleiro · Animais · Filmes · Personalidades Históricas · Profissões · Instrumentos Musicais · Países do Mundo · Países do Mundo 2 · Séries de TV · Brinquedos Clássicos · Contos de Fada · Bandas de Rock · Estrelas do Pop · Ferramentas · Frutas · Personagens da Disney

---

## 🖨️ Como Imprimir

Este repositório contém um único arquivo HTML autocontido que serve como **editor e gerador de cartas para impressão**.

### Passo a Passo

1. **Baixe** o arquivo `camaleao-brazuca.html`
2. **Abra** no seu navegador (Chrome ou Edge recomendados)
3. Navegue até a aba **🖨️ Imprimir**
4. Use os botões de toggle para selecionar quais seções imprimir
5. Clique em **🖨️ Imprimir / PDF** e salve como PDF ou imprima diretamente

### Dicas de Impressão
- **Papel:** A4, gramatura 180g+ para melhor resultado
- **Tamanho das cartas:** 63×88mm (padrão internacional de cartas)
- **Frente/Verso:** Imprima as cartas e os versos separadamente, depois cole as folhas
- **Cores:** Ative "Imprimir gráficos de fundo" nas configurações do navegador

---

## ✏️ Como Editar

O sistema é totalmente editável sem precisar de servidor ou instalação.

### Editar pela Interface
1. Abra o HTML no navegador
2. Use a aba **📋 Tópicos** para editar palavras ou adicionar novas cartas
3. Use a aba **📖 Regras** para ajustar o texto das regras
4. Clique em **💾 Exportar JSON** para salvar suas alterações

### Editar pelo JSON
1. Vá até a aba **🛠️ Editor JSON**
2. Edite diretamente o JSON completo do jogo
3. Clique em **✅ Aplicar JSON** para confirmar
4. Use **💾 Exportar .json** para salvar backup

### Estrutura do JSON

```json
{
  "cards": [
    {
      "id": 1,
      "topico": "Comidas Brasileiras",
      "palavras": [
        "Feijoada", "Coxinha", "Pão de queijo", "Brigadeiro",
        "Tapioca", "Churrasco", "Acarajé", "Escondidinho",
        "Bolinho de bacalhau", "Empadão", "Arroz carreteiro", "Pirarucu",
        "Torta capixaba", "Frango com quiabo", "Barreado", "Sarapatel"
      ]
    }
  ],
  "rules": {
    "objetivo": "...",
    "rodada": "...",
    "votacao": "...",
    "camaleao_pego": "...",
    "pontuacao": "item 1 | item 2 | item 3",
    "vence": "...",
    "dados": "...",
    "jogadores": "..."
  }
}
```

> ⚠️ Cada carta deve ter **exatamente 16 palavras**. O campo `pontuacao` usa `|` para separar os itens que aparecem na carta de regras.

---

## 🎲 Mecânica dos Cartões de Código

Os cartões usam uma grade **12×12 = 144 posições**, preenchida com os números de 1 a 16, cada um aparecendo exatamente **9 vezes** — garantindo probabilidade igual para toda palavra do tópico.

```
Dado 1 (d12) → Linha  (1–12)
Dado 2 (d12) → Coluna (1–12)
Número encontrado → Posição na carta de tópico
```

Todos os jogadores têm **cartões idênticos**. O segredo não está em cartões diferentes — está em que o Camaleão **não recebe cartão de código**, recebendo em vez disso o cartão especial com o 🦎 no centro.

---

## 🔧 Variantes e Regras Especiais

| Nº de Jogadores | Regra Especial |
|---|---|
| 3 jogadores | O Camaleão tem **2 tentativas** para adivinhar a palavra se for pego |
| 4–8 jogadores | Regras normais |

---

## 📁 Estrutura do Repositório

```
camaleao-brazuca/
│
├── camaleao-brazuca.html   # Arquivo principal — editor + impressão
└── README.md               # Este arquivo
```

---

## 🙏 Créditos

- **Jogo original:** *The Chameleon* por Rikki Tahta — [Big Potato Games](https://bigpotato.com)
- **Versão brasileira:** Desenvolvida com carinho para jogar com amigos e família 🇧🇷
- **Tópicos e palavras:** Selecionados para refletir a cultura e o cotidiano brasileiro

---

## 📄 Licença

Este projeto é distribuído sob a licença **MIT**. Sinta-se livre para usar, modificar e compartilhar — mas lembre-se de que o jogo original *The Chameleon* é propriedade intelectual da Big Potato Games.

---

<div align="center">
  <strong>Feito com 🦎 e muito carinho para o Brasil</strong><br/>
  <em>Quem é o Camaleão?</em>
</div>
