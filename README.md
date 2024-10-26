# Portfolio Pro
O projeto **Portfolio Pro** é um modelo de landing page para portfólio pessoal, desenvolvido com HTML, JavaScript e SCSS. Ele inclui seções para apresentação, habilidades, projetos e contato, oferecendo um design moderno e responsivo. É uma base que pode ser personalizada para atender às necessidades específicas de cada desenvolvedor.

### Passos para Rodar o Projeto Corretamente

1. **Clonar o Repositório**
   - Faça o download ou clone o repositório para o seu computador:
     ```bash
     git clone https://github.com/Vitorcostalv/Portfolio-Pro.git
     ```
   - Navegue até o diretório do projeto:
     ```bash
     cd portfolio-pro
     ```

2. **Instalar o Sass**
   - Se ainda não tiver o Sass instalado, instale globalmente:
     ```bash
     npm install -g sass
     ```

3. **Compilar o SCSS para CSS**
   - Para gerar o arquivo CSS a partir do SCSS, execute o comando:
     ```bash
     sass scss/main.scss css/main.css --watch
     ```
   - O comando `--watch` faz com que o Sass monitore as mudanças nos arquivos SCSS e atualize automaticamente o `main.css` sempre que houver alguma alteração.

4. **Abrir o Projeto no Navegador**
   - Abra o arquivo `index.html` no seu navegador para visualizar a página. O design da landing page será atualizado sempre que o `main.css` for recompilado.

### Personalização do Projeto

Esse projeto serve como um modelo básico para um portfólio pessoal. Você pode personalizar:
- **Conteúdo do HTML**: atualize o arquivo `index.html` para incluir suas informações, como nome, habilidades e projetos.
- **Estilos SCSS**: ajuste as variáveis em `_variables.scss` para mudar as cores, fontes e tamanhos, adaptando o design ao seu gosto.
- **Componentes e Layouts**: adicione novas seções ou modifique as existentes, como a ordem das seções ou estilos dos cartões de projetos.

