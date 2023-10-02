## Banco DigitaL - API MuleSoft
Codificação de aplicação MuleSoft fornece uma série de endpoints para facilitar as operações Bancárias Digitais, incluindo autenticação biométrica, interações com aplicativos móveis e integrações com IA e chatbots.


## Pré-requisitos
- Mule Runtime 4.x
- Anypoint Studio 7.x
- JDK 8

## Instalação
Clone este repositório:

```
git clone https://github.com/seuusuario/banco-digital-mulesoft.git
```
Importe o projeto para o Anypoint Studio.

Atualize as configurações conforme necessário.


## Endpoints
Aplicativos Móveis

- Path: /mobile-apps
- Método: GET
- Descrição: Captura as requisições para interações com aplicativos móveis.
- Biometria e Autenticação de Dois Fatores

- Path: /biometric-2fa
- Método: GET
- Descrição: Inicia o processo de autenticação biométrica ou de dois fatores.
- IA e Chatbots

- Path: /ai-chatbots
- Método: GET
- Descrição: Captura e processa as interações com IA e chatbots.
- Executando a Aplicação

No Anypoint Studio, clique com o botão direito do mouse sobre o projeto.

Selecione Run As > Mule Application.

Verifique o console para garantir que a aplicação foi iniciada com sucesso.

Use um cliente HTTP ou cURL para testar os endpoints.


### Autor:
Emerson Amorim


