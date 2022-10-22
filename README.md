## Definir processo de desenvolvimento
![image](https://user-images.githubusercontent.com/71986202/197342897-4c01d3b9-223b-4ae6-a1b8-e745d7bc7bda.png)

## Definir aonde armazenar o seu código e seu fluxo
 - GitFlow
 - GitHub Flow
 - GitLab Flow
 - Trunk-based development

## Definir as branches 
  - feature 
  - develop
  - release
  - hotfix
  - master
  
Consecutivamente suas permissões

## Definir uma arquitetura para o seu projeto
  - fluxo
  - separar responsabilidades
  
  exemplos de arquitetura:
  - Clean Architecture 
  - Arquitetura em camadas
  - Principios de SOLID
  
  criar arquiteturas baseado em sua literatura ou ultilizar alguma arquitetura de referencia 
  
  ![image](https://user-images.githubusercontent.com/71986202/197343533-bab7fd4f-202d-46e2-8161-5976b949f67b.png)
exemplo da foto: Bloc
  
  link:
  https://verygood.ventures/blog/very-good-flutter-architecture
  
## Gerenciamento de Estado
  Pesquisar sobre as tecnologias que empresas maiores estão ultilizando e se tem suporte para o pacote que deseja ultilizar.
  Para quem vem do desenvolvimento WEB é comum o uso do MobX
 
## Verificar a versão do seu Flutter e as novidades que foram implementadas
 - 3.3 por exemplo, tem o: Wonderous
 https://github.com/gskinnerTeam/flutter-wonderous-app
 
## Cuidado na definição das dependencias / packages 
 - Dependencias que vão ser o core
    - Verificar a quantidade de like
    - Se possui o selo Flutter Favorite
    - Versão
    - Ciclo de publicação
    - Quais plataformas que o package da suporte
    - Provide Documentation
    - Cobertura de tests
    
## Verificar SDK para aonde você vai desenvolver
  - Android:
    https://gs.statcounter.com/os-version-market-share/android
    
## Definir as Widgest mais pequenas e reusáveis possivel 

## Mantenha um codigo de qualidade

## Cuidado com a segurança do aplicativo
  - Cuidar com o que salvo no app (troque o sharedPreference por secure_storage para credencial)

## Cuidado com a requisições
  - Ultilizar padrões de https e certificações para evitar que pessoas maliciosas interceptam essas requisições
  
## Variaveis de Ambiantes
  - .env = muitas vezes ele copia o .env para o bandle do android/iphone
  
## Criar um processo automatizado de CI/CD
  - Github para rodar 
    - Firebase Test Lab
    - codemagic (hibrido e nativo)
  - App Distribution (teste de QI)
  
## Monitorar o app em produção
  - Firebase Crashlytics (crash)
  - Sentry.io (crash)
  - Firebase Performace Monitoring (performace)

    
  

  
  
  
