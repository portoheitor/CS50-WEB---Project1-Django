# CS50-WEB Project1-Django 💻⚙️

## Requisitos do Projeto ⚗️

### Página de Entrada

- **Visitar `/wiki/TITULO`**:
  - Onde `TITULO` é o título de uma entrada da enciclopédia.
- **Renderizar uma Página**:
  - Exibir o conteúdo da entrada.
- **Obter o Conteúdo**:
  - Chamar a função `util` apropriada.
- **Entrada Não Existe**:
  - Mostrar uma página de erro.
- **Entrada Existe**:
  - Mostrar uma página com o conteúdo da entrada.
  - O título da página deve incluir o nome da entrada.

### Página de Índice

- **Atualizar `index.html`**:
  - Permitir que o usuário clique nos nomes das entradas e seja levado diretamente para a página da entrada correspondente.

### Busca

- **Caixa de Busca na Barra Lateral**:
  - Permitir que o usuário digite uma consulta.
- **Consulta Corresponde ao Nome de uma Entrada**:
  - Redirecionar o usuário para a página dessa entrada.
- **Consulta Não Corresponde ao Nome de uma Entrada**:
  - Levar o usuário a uma página de resultados de busca que liste todas as entradas contendo a consulta como substring.
  - Exemplo: Se a consulta for "ytho", "Python" deve aparecer nos resultados.
- **Clicar em um Nome de Entrada nos Resultados**:
  - Levar o usuário para a página dessa entrada.

### Nova Página

- **Clicar em "Criar Nova Página" na Barra Lateral**:
  - Levar o usuário a uma página para criar uma nova entrada.
- **Inserir Título e Conteúdo em Markdown**:
  - O usuário deve poder inserir um título e o conteúdo em Markdown em uma área de texto.
- **Salvar Nova Página**:
  - Clicar em um botão para salvar.
  - **Título Já Existe**:
    - Mostrar uma mensagem de erro.
  - **Título Não Existe**:
    - Salvar a entrada no disco e redirecionar o usuário para a nova página.

### Editar Página

- **Link para Editar Conteúdo em Markdown**:
  - Cada página de entrada deve ter um link para editar o conteúdo.
- **Área de Texto Preenchida com Conteúdo Existente**:
  - O usuário deve poder salvar as alterações clicando em um botão.
- **Salvar Alterações**:
  - Redirecionar o usuário de volta para a página da entrada.

### Página Aleatória

- **Clicar em "Página Aleatória" na Barra Lateral**:
  - Levar o usuário a uma entrada aleatória da enciclopédia.
 
1. **Clonar o Repositório**:
   ```bash
   git clone git@github.com:portoheitor/CS50-WEB---Project1-Django.git
   ```

2. **Iniciar o Ambiente Virtual**:
   - Windows:
   ```bash
   venv/Scripts/Activate
   ```
    - Linux:
   ```bash
   source venv/Activate
   ```

3. **Iniciar o Servidor Web Local**:
   ```bash
   python manage.py runserver
   ```
<video width="640" height="480" controls>
  <source src="https://drive.google.com/file/d/1TW-R19stZNePKYJMr2e396r8g1xlhyVS/preview"
</video>

