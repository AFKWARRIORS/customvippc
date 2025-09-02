# 🧠 Mapa Mental Interativo

Um mapa mental interativo e responsivo criado com HTML, CSS e JavaScript puro. Permite criar, editar e organizar ideias de forma visual e intuitiva.

## ✨ Características

- **Interface Intuitiva**: Design moderno e responsivo
- **Drag & Drop**: Arraste os nós para reorganizar
- **Edição em Tempo Real**: Duplo-clique para editar textos
- **Hierarquia Visual**: Diferentes cores para diferentes níveis
- **Conexões Automáticas**: Linhas conectam automaticamente os nós relacionados
- **Exportação**: Salve seu mapa mental em formato JSON
- **Responsivo**: Funciona em desktop e dispositivos móveis

## 🚀 Como Usar

### Abrindo o Mapa Mental

1. Abra o arquivo `mindmap.html` em qualquer navegador moderno
2. O mapa mental será carregado automaticamente com um nó central

### Controles Básicos

#### Painel de Controles (lado esquerdo)
- **Campo de Texto**: Digite o texto que deseja adicionar ao próximo nó
- **Adicionar Nó Central**: Cria um novo tópico principal
- **Adicionar Nó Filho**: Adiciona um subtópico ao nó selecionado
- **Adicionar Nó Neto**: Adiciona um sub-subtópico (apenas para nós filhos)
- **Deletar Nó Selecionado**: Remove o nó atualmente selecionado
- **Limpar Tudo**: Remove todos os nós do mapa
- **Exportar**: Salva o mapa mental como arquivo JSON

#### Interações com o Mouse
- **Clique**: Seleciona um nó
- **Duplo-clique**: Edita o texto do nó
- **Clique e arraste**: Move o nó para uma nova posição

### Estrutura Hierárquica

O mapa mental suporta três níveis de hierarquia:

1. **Nó Central (Azul)**: Tópico principal do mapa mental
2. **Nó Filho (Rosa)**: Subtópicos que se conectam ao nó central
3. **Nó Neto (Azul claro)**: Sub-subtópicos que se conectam aos nós filhos

### Dicas de Uso

1. **Planeje sua estrutura**: Comece com o tópico central e expanda gradualmente
2. **Use textos concisos**: Mantenha os textos dos nós curtos e diretos
3. **Organize visualmente**: Arraste os nós para criar uma distribuição equilibrada
4. **Salve regularmente**: Use a função de exportação para não perder seu trabalho

## 🎨 Personalização

O mapa mental usa um design moderno com:
- Gradientes coloridos para diferentes tipos de nós
- Efeitos de hover e seleção
- Animações suaves
- Interface com glassmorphism

## 📁 Estrutura de Arquivos

```
├── mindmap.html      # Arquivo principal do mapa mental
├── README.md         # Este arquivo de instruções
└── mindmap.json      # Arquivo de exportação (criado automaticamente)
```

## 🔧 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna com flexbox e grid
- **JavaScript ES6+**: Funcionalidades interativas
- **Canvas API**: Para desenhar as conexões entre nós

## 🌟 Funcionalidades Avançadas

### Exportação de Dados
O mapa mental pode ser exportado como arquivo JSON, contendo:
- Posição de todos os nós
- Textos e hierarquia
- Relacionamentos entre nós

### Responsividade
- Adapta-se a diferentes tamanhos de tela
- Funciona em dispositivos móveis
- Interface otimizada para touch

## 🐛 Solução de Problemas

### Nó não se move
- Certifique-se de clicar diretamente no nó
- Verifique se não há outros elementos sobrepostos

### Conexões não aparecem
- As conexões são criadas automaticamente
- Verifique se os nós têm relacionamentos pai-filho corretos

### Texto não edita
- Use duplo-clique para editar
- Certifique-se de que o nó está selecionado

## 📝 Licença

Este projeto é de código aberto e pode ser usado livremente para fins educacionais e pessoais.

## 🤝 Contribuições

Sinta-se à vontade para:
- Reportar bugs
- Sugerir melhorias
- Contribuir com código
- Compartilhar seus mapas mentais criados

---

**Divirta-se criando seus mapas mentais! 🧠✨**