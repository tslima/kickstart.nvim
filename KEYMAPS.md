# Atalhos desta configuração

> Gerado a partir de `init.lua`. `<leader>` = `<space>`.

## Geral

| Atalho | Modo | Ação |
|---|---|---|
| `<Esc>` | Normal | Limpar highlight de busca (`:nohlsearch`) |
| `<leader>q` | Normal | Abrir lista de diagnósticos (quickfix) |
| `<Esc><Esc>` | Terminal | Sair do modo terminal |

## Navegação entre janelas

| Atalho | Modo | Ação |
|---|---|---|
| `<C-h>` | Normal | Mover foco para a janela à esquerda |
| `<C-l>` | Normal | Mover foco para a janela à direita |
| `<C-j>` | Normal | Mover foco para a janela abaixo |
| `<C-k>` | Normal | Mover foco para a janela acima |

## Busca (Telescope)

| Atalho | Modo | Ação |
|---|---|---|
| `<leader>sh` | Normal | Buscar help tags |
| `<leader>sk` | Normal | Buscar keymaps |
| `<leader>sf` | Normal | Buscar arquivos |
| `<leader>ss` | Normal | Selecionar picker do Telescope |
| `<leader>sw` | Normal/Visual | Buscar palavra sob o cursor |
| `<leader>sg` | Normal | Buscar por grep (live grep) |
| `<leader>sd` | Normal | Buscar diagnósticos |
| `<leader>sr` | Normal | Retomar última busca |
| `<leader>s.` | Normal | Buscar arquivos recentes |
| `<leader>sc` | Normal | Buscar comandos |
| `<leader><leader>` | Normal | Buscar entre buffers abertos |
| `<leader>/` | Normal | Busca fuzzy no buffer atual |
| `<leader>s/` | Normal | Live grep apenas nos arquivos abertos |
| `<leader>sn` | Normal | Buscar arquivos da config do Neovim |

## LSP

| Atalho | Modo | Ação |
|---|---|---|
| `grn` | Normal | Renomear símbolo |
| `gra` | Normal/Visual | Executar code action |
| `grD` | Normal | Ir para declaração |
| `grr` | Normal | Ir para referências (Telescope) |
| `gri` | Normal | Ir para implementação (Telescope) |
| `grd` | Normal | Ir para definição (Telescope) |
| `gO` | Normal | Listar símbolos do documento |
| `gW` | Normal | Listar símbolos do workspace |
| `grt` | Normal | Ir para definição de tipo |
| `<leader>th` | Normal | Alternar inlay hints |

## Git (gitsigns — atalhos locais ao buffer)

| Atalho | Modo | Ação |
|---|---|---|
| `]c` | Normal | Ir para a próxima alteração (hunk) |
| `[c` | Normal | Ir para a alteração (hunk) anterior |
| `<leader>hs` | Normal/Visual | Stage hunk |
| `<leader>hr` | Normal/Visual | Reset hunk |
| `<leader>hS` | Normal | Stage do buffer inteiro |
| `<leader>hR` | Normal | Reset do buffer inteiro |
| `<leader>hp` | Normal | Preview do hunk |
| `<leader>hi` | Normal | Preview do hunk (inline) |
| `<leader>hb` | Normal | Blame da linha atual |
| `<leader>hd` | Normal | Diff contra o índice |
| `<leader>hD` | Normal | Diff contra o último commit |
| `<leader>hQ` | Normal | Quickfix com hunks de todo o repo |
| `<leader>hq` | Normal | Quickfix com hunks do arquivo atual |
| `<leader>tb` | Normal | Alternar blame inline da linha |
| `<leader>tw` | Normal | Alternar diff de palavras |
| `ih` | Operator/Visual | Text object: dentro do hunk |

## Formatação

| Atalho | Modo | Ação |
|---|---|---|
| `<leader>f` | Normal/Visual | Formatar buffer (conform.nvim) |

## Autocomplete (blink.cmp — modo de inserção)

| Atalho | Ação |
|---|---|
| `<C-y>` | Aceitar sugestão selecionada |
| `<Tab>` / `<S-Tab>` | Mover pelo snippet expandido |
| `<C-space>` | Abrir menu / abrir documentação |
| `<C-n>` / `<C-p>` ou `↑` / `↓` | Selecionar item seguinte/anterior |
| `<C-e>` | Esconder o menu |
| `<C-k>` | Alternar signature help |

## Texto: objetos e surround (mini.ai / mini.surround)

| Atalho | Ação |
|---|---|
| `a` + objeto (ex.: `)`, `'`, `w`) | Around: seleciona incluindo o delimitador |
| `i` + objeto | Inside: seleciona só o conteúdo |
| `aa` / `ii` | Around/Inside do próximo objeto |
| `sa` + motion/objeto + delimitador | Adicionar surround |
| `sd` + delimitador | Remover surround |
| `sr` + delimitador antigo + novo | Substituir surround |

## Explorador de arquivos (neo-tree)

| Atalho | Modo | Ação |
|---|---|---|
| `<leader>e` | Normal (global) | Abrir/fechar o explorador |
| `l` | Normal (dentro do neo-tree) | Abrir diretório/arquivo |
| `h` | Normal (dentro do neo-tree) | Fechar o diretório atual |
| `<cr>` | Normal (dentro do neo-tree) | Abrir (padrão do plugin) |
| `<space>` | Normal (dentro do neo-tree) | Expandir/colapsar nó (padrão do plugin) |
