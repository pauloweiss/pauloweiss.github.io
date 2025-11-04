---
layout: post
title: "Git: Comandos Básicos que Todo Desenvolvedor Deve Conhecer"
date: 2025-11-04 15:00:00 -0300
categories: desenvolvimento git
tags: [git, controle-versão, comandos]
---

O Git é essencial para qualquer desenvolvedor. Aqui estão os comandos que uso diariamente:

## Comandos Básicos

### Inicializar repositório
```bash
git init
```

### Ver status dos arquivos
```bash
git status
```

### Adicionar arquivos
```bash
git add .                # Adiciona todos
git add arquivo.txt      # Adiciona específico
```

### Fazer commit
```bash
git commit -m "Mensagem descritiva"
```

### Enviar para GitHub
```bash
git push origin main
```

## Comandos Úteis

### Ver histórico
```bash
git log --oneline --graph
```

### Desfazer alterações
```bash
git checkout -- arquivo.txt
```

### Ver diferenças
```bash
git diff
```

## Dicas

- Faça commits pequenos e frequentes
- Escreva mensagens de commit claras
- Use branches para novas features
- Sempre faça `git pull` antes de começar a trabalhar

Esses comandos cobrem 90% do uso diário do Git!