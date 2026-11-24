# neoforge-1.21.1-pack

Modpack **NeoForge 1.21.1** (loader `21.1.265`) com 138 mods, empacotado em um `.mrpack`.
Servidor e cliente usam o mesmo conjunto.

## Jogar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/neoforge-1.21.1-pack.git
   ```
2. No launcher (Modrinth App, Prism, SKLauncher): **Modpacks → Import / Adicionar de arquivo**
   → `neoforge-1.21.1-1.0.0.mrpack`.
3. O launcher instala NeoForge 21.1.265 e os 138 mods (119 vêm do CDN do Modrinth, 19 vão dentro do pacote).
4. Entre no servidor.

## Conteúdo

| arquivo | o que é |
|---|---|
| `neoforge-1.21.1-1.0.0.mrpack` | o modpack |
| `mods-lista.txt` | lista legível dos 138 mods com versão |
| `mods-so-cliente.txt` | 15 jars que não existem em servidor dedicado (Sodium, Zoom, BetterF3…) |

`config/` e `defaultconfigs/` já vão dentro do `.mrpack` (overrides).

## Requisitos

- Java 21
- ~8 GB de RAM para cliente e servidor juntos, se rodarem na mesma máquina
- NeoForge 21.1.x no servidor (testado em 21.1.265 e 21.1.267)

## Aviso

Os 19 jars embutidos em `overrides/` são de terceiros (ProjectE, Croptopia, Thut, e mods
custom deste pack). As licenças de cada mod continuam valendo para redistribuição.
