# 🎬 Vídeos Surpresa

Este projeto é um site que oferece uma experiência de "Vídeos Surpresa" ao usuário. O site carrega vídeos aleatórios de categorias como **Carros**, **Humor**, **Política** e muitas outras, utilizando a **API do YouTube**. O projeto é otimizado para uma requisição única por acesso e apresenta uma interface simples e intuitiva.

## Funcionalidades

- **Vídeo Surpresa**: Ao clicar no botão "Vídeo Surpresa", um vídeo de uma categoria aleatória será carregado.
- **Categorias**: O site possui categorias como **Carros**, **Humor**, **Política**, **Música**, entre outras, onde o usuário pode explorar vídeos relacionados.
- **Modo Dark/Light**: Alternância entre os modos de tema claro e escuro com um simples clique no ícone.
- **Armazenamento Local**: Utiliza `localStorage` para garantir que apenas uma requisição à API seja feita durante a sessão do usuário.
- **Responsividade**: O design é totalmente adaptável, proporcionando uma boa experiência em dispositivos móveis e desktop.

## Tecnologias Usadas

- **HTML5**: Estruturação do conteúdo da página.
- **CSS3**: Estilização responsiva e animações.
- **JavaScript**: Lógica para interação com a API do YouTube e controle de vídeo.
- **API do YouTube**: Utilizada para buscar vídeos aleatórios por categoria.
- **localStorage**: Para armazenar o vídeo carregado e evitar requisições repetidas.

## Como Rodar o Projeto

1. **Clonar o repositório**:
    ```bash
    git clone https://github.com/SEU-USUARIO/VIDEOS-SURPRESA.git
    ```
2. **Abrir o arquivo `index.html` no navegador**:
    - O site não depende de um servidor, basta abrir o arquivo diretamente no navegador.

## Como Funciona

1. Quando o site é acessado pela primeira vez, uma requisição é feita à **API do YouTube** para carregar um vídeo aleatório de uma categoria. O vídeo é então armazenado no `localStorage`.
2. Os botões de categoria permitem que o usuário visualize vídeos relacionados a diferentes temas (ex: **Carros**, **Humor**, etc.).
3. O botão "Vídeo Surpresa" carrega um novo vídeo de uma categoria aleatória sem fazer outra requisição à API.
4. O botão de alternância de tema permite que o usuário alterne entre o modo claro e escuro.

## Como Contribuir

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Faça commit das suas alterações (`git commit -am 'Adiciona nova feature'`).
4. Envie para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request para o repositório principal.

## Créditos

- **Desenvolvedor**: João Ricardo, engenheiro de computação
- **Instagram**: [@joaoricardo.pe](https://www.instagram.com/joaoricardo.pe)

## Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
