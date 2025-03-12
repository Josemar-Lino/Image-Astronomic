# NASA APOD (Astronomy Picture of the Day)

Este projeto utiliza a API da NASA para exibir a **Imagem do Dia da Astronomia** (APOD - Astronomy Picture of the Day). A página mostra uma imagem ou vídeo relacionado ao espaço, juntamente com um título, data e explicação sobre o conteúdo. A interface também oferece tradução automática para o português, utilizando o serviço de tradução do Google.

## Funcionalidades

- Exibe a **Imagem ou Vídeo do Dia** relacionado ao espaço.
- Fornece o **título**, **data** e uma **explicação** sobre o conteúdo.
- Suporta **tradução automática** para português, inglês e espanhol, usando a API de tradução do Google.

## Tecnologias Usadas

- **HTML**: Para estruturação da página.
- **CSS**: Para estilizar os elementos (referenciado através de `styles.css`).
- **JavaScript**: Para fazer a requisição à API da NASA e atualizar o conteúdo dinamicamente.
- **API da NASA**: Para obter a Imagem do Dia da Astronomia (APOD).
- **Google Translate**: Para oferecer tradução automática da página para português, inglês e espanhol.

## Como Usar

### 1. Obter uma Chave API da NASA
Este projeto usa a [API da NASA](https://api.nasa.gov/). Você precisará de uma chave API pessoal para evitar limitações no número de requisições. Para obter sua chave, siga os passos abaixo:

- Acesse [NASA API](https://api.nasa.gov/).
- Crie uma conta e gere sua chave API.
- Substitua o valor da variável `API_KEY` no código pelo valor da sua chave API.

```javascript
const API_KEY = 'SUA_CHAVE_API';

## Contribuição
Se você deseja contribuir com o projeto, sinta-se à vontade para fazer um fork e enviar pull requests. Certifique-se de seguir os seguintes passos:

Faça um fork do repositório.
Crie uma branch para a sua feature (git checkout -b minha-feature).
Faça as mudanças desejadas e faça commit (git commit -am 'Adiciona minha feature').
Envie para o repositório (git push origin minha-feature).
Abra um pull request.

## Licença

Este projeto é licenciado sob a MIT License - consulte o arquivo LICENSE para mais detalhes.
