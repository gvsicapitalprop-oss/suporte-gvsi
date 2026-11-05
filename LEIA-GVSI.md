# Suporte GVSI

Versão do [RustDesk](https://github.com/rustdesk/rustdesk) 1.5.1 com a identidade da GVSI Capital Prop,
usada pelo suporte da comunidade para acessar o computador de alunos, com autorização deles.

O RustDesk é software livre (licença AGPL-3.0, arquivo `LICENCE`). Este repositório é público para
cumprir essa licença: o código-fonte de todas as mudanças está aqui.

## O que muda em relação ao RustDesk original

- Nome do programa: Suporte GVSI (nome interno `SuporteGVSI`, link `suportegvsi://`).
- Servidor de conexão próprio da GVSI e a chave dele embutidos (`libs/hbb_common/src/config.rs`).
- Ícones, logo (claro e escuro) e cor principal da GVSI.
- `libs/hbb_common` deixou de ser submódulo para levar essas mudanças junto.
- Compilação só para Windows x64 (`.github/workflows/gvsi-windows.yml`); o programa sai como artefato
  `suporte-gvsi-windows-x64` (Suporte-GVSI.exe).

Todos os créditos do programa são do projeto RustDesk e de seus colaboradores.
