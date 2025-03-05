
# WeatherMap

O **WeatherMap** é um aplicativo Android simples e intuitivo que exibe a previsão do tempo atual, incluindo temperatura, condições climáticas e umidade. Desenvolvido com **Kotlin**, **Jetpack Compose** e integração com a API do OpenWeatherMap, ele oferece uma experiência moderna e responsiva para os usuários.

---

## Funcionalidades Principais

- **Temperatura Atual**: Exibe a temperatura atual em graus Celsius.
- **Condições Climáticas**: Mostra as condições climáticas atuais (ex: céu limpo, nublado, chuva).
- **Umidade**: Exibe a porcentagem de umidade do ar.
- **Integração com API**: Utiliza a API do OpenWeatherMap para obter dados meteorológicos precisos e confiáveis.
- **Interface Moderna**: Desenvolvido com Jetpack Compose para uma UI fluída e responsiva.

---

## Pré-requisitos

Antes de começar, você precisará de:

1. **Chave de API do OpenWeatherMap**:
   - Obtenha uma chave de API gratuita no site do [OpenWeatherMap](https://openweathermap.org/api).
   - A chave será necessária para fazer requisições à API.

2. **Android Studio**:
   - Certifique-se de ter o Android Studio instalado. Você pode baixá-lo em [developer.android.com](https://developer.android.com/studio).

3. **Dispositivo ou Emulador Android**:
   - Um dispositivo físico ou um emulador configurado para testar o aplicativo.

---

## Instalação

Siga os passos abaixo para configurar e executar o projeto localmente:

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Arthurvenicio03/WeatherMap.git
   cd WeatherMap
   ```

2. **Abra o projeto no Android Studio**:
   - Inicie o Android Studio e selecione "Open an Existing Project".
   - Navegue até a pasta do projeto e clique em "OK".

3. **Configure a chave da API**:
   - No arquivo `local.properties`, adicione sua chave de API do OpenWeatherMap:
     ```properties
     OPENWEATHERMAP_API_KEY=sua_chave_aqui
     ```

4. **Execute o aplicativo**:
   - Conecte um dispositivo Android ou inicie um emulador.
   - Clique em "Run" (ícone de play) no Android Studio para compilar e executar o aplicativo.

---

## Como Usar

1. **Acesse o aplicativo**:
   - Abra o WeatherMap no seu dispositivo ou emulador.

2. **Insira a localização**:
   - Digite o nome da cidade no campo de busca e pressione "Enter" ou o ícone de busca.

3. **Veja a previsão do tempo**:
   - O aplicativo exibirá a temperatura, condições climáticas e umidade da localização inserida.

---

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
WeatherMap/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/weathermap/  # Código-fonte em Kotlin
│   │   │   │   ├── ui/                      # Componentes da UI com Jetpack Compose
│   │   │   │   ├── viewmodel/               # ViewModels para gerenciar dados
│   │   │   │   ├── repository/             # Repositório para interação com a API
│   │   │   │   ├── model/                   # Modelos de dados
│   │   │   │   └── utils/                  # Utilitários e extensões
│   │   │   ├── res/                         # Recursos do aplicativo (imagens, strings, etc.)
│   │   │   └── AndroidManifest.xml          # Configurações do aplicativo
│   │   └── test/                            # Testes unitários
├── build.gradle                             # Configurações de build do módulo app
├── local.properties                         # Arquivo para variáveis locais (API Key)
├── .gitignore                               # Arquivo para ignorar arquivos no Git
└── README.md                                # Documentação do projeto
```

---

## Tecnologias Utilizadas

- **Kotlin**: Linguagem de programação moderna para desenvolvimento Android.
- **Jetpack Compose**: Framework declarativo para construção de interfaces de usuário.
- **Retrofit**: Cliente HTTP para integração com a API do OpenWeatherMap.
- **ViewModel**: Para gerenciar dados relacionados à UI de forma eficiente.
- **LiveData/State**: Para observação de dados e atualização da UI.
- **Material Design 3**: Design system moderno para interfaces Android.

---

## Contribuição

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

1. Faça um fork do repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -m 'Adicionando nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

---

## Licença

Este projeto está licenciado sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- **Email**: Arthurvenicio3@gmail.com
- **GitHub**: [ArthurVenicio03](https://github.com/ArthurVenicio03)

---

**WeatherMap** - Mantenha-se informado sobre o clima de forma simples e rápida! 🌦️

---
