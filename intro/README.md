# Criar uma máquina virtual no Hyper-V
## Habilitar o uso do Hyper-V
- Digite “Ativar ou desativar recursos do Windows” no campo de busca do Windows 10 e clique na opção que aparecer;
- Marque a caixa “Hyper-V” e clique em “OK”;
- O Windows irá instalar os recursos do Hyper-V no computador;
- Ao final do processo, clique em “Reiniciar agora” e reinicie o Windows.
## Criar Virtual Machine (VM)
- Abra o gerenciador de Hyper-v;
- Clique com o botão direito do mouse na máquina host;
- Em seguida, clique em "Novo" > "Máquina Vitual" > Avançar;
- Selecione o nome e o local de armazenamento da VM, clique em Avançar;
- Selecione a "Geração 1", clique em Avançar;
- Atribua o tamanho da memória RAM adequada à quantidade de VMs desejadas, clique em Avançar;
- Em Configurar Rede, escolha Default Switch e clique em Avançar;
- Em Conectar Disco Rígido Virtual, especifique o nome, a localização e o tamanho da VM, clique em Avançar;
- Revise as opções e conclua as configurações se tudo estiver OK;
- Após criada, a VM ficará visível na aba de Máquinas Virtuais;
- Instale o sistema operacional desejado clicando na VM desejada, acesse a aba Mídia e selecione a unidade de disco ou o ISO com o sistema operacional desejado;
- Clique em Iniciar e aguarde a instalação.
*O precesso deve ser repetido na criação de outras máquinas virtuais.*
# Hypervisor do tipo 2
A prática acima é considerada hypervisor do tipo 2 devido à necessidade de operar sob o sistema operacional (host) para criar máquinas virtuais.
# Configuração para que um servidor suporte três máquinas virtuais como as apresentadas no artigo de base
Há a necessidade de realizar um upgrade nos tamanhos da memória RAM e do disco rígido para aprimorar a performance nas atividades exercidas pela empresa.

