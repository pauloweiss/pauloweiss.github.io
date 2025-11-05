---
layout: single
title: "Título do Post"
date: 2025-11-04 14:30:00 -0300
categories: desenvolvimento
tags: [jekyll, blog]
toc: true  # Tabela de conteúdo
toc_label: "Neste post"
toc_icon: "list"
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