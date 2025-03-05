<h1> WeatherMap </h1>
 WeatherMap é um aplicativo simples que exibe a previsão do tempo atual, incluindo temperatura, condições climáticas e umidade. O aplicativo faz integração com a API do OpenWeatherMap para obter os dados meteorológicos em tempo real.

Funcionalidades
Temperatura Atual: Exibe a temperatura atual em graus Celsius.

Condições Climáticas: Mostra as condições climáticas atuais (ex: céu limpo, nublado, chuva).

Umidade: Exibe a porcentagem de umidade do ar.

Integração com API: Utiliza a API do OpenWeatherMap para obter dados meteorológicos precisos.

Pré-requisitos
API Key do OpenWeatherMap: Para utilizar o aplicativo, você precisará de uma chave de API do OpenWeatherMap. Você pode obter uma chave gratuita aqui.

Instalação
Clone o repositório:

bash
Copy
git clone https://github.com/Arthurvenicio03/WeatherMap.git
cd WeatherMap
Instale as dependências:

bash
Copy
npm install
Configure a API Key:

Crie um arquivo .env na raiz do projeto.

Adicione sua chave de API do OpenWeatherMap no arquivo .env:

env
Copy
REACT_APP_OPENWEATHERMAP_API_KEY="sua_chave_aqui"
Inicie o aplicativo:

bash
Copy
npm start
O aplicativo estará disponível em http://localhost:3000.

Como Usar
Acesse o aplicativo: Abra o navegador e vá para http://localhost:3000.

Insira a localização: Digite o nome da cidade no campo de busca e pressione "Enter".

Veja a previsão do tempo: O aplicativo exibirá a temperatura, condições climáticas e umidade da localização inserida.

Estrutura do Projeto
src/components/: Contém os componentes React do aplicativo.

src/services/: Contém o serviço de integração com a API do OpenWeatherMap.

src/App.js: Componente principal do aplicativo.

src/index.js: Ponto de entrada do aplicativo.

Tecnologias Utilizadas
React: Biblioteca JavaScript para construção de interfaces de usuário.

Axios: Cliente HTTP para fazer requisições à API.

OpenWeatherMap API: API de previsão do tempo.

Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.

Contato
Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

Email: Arthurvenicio3@gmail.com

GitHub: ArthurVenicio03

WeatherMap - Mantenha-se informado sobre o clima de forma simples e rápida!
