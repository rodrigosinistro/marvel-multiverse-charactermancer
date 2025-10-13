# Changelog

## v0.1.1 — 2025-10-04
- Fix: Traços e Tags escolhidos no Charactermancer agora são criados na ficha com seus tipos canônicos do compêndio.
- Data: carregamento de Traços/Tags mantém o tipo original e usa um `mmcKind` normalizado para categorizar corretamente.

## v0.1.0 — 2025-10-03
- First GitHub release (baseline interno = v0.6.109).
- **Step 5 (Poderes):** cross-list de famílias numeradas entre Power Sets (ex.: *Jump 1/2/3* em **Super-Strength** e **Spider-Powers**).
- **Step 5:** dedupe por *(nome + powerSet)* e filtro case-insensitive; fonte correta da lista.
- **Step 4 (Traits & Tags):** carga “fresca” de Mundo + Compêndios ao abrir (sem botão **Atualizar**), hooks live, preservação de scroll.
- **Finalize:** criação do ator sem `type undefined`.
- **Compat:** Foundry v13 (mín. v12).
