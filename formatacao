# RELATORIOS MANUTENÇÃO E MONTAGEM DE COMPUTADORES
## AULA 6 26/10/2023
### ANDRESSA GOMES

## INSTALAÇÃO DE SISTEMA OPERACIONAL
O sistema operacional é um sistema básico. Ele é essencial para o funcionamento completo de todos os hardwares conectados à placa mãe. É o sistema operacional que dá vida aos dispositivos como mouse, teclado, placa de áudio e vídeo, etc.
Um computador com sistema operacional instalado permite instalar outros softwares (conhecidos também como aplicativos) tais como: Word, Excel, PowerPoint, Photoshop, etc. Sem um sistema operacional não é possível instalar nenhum desses softwares.
BIOS – Basic Input Output System – Conhecido também como firmware, ou simplesmente BIOS, é um sistema extremamente simples no qual pode-se realizar apenas configurações de baixo nível como, por exemplo, alteração de data e hora, local o sistema operacional vai iniciar (por exemplo, drive de DVD e só então acessar o HD).

## Freeze S.O
O Freeze tem como base a tecnologia MP (Multi Polar Magnetic Pulse). A ponteira emite pulsos magnéticos que estimulam a produção de hormônios como o FGF2, responsáveis pelo crescimento dos vasos sanguíneos. Em paralelo, a radiofrequência do aparelho aquece a pele e estimula a produção de colágeno.
Em cada sessão, a região tratada passa por uma limpeza e a aplicação de um gel. O profissional faz movimentos suaves com o aparelho para garantir que a temperatura fique controlada.
Cada sessão dura entre 20 a 40 minutos. A frequência pode variar de acordo com diversos fatores, como a região tratada, os objetivos da cliente e o tipo de corpo. Em geral, são necessárias de 3 a 10 sessões. Após o fim do tratamento, recomenda-se fazer sessões pelo menos uma vez ao ano para manter o resultado.

## MBR

MBR significa “Master Boot Record”, é o método mais antigo de particionamento, permite a criação de até 4 partições primárias. O MBR é recomendado em sistemas operacionais mais antigos, até o Windows 8.1, e é a única opção em processadores de 32-bits.
Uma limitação da partição MBR se apresenta pelo aumento da capacidade de armazenamento das novas gerações de HD e SSD. O MBR limita a leitura e o reconhecimento de cada partição em 2TB. No caso de uma partição ultrapassar esse limite, a parte que está para além dos 2TB torna-se desconhecida e inutilizável.

## GPT

GPT significa “GUID Partition Table”, é um modelo mais atual de partição de HD ou SSD, por apresentar vantagens em relação ao MBR, deve ser utilizado sempre que for possível. Entretanto, o GPT só pode ser utilizado em processadores 64-bit e em sistemas operacionais posteriores ao Windows 8.1.
O GPT possibilita até 128 partições no sistema operacional do Windows e em sistemas Linux, esse número ainda pode ser acrescido. O limite de leitura das partições no GPT é de 9,4 ZB, o que faz com que, na prática, seja ilimitado.

## Partição Logica

Particionamento lógico é a capacidade de fazer um servidor ser executado como se fosse dois ou mais servidores independentes. Quando você particiona logicamente um servidor, divide os recursos no servidor em subconjuntos denominados partições lógicas. Você pode instalar o software em uma partição lógica, e ela é executada como um servidor lógico independente com os recursos que foram alocados a ela.

Você pode designar processadores, memória e dispositivos de entrada/saída para partições lógicas. É possível executar o sistema operacional AIX, IBM® i, Linux, e o Servidor de E/S Virtual em partições lógicas. O Servidor de E/S Virtual fornece recursos de E/S virtuais para outras partições lógicas com sistemas operacionais para fins gerais.

As partições lógicas compartilham alguns atributos de sistema, como o número de série do sistema, o modelo do sistema e o código de recurso do processador. Todos os outros atributos de sistema podem variar de uma partição lógica para outra.

É possível criar um máximo de 1000 partições lógicas em um servidor. Você deve utilizar ferramentas para criar partições lógicas em seus servidores. A ferramenta que você utiliza para criar partições lógicas em cada servidor depende do modelo do servidor e dos sistemas operacionais e recursos que você deseja utilizar no servidor.

## Partição Primaria
Partição primária é a partição do disco rígido onde o sistema operacional Windows e outros dados podem ser armazenados, e é a única partição que pode ser definida como ativa. Ela pode ser definida como ativa para que o BIOS possa localizá-la, e os arquivos de inicialização salvos na partição primária devem ser definidos como ativos. Caso contrário, o Windows não poderá ser inicializado. Além disso, apenas uma partição primária em um disco rígido pode ser definida como ativa por vez. Um disco MBR só pode conter, no máximo, 4 partições primárias ou 3 partições primárias e 1 partição estendida.

## Partição Estendida
Isso mesmo, no singular. Só pode haver uma partição estendida em cada disco. Uma partição estendida é um tipo especial de partição primária que não pode conter um sistema de arquivos. Ao invés disso, ela contém partições lógicas. Se existir uma partição estendida, ela toma o lugar de uma das partições primárias, podendo haver apenas três.
Se houver, por exemplo, três partições no disco, sendo duas primárias e uma estendida, o esquema de nomes ficará assim:
* /dev/hda1 (Primária)
* /dev/hda2 (Primária)
* /dev/hda3 (Estendida)

## Partição Swap
a partição Swap é um espaço restrito que armazena uma quantidade de memória física a ser utilizada quando o sistema operacional fica sobrecarregado. É como uma válvula de escape para o computador, a qual evita a queda de desempenho, travamentos e desligamentos automáticos.
Um detalhe importante sobre o Swap é que o espaço reservado a ele é definido pelo próprio usuário.
Por um lado, temos plena liberdade para configurá-lo como bem entendermos. Por outro, é necessário cautela na hora de analisar a capacidade que dedicará à partição, a qual varia de acordo com o kernel.


# REFERÊNCIA
O Sistema Operacional Windows 10. ([s.d.]). Com.br. Recuperado 23 de novembro de 2023, de https://trilhante.com.br/curso/windows-10/aula/o-sistema-operacional-windows-10

Finaformablog, P. (2020, dezembro 23). Tudo o que você precisa saber sobre Freeze. Fina Forma. https://www.finaforma.com.br/blog/tudo-sobre-freeze/

Qual a diferença entre as partições MBR e GPT e qual a melhor? (2020, novembro 30). Significados. https://www.significados.com.br/mbr-ou-gpt/

IBM Documentation. (2021, março 1). Ibm.com. https://www.ibm.com/docs/pt-br/power8?topic=partitioning-logical-partition-overview

Partição Primária X Unidade Lógica: Seus Recursos Específicos. (2020, setembro 16). MiniTool. https://www.minitool.com/pt/particao-disco/particao-primaria-x-unidade-logica.html

Diferenças entre partição Primária, Estendida e Lógica. (2011, outubro 8). carlosmiquelon. https://carlosmiquelon.wordpress.com/2011/10/08/diferencas-entre-particao-primaria-estendida-e-logica/

Partição SWAP: Tudo Que Você Precisa Saber Para Criar E Gerenciar Esse Tipo de Partição No Linux. (2019, março 22). E-tinet. https://e-tinet.com/particao-swap/

