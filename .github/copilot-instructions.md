# Descrição do Projeto

Este projeto é um site educacional para compartilhar tarefas de casa e exercícios de programação com estudantes. Os estudantes podem navegar, visualizar e baixar tarefas diretamente do portal.

## Estrutura do Projeto

- [`assignments/`](../assignments/) Cada tarefa de casa é armazenada em sua própria subpasta com sua estrutura existente
- [`templates/`](../templates/) Templates reutilizáveis para novo conteúdo
- [`assets/`](../assets/) Contém os recursos do site incluindo CSS, JavaScript, imagens e arquivos de configuração
- [`index.html`](../index.html) A página principal do site que serve como um portal estático para navegar e visualizar tarefas. O conteúdo é configurável através do arquivo [`config.json`](../config.json) para gerar dinamicamente listas e detalhes de tarefas.

## Diretrizes do Projeto

- Manter estilo consistente em todas as páginas
- Manter nomes de arquivos e pastas descritivos e organizados

## Conventional Commits

Este projeto utiliza o padrão Conventional Commits para mensagens de commit. Siga sempre este formato:

```
<tipo>(<escopo>): <descrição>

[corpo opcional]

[rodapé opcional]
```

### Tipos de Commit

- **feat**: Nova funcionalidade para o usuário
- **fix**: Correção de bug
- **docs**: Mudanças na documentação
- **style**: Formatação, ponto e vírgula ausente, etc (sem mudança de código)
- **refactor**: Refatoração de código (sem correção de bug ou nova funcionalidade)
- **test**: Adicionar ou corrigir testes
- **chore**: Tarefas de manutenção (atualização de dependências, configurações, etc)

### Exemplos de Commits

```bash
feat(assignments): adiciona nova tarefa de análise de dados
fix(css): corrige layout responsivo no mobile
docs(readme): atualiza instruções de instalação
style(js): aplica formatação consistente no código
refactor(config): reorganiza estrutura de configuração
test(python): adiciona testes para exercícios básicos
chore(deps): atualiza dependências do projeto
```

### Escopo (Opcional)

Use escopos para indicar a área afetada:
- `assignments`: Tarefas e exercícios
- `assets`: CSS, JS, imagens
- `config`: Arquivos de configuração
- `templates`: Templates reutilizáveis
- `docs`: Documentação

## Padrões Educacionais

Ao gerar conteúdo para este projeto:

- **Focado em aprendizado**: Todo conteúdo deve ser projetado com objetivos de aprendizado claros e níveis de dificuldade apropriados
- **Explicações claras**: Forneça comentários detalhados no código e documentação que explique conceitos para estudantes
- **Progressão estruturada**: Organize exercícios do básico ao avançado
- **Exemplos práticos**: Inclua exemplos do mundo real que sejam relevantes para estudantes
- **Código limpo**: Demonstre boas práticas de programação e convenções de codificação
- **Interatividade**: Quando possível, crie exercícios que permitam experimentação e descoberta

## Linguagens de Programação

Este projeto foca principalmente em:
- **Python**: Para exercícios de programação básica e análise de dados
- **JavaScript**: Para funcionalidades web interativas
- **HTML/CSS**: Para estrutura e estilo do portal web

## Formato de Resposta

Sempre responda em português brasileiro e mantenha um tom educacional e encorajador.