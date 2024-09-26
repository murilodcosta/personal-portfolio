# Personal Portfolio

Este é um projeto de portfólio desenvolvido usando Flask. O objetivo deste projeto é fornecer uma página simples e estilosa para exibir suas informações profissionais e projetos.

## Estrutura do Projeto

- **app.py**: Arquivo principal da aplicação Flask.
- **requirements.txt**: Arquivo contendo as dependências do projeto.
- **static/**: Pasta onde estão armazenados os arquivos estáticos, como CSS, imagens e scripts.
  - **css/**:
    - **index.css**: Arquivo de estilos.
  - **img/**:
    - **mc-logo.png**: Logotipo usado no site.
    - **mc-logo-b.png**: Logotipo usado no site.
    - **mc-logo-w.png**: Logotipo usado no site.
  - **js/**:
    - **script.js**: Arquivo de scripts.
- **templates/**: Pasta onde estão os templates HTML.
  - **index.html**: Página principal da aplicação.

## Como Executar o Projeto


1. *Clone o repositório:*

   bash
   git clone https://github.com/seu-usuario/personal-portfolio.git
   cd personal-portfolio
   

2. *Crie um ambiente virtual e ative-o:*

   bash
   python -m venv venv
   source venv/bin/activate  # Linux/MacOS
   venv\Scripts\activate  # Windows
   

3. *Instale as dependências:*

   bash
   pip install -r requirements.txt
   

4. *Execute a aplicação:*

   bash
   python app.py
  

## Uso de Bootstrap

O projeto utiliza o [Bootstrap](https://getbootstrap.com/) para estilização e layout responsivo. O Bootstrap é uma biblioteca de CSS que facilita a criação de layouts modernos e responsivos sem muito esforço.

### Onde o Bootstrap é Utilizado:

- *index.html*: O Bootstrap é importado diretamente no <header> (NAVBAR) da página HTML para fornecer classes utilitárias usadas em diversos elementos da página, como containers, grids e botões.
- *style.css*: O arquivo style.css pode conter customizações adicionais ou sobreposições às classes do Bootstrap para ajustar a aparência conforme necessário.

## Personalização

Você pode personalizar o conteúdo da página editando o arquivo index.html na pasta templates. Para mudar os estilos, edite o arquivo index.css na pasta static. Se precisar alterar algo relacionado ao layout, considere o uso das classes do Bootstrap ou adicione suas próprias classes CSS.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.
