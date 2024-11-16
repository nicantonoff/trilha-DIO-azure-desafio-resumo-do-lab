# trilha-DIO-azure-desafio-resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Curso AZ-900 disponibilizado dentro do bootcamp "XP Inc. - Full Stack Developer".

Lab 01
- O portal da Azure é o mesmo tanto para empresas grandes como para usuário individual, só talvez tenha algumas limitações para usuário gratuito.
- Existe a possibilidade de mudar o estilo visual/esquema de cores.
- Os serviços são separados por tipo: computação, bancos de dados, rede, armazenamento, etc.
- Serviços em "versão prévia" não possuem SLA (Service Level Agreement) e podem ser descontinuados sem aviso prévio, portanto, não é para usar para cargas de trabalho em produção.

Lab 02
- Quanto maior o número de noves do SLA, menor a tolerância de indisponibilidade.
- SLA 99% é mais barato mas permite indisponibilidade de até 3,65 dias em um ano.
- SLA 99,999% é mais caro mas reduz a indisponibilidade para um máximo de 5,26 minutos em um ano.
- Na criação de uma máquina virtual é possível selecionar somente uma ou mais de uma zona de disponibilidade, isso faz com que a Azure crie uma máquina virtual em cada zona de disponibilidade que foi selecionada.
- Existem tooltips e links para documentação que explicam em mais detalhes cada opção e recurso.
- Na criação de uma máquina virtual é possível selecionar diferentes opções de disponibilidade, cada opção tem um SLA diferente, que deverá ser pesquisado na documentação.
- Contas de armazenamento tem várias opções de redundância, que implicam diretamente no número de noves do SLA e no preço cobrado.
- Ao atender uma demanda de criação de recurso na nuvem é necessário entender se é para um cenário de testes ou produção e qual é o nível de criticidade, para que a melhor solução custo-benefício seja aplicada.
