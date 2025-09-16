# 🚀 Sandbox Repository

Um repositório sandbox para preview de documentos Markdown e testes antes da implementação final.

## 📋 Sobre

Este repositório serve como um ambiente intermediário onde você pode:

- ✏️ **Escrever documentos em Markdown** com templates prontos
- 👀 **Visualizar preview** dos documentos antes de mover para o projeto final
- 🧪 **Testar formatação** e estrutura de conteúdo
- 📁 **Organizar rascunhos** e versões de trabalho

## 🗂️ Estrutura de Pastas

```
📦 Sandbox/
├── 📄 docs/           # Documentos finalizados e templates
├── 📋 examples/       # Exemplos e referências
├── ✏️ drafts/         # Rascunhos e trabalhos em progresso
├── 🖼️ assets/         # Imagens, diagramas e mídia
├── 🌐 index.html      # Interface web para navegação
└── 📦 package.json    # Ferramentas de preview
```

## 🚀 Como Usar

### 1. Preview Local com Live Server

```bash
# Instalar dependências
npm install

# Iniciar servidor de preview (porta 3000)
npm run preview

# Ou usar servidor HTTP simples
npm run serve
```

### 2. Criando Documentos

1. **Para novos documentos:** Copie o template de `docs/template.md`
2. **Para rascunhos:** Use a pasta `drafts/`
3. **Para exemplos:** Consulte `examples/sample-document.md`

### 3. Adicionando Mídia

- Coloque imagens na pasta `assets/`
- Reference com: `![Alt text](../assets/nome-da-imagem.png)`

### 4. Navegação Web

Abra `index.html` no navegador para uma interface visual de navegação pelos documentos.

## 📝 Templates Disponíveis

- **📄 Template Básico** (`docs/template.md`): Estrutura padrão para documentos
- **📋 Documento de Exemplo** (`examples/sample-document.md`): Showcase de recursos Markdown

## 🛠️ Ferramentas de Preview

### Live Server
```bash
npm run preview
```
- Auto-reload quando arquivos mudam
- Servidor local na porta 3000
- Navegação por pastas

### HTTP Server Simples
```bash
npm run serve
```
- Servidor estático básico
- Boa para preview rápido

## 📚 Exemplos de Uso

### Workflow Típico

1. **Rascunho inicial:** Criar arquivo em `drafts/`
2. **Desenvolvimento:** Usar preview para ajustar formatação
3. **Finalização:** Mover para `docs/` quando pronto
4. **Transferência:** Copiar conteúdo para projeto final

### Estrutura de Documento Recomendada

```markdown
# Título do Documento

**Data:** [Data Atual]
**Autor:** [Seu Nome]
**Status:** [Rascunho/Revisão/Final]

## Conteúdo...
```

## 🔧 Comandos Disponíveis

```bash
npm run preview      # Live server com auto-reload
npm run serve        # Servidor HTTP simples
npm run install-tools # Instalar ferramentas globais
npm run help         # Ver comandos disponíveis
```

## 📖 Recursos Markdown Suportados

- **Formatação:** Negrito, itálico, código
- **Listas:** Numeradas e com marcadores
- **Tabelas:** Formatação completa
- **Código:** Blocos com syntax highlighting
- **Links:** Internos e externos
- **Imagens:** Com suporte a assets locais
- **Blockquotes:** Citações formatadas

## 🎯 Casos de Uso

- 📝 **Documentação técnica:** Preview antes de commit
- 📚 **Artigos e posts:** Teste de formatação
- 📋 **README files:** Validação de estrutura
- 🎨 **Experimentação:** Teste de novos formatos

## 🤝 Contribuindo

Este é seu sandbox pessoal! Sinta-se livre para:

- Adicionar novos templates
- Criar exemplos específicos
- Organizar pastas conforme necessário
- Personalizar o ambiente de preview

---

**💡 Dica:** Use este repositório como um "laboratório" para testar ideias antes de implementá-las em seus projetos principais!