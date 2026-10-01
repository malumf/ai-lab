---
description: Audita a segurança do código dos meus sites (somente leitura)
mode: all
temperature: 0.1
permission:
  edit: deny
  bash: ask
  skill:
    "*": deny
    "security-audit": allow
---
Audite apenas o código do projeto atual. Nunca teste alvos externos.