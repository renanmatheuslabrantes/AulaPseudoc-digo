# 📘 Aula Completa de Pseudocódigo

Uma aula interativa de pseudocódigo feita em HTML puro — sem dependências, sem frameworks, abre direto no navegador.

---

## 📋 Sobre o Projeto

Página educacional estática cobrindo do zero ao avançado em pseudocódigo no padrão brasileiro (Visualg / Portugol). Inclui teoria, sintaxe, estruturas de controle e 10 exercícios práticos com soluções interativas.

---

## 🚀 Como Usar

Nenhuma instalação necessária. Basta abrir o arquivo no navegador:

```bash
# Clone ou baixe o arquivo
# Depois, abra diretamente:
double-click aula_pseudocodigo.html

# Ou via terminal:
open aula_pseudocodigo.html        # macOS
start aula_pseudocodigo.html       # Windows
xdg-open aula_pseudocodigo.html    # Linux
```

> ⚠️ Requer conexão com internet apenas para carregar as fontes (Google Fonts). O conteúdo funciona offline normalmente.

---

## 📂 Estrutura do Arquivo

```
aula_pseudocodigo.html
│
├── <style>          → Todo o CSS (tema dark, variáveis, animações)
├── <nav>            → Menu de navegação fixo com scroll suave
├── <section #oq-e>  → O que é pseudocódigo
├── <section #ferramentas> → Ferramentas recomendadas
├── <section #instalacao>  → Instalação do Visualg passo a passo
├── <section #sintaxe>     → Tipos, operadores, entrada/saída
├── <section #estruturas>  → SE, PARA, ENQUANTO, REPITA, Vetores, Funções
├── <section #fluxo>       → Fluxograma vs Pseudocódigo
├── <section #exercicios>  → 10 exercícios práticos interativos
└── <script>         → Accordion dos exercícios + toggle de soluções
```

---

## 📚 Conteúdo da Aula

### Seções teóricas

| # | Seção | O que cobre |
|---|-------|-------------|
| 01 | O que é Pseudocódigo | Conceito, analogia, 4 motivos para aprender |
| 02 | Ferramentas | Visualg 3.0, Portugol Studio, Portugol Webstudio |
| 03 | Instalação | Passo a passo do Visualg + estrutura básica |
| 04 | Sintaxe | Tipos de dados, operadores, entrada/saída |
| 05 | Estruturas de Controle | SE, ESCOLHA, ENQUANTO, PARA, REPITA, Vetores, Funções |
| 06 | Fluxograma | Comparação visual fluxograma × pseudocódigo |

### Exercícios práticos

| # | Exercício | Nível | Conceitos |
|---|-----------|-------|-----------|
| 01 | Área do Retângulo | 🟢 Fácil | Variáveis, operadores |
| 02 | Par ou Ímpar | 🟢 Fácil | Condicional, MOD |
| 03 | Tabuada Completa | 🟢 Fácil | Laço PARA |
| 04 | Média com Situação | 🟡 Médio | Condicional aninhado |
| 05 | Contador de Pares | 🟡 Médio | Laço + condicional |
| 06 | Fatorial | 🟡 Médio | Laço acumulador |
| 07 | Maior Valor em Vetor | 🟡 Médio | Vetor + laço |
| 08 | Calculadora com Menu | 🟡 Médio | ESCOLHA, REPITA |
| 09 | Sequência Fibonacci | 🔴 Difícil | Laço, variáveis auxiliares |
| 10 | Bubble Sort | 🔴 Difícil | Vetor, laço duplo, troca |

---

## 🛠️ Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — tema dark, CSS variables, animações, grid, flexbox
- **JavaScript vanilla** — accordion dos exercícios e toggle de soluções
- **Google Fonts** — `JetBrains Mono` (código) + `Space Grotesk` (texto)

Sem frameworks. Sem bibliotecas externas. Sem bundler. Um único arquivo `.html`.

---

## 🎨 Design

- Tema escuro (`#0a0c0f`) com accent em ciano (`#00e5ff`) e roxo (`#7c3aed`)
- Grid animado no hero
- Blocos de código com syntax highlighting manual via `<span>` + classes CSS
- Cards interativos com hover e transições suaves
- Layout responsivo (mobile-first via `clamp()` e `auto-fit`)

---

## 🔧 Ferramentas para Executar os Algoritmos

Os códigos de pseudocódigo da aula seguem a sintaxe do **Visualg**. Para executá-los:

| Ferramenta | Plataforma | Link |
|-----------|-----------|------|
| **Visualg 3.0** | Windows | [sourceforge.net/projects/visualg30](https://sourceforge.net/projects/visualg30/) |
| **Portugol Studio** | Windows / Mac / Linux | [univali-lite.github.io/Portugol-Studio](https://univali-lite.github.io/Portugol-Studio/) |
| **Portugol Webstudio** | Navegador (online) | [dgadelha.github.io/Portugol-Webstudio](https://dgadelha.github.io/Portugol-Webstudio/) |

---

## 📄 Licença

Livre para uso educacional. Sinta-se à vontade para adaptar, distribuir e usar em aulas.
