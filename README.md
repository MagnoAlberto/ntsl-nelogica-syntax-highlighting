# Nelogica NTSL Language Support for VS Code / Antigravity IDE

Extensão de suporte completo à linguagem **NTSL (Nelogica Trading System Language)** utilizada na plataforma **Profit (ProfitChart / Nelogica)**.

## ✨ Recursos

- **Realce de Sintaxe Completo (Syntax Highlighting)**:
  - Blocos de parâmetros: `input`, `var`, `begin`, `end`.
  - Séries temporais nativas: `Open`, `Close`, `High`, `Low`, `Volume`, `Date`, `Time`, `CurrentBar`, etc.
  - Funções nativas e de desenho: `LineSegment`, `Plot`, `PaintBar`, `Round`, `ELDate_Consol`, etc.
  - Constantes de cores: `clVerde`, `clVermelho`, `clAmarelo`, `clAzul`, etc.
  - Constantes de estilo: `psSolid`, `psDash`, `tpTopRight`, etc.
  - Tipos primitivos: `Float`, `Integer`, `Boolean`, `String`, `Serie`.
  - Comentários de linha (`//`) e bloco (`{ }`, `(* *)`).
  - Operadores de atribuição (`:=`) e comparação (`<>`, `<=`, etc.).
- **Snippets Úteis**:
  - `input` $\rightarrow$ cria bloco de entrada.
  - `var` $\rightarrow$ cria declaração com tipos.
  - `linesegment` $\rightarrow$ gera chamada completa com todos os parâmetros.
  - `ifelse`, `while`, `for`, `plot`, `paintbar`.
- **Configuração de Linguagem**:
  - Auto-fechamento de parênteses `()`, colchetes `[]`, chaves `{}` e aspas.
  - Dobradura de código (Code Folding) para blocos `begin...end`.

## 📦 Instalação

1. Copie a pasta desta extensão para o diretório de extensões do VS Code ou Antigravity:
   - Antigravity IDE: `~/.antigravity-ide/extensions/`
   - VS Code: `~/.vscode/extensions/`
2. Recarregue a janela (`Ctrl + Shift + P` $\rightarrow$ `Developer: Reload Window`).

## 📄 Licença
MIT
