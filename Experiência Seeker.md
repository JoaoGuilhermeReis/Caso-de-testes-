#  Estudo prático com Seeker + Ngrok (Geolocalização via Engenharia Social)

##  Inicialização com Ngrok

```bash
python3 seeker.py

Pra que serve: 
Envio do link gerado para o alvo de teste e obtenha dados de **geolocalização** ao clicar no link.
Abaixo vou descrever o que aconteceu: 
**1º Passo**: Iniciei o Seeker no Kali Linux, onde precisei escolher entre a opção https (via Ngrok) ou porta 8080.
https://github.com/user-attachments/assets/e0acd60e-f6ac-4144-9d23-363437c446db
**2º Passo**: Escolhi a opção https (via Ngrok) e compartilhei o link comigo mesmo via WhatsApp. O link usado foi o de Forwarding HTTPS gerado pelo Ngrok.

https://github.com/user-attachments/assets/4f272b5f-2987-4972-9190-60ff59f5da3b
https://github.com/user-attachments/assets/305960bd-0aa4-4302-9549-bc1989a760c4

**3º Passo**: Ao acessar o link, recebi um alerta de segurança padrão do Ngrok avisando que o link pode ser malicioso, isso acontece apenas na versão gratuita.
Cliquei em "Visit site" (botão azul) para prosseguir.
https://github.com/user-attachments/assets/ae2d573b-164f-4ecf-b67e-0a6b4f9a89a6

**4º Passo**: Escolhi a opção 0 - Near You, e o Seeker gerou uma página falsa automaticamente.e.
https://github.com/user-attachments/assets/c5afb6c6-54c6-4840-9164-291990971d62

**5º Passo**: Ao clicar em "Continue", o site solicitou permissão de acesso à localização. Um usuário leigo provavelmente clicaria em "Permitir", expondo minha posição.
https://github.com/user-attachments/assets/bb80b143-c57b-4ca8-a30c-45933238ac5c
https://github.com/user-attachments/assets/63ecc0fe-cf42-42c2-bd0b-66d0e2604ea6

**6º Passo**: Coleta de informações com sucesso
https://github.com/user-attachments/assets/3529774d-2452-4f92-a462-692531bfd986

Após a permissão, obtive os seguintes dados via terminal:
Dados obtidos:
-Modelo e versão do dispositivo
-IP público
-País, Estado e Cidade (via IP)
-Latitude e Longitude reais (com link para Google Maps)
-Endereço aproximado do usuário

Considerações Finais
Este experimento mostra como ferramentas de engenharia social podem ser usadas para capturar dados sensíveis, mesmo sem interação maliciosa explícita. A lição mais importante é a necessidade de educação digital, tanto para usuários comuns quanto para profissionais de segurança.

Este estudo foi realizado em ambiente controlado, com fins educacionais e éticos. Nenhuma informação foi coletada sem consentimento.

Espero que tenha gostado da leitura, até a próxima ferramenta! :)
