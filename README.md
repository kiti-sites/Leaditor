# Leaditor

Editor de texto em blocos independente, offline, sem servidor. Baseado no Editor.js, sem CDN, sem build, sem servidor.

## Arquivos

- `index.html` — interface completa
- `core.css` — estilos do editor
- `editorjs/` — Editor.js + plugins (header, list, code, quote, delimiter)

## Como usar

Abra `index.html` diretamente no navegador (não precisa de servidor). Todo o processamento é local (edição, rascunho no `localStorage`, exportação HTML com CSS embutido).

Atalhos principais: Ctrl+N (novo), Ctrl+O (abrir), Ctrl+S (salvar rascunho), Ctrl+E (exportar HTML), Ctrl+P (imprimir).

## Licença

Apache-2.0 — Leafole Labs. <br>
Editor.js: Apache-2.0. Plugins: MIT. <br>
Ver `THIRD_PARTY_NOTICES.md` para detalhes.
