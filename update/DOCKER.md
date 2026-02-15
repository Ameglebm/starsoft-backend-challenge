1° Ajustar docker = OK
2° Docker composer pois vai ter varias aplicações rodando ao mesmo tempo = OK
    Serviços
    Rede
    Portas
    Dependências
    Variáveis
    Volume
    Recursos
3° Defini 4 containes 1 pro postgre, redis, rabbit = OK
    Postgres    Persistência de dados
    Redis       Cache / performance
    RabbitMQ    Comunicação assíncrona
    nest        Aplicação
    Obs: Tem que tudo rodar somente com 1 comando
4° Instalar dependencias = OK
5° Testar o docker com uma mensagem funcionando todos os containers = OK 
6° Verificar se tem container rodando em docker ps = OK
7° Se tiver matar e começar zerado sudo lsof i :..... e sudo kill .... e nao esquecer de ver os containers parados docker ps -a ou remover manualmente se nao sair por nd docker rm {id} = OK
8° Analisar todos containers feitos e se esta funcionando idependente ou em conjunto tambem e verificar documentaçãocom versões para nao ter erro de versão
9° Começar a criar o nest e suas dependencias,  usa o npx @nestjs/cli new . --skip-install q ele já se ajusta com a pasta atual e global
10° Depois de instalado e funcionando no container verificar atulizacoes e dependencias tbm limpar nodemodules, tsconf,pck.json e limpar o cache para nenhum erro aftansma e depois instala rnovamnte
11° Verificar pacotes atualizados npm outdated e atualize os que estiverem desatualizados e depois refazer a etapa 10
12° rodar o projeto e verificar se ainda há erros ou atualizações necessarias
13° Atualizar e verificar novamente e prosseguir e apagar os volumes e deixar atualizado do zero limpooO
14° Subir os containers com o -d na hr de buildar o docker
15° Verificar todos containers ativos
16° Testar cada container idependente e depois subir todos juntos
17° Commitar e enviar o Init do projeto