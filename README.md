# Resumo-de-Estudo-Pick2026
## DOCKER
É um projeto de software livre que automatiza a implantação de aplicativos como containeres. O docker se apoia em recursos existentes do kernel do linux, para isolar a execução de processos. 
## CONTAINER
É um padrão de unidade de software que empacota código e todas as dependências de uma aplicação fazendo com que ela seja executada rapidamente de forma confiável independente do ambiente computacional.
## COMPARATIVO DAS VMS COM CONTAINERS
As VM's incluem sistemas operacionais inteiros, tornando-as mais pesadas e mais lentas para iniciar já os containers compartilham o kernel do sistema operacional host e isolam apenas o aplicativo e suas dependencias. Isso torna os containeres muito mais leves, mais eficientes no uso de recursos e mais rápido para iniciar do que as VM's. Os contêineres oferecem uma virtualização mais simplificada e focada em aplicativos em comparação com sistemas mais amplos das VM's.
## IMAGEM DOCKER
É um pacote leve, independente e executável que inclui tudo o que é necessário para executar um software, incluindo código, tempo de execução, bibliotecas, variáveis de ambiente e arquivos de configuração. A imagem isola o aplicativo de seu ambiente e garante que ele funcione de maneira uniforme..
## DOCKER FILE
É um arquivo de texto simples que contém uma série de comandos que Docker usa para montar uma imagem, dessa forma conseguiremos automatizar o processo de criação de imagens ex: se você tem várias imagens em um projeto, através da automação usando o docker file é possivel subir todas as imagens de uma só vez caso tenha necessidade destas imagens em um outro projeto.
