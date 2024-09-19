Arquivo .env


 ----------------------------------


 
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_bWFnbmV0aWMtd2FsbGFieS03OC5jbGVyay5hY2NvdW50cy5kZXYk


EXPO_PUBLIC_PLACES_API_KEY=AIzaSyBpuY89aB4EZB7oQjQx1dDCf5yFV6lSv80
#EXPO_PUBLIC_DIRECTIONS_API_KEY=

DATABASE_URL=postgresql://jsm_belovedfriends_owner:sWPwy8GNKR3Z@ep-old-field-a5ctronr.us-east-2.aws.neon.tech/jsm_belovedfriends?sslmode=require

EXPO_PUBLIC_SERVER_URL=https://belovedfriends.com/

EXPO_PUBLIC_GEOAPIFY_API_KEY=f98e36dc45d4499c87a7764f91809369

 -----------------------------------

Passo a passo para rodar o projeto:

1- Baixe todo o projeto (git clone)

2- Instale todas as dependencias ( npm install )

3- Após instalar todas as dependecias, abra o terminal e digite "npm start"

4- Após o "npm start" ( ou "npx expo start), o terminal irá exibir o link para acesso do projeto pelo navegador e também um QRCODE para conseguir ter acesso via celular

5- Baixe o aplicativo "Expo Go" em seu celular para conseguir visualizar o app no seu celular

6- Com o aplicativo baixado, basta entrar no aplicativo e selecionar a opçao "Scan QRCODE", depois scaneie o QRCODE gerado no terminal para conseguir acessar o projeto, com isso podemos abrir o projeto no celular e testa lo perfeitamente!!

-------------------------------------

Descrições técnicas utilizadas no projeto:

Utilizamos o next react como framework e a lingaguem typescript como principal lingaguem de programação. Além disso utilizamos outros serviços e tecnologias como ferramentas para o desenvolvimento do projeto.

Utilizamos o Clerk para ser nosso Authenticator, através dele é possivel criar contas, fazer login e até mesmo entrar com um provider como: entrar com sua conta Google

Utilizamos o Banco de Dados Neon para salvar toda a parte de informações do aplicativo, como filiados, passeios, entre outros

Utilizamos também o Geoapify para ajudar na parte de renderização de localicadades e auxiliar o Google Maps

Utilizamos o Google Maps para fazer toda a parte de localização tanto do usuario quanto do filiado e o sistema de tracking dos passeios em si










