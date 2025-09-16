# 🎯 Guia de Uso Rápido

## ⚡ Início Rápido

### 1. Instalar Dependências
```bash
npm install
```

### 2. Iniciar Preview
```bash
# Opção 1: Live Server (recomendado)
npm run preview

# Opção 2: HTTP Server simples
npm run serve
```

### 3. Acessar Interface
- **Web Interface:** Abra `http://localhost:3000` no navegador
- **Navegação:** Use `index.html` como ponto de entrada

## 📝 Fluxo de Trabalho

### Criando um Novo Documento

1. **Copie o template:**
   ```bash
   cp docs/template.md docs/meu-documento.md
   ```

2. **Edite o conteúdo:**
   - Use seu editor favorito
   - Preview em tempo real no navegador

3. **Adicione mídia:**
   - Coloque imagens em `assets/`
   - Reference: `![desc](../assets/image.png)`

4. **Finalize:**
   - Mova para `docs/` quando pronto
   - Use `drafts/` para trabalho em progresso

### Organizando Conteúdo

- **📄 docs/**: Documentos finalizados
- **✏️ drafts/**: Rascunhos e ideias
- **📋 examples/**: Referências e exemplos
- **🖼️ assets/**: Imagens e mídia

## 🛠️ Comandos Úteis

```bash
# Preview com live reload
npm run preview

# Servidor HTTP básico
npm run serve

# Ajuda
npm run help

# Instalar ferramentas globais
npm run install-tools
```

## 💡 Dicas

- **Auto-reload:** Funciona com `npm run preview`
- **Markdown:** Suporte completo incluindo tabelas e código
- **Assets:** Use caminhos relativos para imagens
- **Templates:** Personalize conforme necessário

## 🔗 Links Úteis

- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Flavored Markdown](https://github.github.com/gfm/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)