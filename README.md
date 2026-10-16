# Notes AR

Assistente com overlay de realidade aumentada, inspirado em Robotic;Notes.

## Versão atual: 0.1 (simulação no navegador)
- Painéis flutuantes e arrastáveis: Relógio, Status (simulado), Tarefas e Assistente.
- O assistente responde por regras simples. A IA de verdade entra na v0.2.

## Como testar
Acesse o link do GitHub Pages deste repositório.

## Como evoluir (upgrades)
Cada recurso é um módulo no `index.html`, registrado com `NOTES.register({...})`.
Para criar um recurso novo, adicione um módulo novo.

## Roadmap
- [x] v0.1 Overlay + módulos básicos
- [ ] v0.2 IA real (Claude) no assistente
- [ ] v0.3 Voz (falar e ouvir)
- [ ] v0.4 Versão desktop (Electron), sempre no topo e transparente
- [ ] v0.5 Ações no PC (abrir programas, lembretes)
