<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> AZ-900 : Introdução aos Conceitos Básicos do Microsoft Azure</span>
</h1>

## Objetivo
Resumo dos conceitos visto na primeira parte do curso Microsoft Azure Essentials. <br> ![Azure](https://img.shields.io/badge/Azure-blue?style=for-the-badge&logo=microsoft%20azure&logoColor=blue&labelColor=FFFFFF&link=https%3A%2F%2Fimages.app.goo.gl%2FK7PN1jYJd57x4q7A8)

## O que é a computação em nuvem?
A computação em nuvem é o fornecimento de serviços de computação pela Internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala.

## Nuvem privada
As organizações criam um ambiente em nuvem em seu datacenter.<br>
As organizações são responsáveis por operar os serviços que fornecem.<br>
Não fornece acesso aos usuários fora da organização.<br>
As organizações têm controle total sobre os recursos e a segurança.<br> 
As organizações são responsáveis pela manutenção e pelas atualizações de hardware.

## Nuvem pública
Pertencente a serviços de nuvem ou provedor de hosting.<br>
Fornece recursos e serviços a várias organizações e usuários.<br>
Acessada via conexão de rede segura  (geralmente pela Internet).<br>
Nenhuma despesa de capital para escalar verticalmente.<br>
Os aplicativos podem ser provisionados e desprovisionados rapidamente.<br>
As organizações pagam apenas pelo que utilizam.

## Nuvem híbrida
Combina nuvens públicas e privadas para permitir que os aplicativos sejam executados no local mais adequado.<br>
As organizações determinam onde executar seus aplicativos.<br>
As organizações controlam a segurança, a conformidade e os requisitos legais.<br>
Fornece a maior flexibilidade.

## Nuvem multicloud
Redes multicloud referem-se à utilização de várias plataformas de nuvem de diferentes provedores para atender às necessidades de uma organização. 

## CapEx e OpEx
CapEx (Despesas de capital) e OpEx (Despesas operacionais ) são dois conceitos financeiros amplamente utilizados para classificar os gastos de uma empresa. A diferença principal está em como os recursos são alocados e contabilizados.

## Despesas operacionais (OpEx)
O gasto inicial de dinheiro em infraestrutura física.<br>
As despesas do CapEx têm um valor que se reduz com o tempo.

## Despesas operacionais (OpEx)
Gastar com produtos e serviços conforme necessário, pagamento conforme o uso.<br>
Seja cobrado imediatamente

## Modelo baseado em consumo
Os provedores de serviços em nuvem operam em um modelo baseado no consumo,  o que significa que os usuários finais pagam somente pelos recursos que usam.<br>
Melhor previsão de custos.<br>
São fornecidos preços para recursos e serviços individuais.<br>
A cobrança é feita com base no seu uso real.

<h1>
    <span> Benefícios da nuvem</span>
</h1>


## Alta disponibilidade
Quando você está implantando um aplicativo, um serviço ou qualquer recurso de TI, é importante que os recursos estejam disponíveis quando necessário. A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.

## Escalabilidade
Outro grande benefício da computação em nuvem é a escalabilidade dos recursos de nuvem. A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda. Se você experimentar um pico repentino de tráfego e seus sistemas ficarem sobrecarregados, a capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.

## Confiabilidade
Resiliência é a capacidade que um sistema tem de se recuperar de falhas e continuar funcionando. Ela também é um dos pilares do Microsoft Azure Well-Architected Framework.<br>

Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo. Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento. Você pode criar aplicativos para aproveitar automaticamente essa confiabilidade maior. Em alguns casos, o próprio ambiente de nuvem mudará automaticamente para uma região diferente, sem que você precise realizar nenhuma ação.

## Previsibilidade
A previsibilidade na nuvem permite que você avance com confiança. A previsibilidade pode se concentrar na previsibilidade de desempenho ou na previsibilidade de custo. Tanto a previsibilidade de desempenho quanto a de custo são bastante influenciadas pelo Microsoft Azure Well-Architected Framework.<br>

### Desempenho
A previsibilidade de desempenho se concentra em prever os recursos necessários para oferecer uma experiência positiva aos clientes. O dimensionamento automático, o balanceamento de carga e a alta disponibilidade são apenas alguns dos conceitos de nuvem que dão suporte à previsibilidade de desempenho. Se de repente você precisar de mais recursos, o dimensionamento automático poderá implantar recursos adicionais para atender à demanda e depois reduzir a implantação quando a demanda cair. Ou se o tráfego estiver bem concentrado em uma área, o balanceamento de carga ajudará a redirecionar parte da sobrecarga para áreas menos sobrecarregadas.

### Custo
A previsibilidade de custos se concentra em prever o custo dos gastos com a nuvem. Com a nuvem, você pode acompanhar o uso de recursos em tempo real, monitorar os recursos para garantir a maior eficiência de uso possível e aplicar a análise de dados para encontrar padrões e tendências que ajudam a planejar melhor as implantações de recursos. Operando na nuvem e usando a análise e as informações da nuvem, você pode prever custos futuros e ajustar os recursos conforme o necessário. Você pode até mesmo usar ferramentas como TCO (custo total de propriedade) ou a Calculadora de Preços para obter uma estimativa de possíveis gastos com a nuvem.

## Segurança
<ul>
	<li>
		A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente. 
	</li>
	<li>
		Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção. 
	</li>
	<li>	
		Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.
	</li>	
</ul>

## Governança
A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação. <br>
Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.<br>
Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.	

## Gerenciabilidade 
Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem

### Gerenciamento da nuvem
O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Na nuvem, você pode:
<ul>
	<li>
		Escalar automaticamente a implantação de recursos com base na necessidade.
	</li>
	<li>
		Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
	</li>
	<li>	
		Monitorar a integridade dos recursos e substituir automaticamente os recursos com falha.
	</li>	
	<li>	
		Receber alertas automáticos com base em métricas configuradas, de modo a ficar ciente do desempenho em tempo real.
	</li>	
</ul>

### Gerenciamento na nuvem
O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Você pode gerenciá-los:
<ul>
	<li>
		Por meio de um portal da Web.
	</li>
	<li>
		Usando uma interface de linha de comando.
	</li>
	<li>	
		Usando APIs.
	</li>	
	<li>	
		Usando o PowerShell.
	</li>	
</ul>

<h1>
    <span> Tipos de Serviço de Nuvem  	</span>
</h1>

## IaaS (infraestrutura como serviço)
Crie uma infraestrutura de TI de pagamento conforme o uso alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.
<ul>
	<li>
		O serviço de nuvem mais flexível.
	</li>
	<li>
		Você configura e gerencia o hardware para seu aplicativo.
	</li>
</ul>


## PaaS (plataforma como serviço)
Fornece um ambiente para a criação, o teste e a implantação de aplicativos de software, sem focar no gerenciamento da infraestrutura subjacente.
<ul>
	<li>
		Focado no desenvolvimento de aplicativos.
	</li>
	<li>
		O gerenciamento de plataforma é realizado pelo provedor de nuvem.
	</li>
</ul>

## SaaS
Os usuários se conectam e usam aplicativos com base em nuvem pela Internet: por exemplo, Microsoft Office 365, email e calendários.
<ul>
	<li>
		Modelo de preço de pagamento conforme o uso.
	</li>
	<li>
		Os usuários pagam pelo software que utilizam em um modelo de assinatura.
	</li>
</ul>

## Modelo de responsabilidade compartilhada

![image](https://github.com/user-attachments/assets/650af68c-e954-4a8f-85c1-a0c670770ff9)

<h1>
    <span> Arquitetura e serviços do Azure 	</span>
</h1>

## Regiões
O Azure oferece mais regiões globais do que qualquer outro provedor de nuvem, com mais de 60 regiões representando mais de 140 países.

<ul>
	<li>
		As regiões são compostas de um ou mais datacenters muito próximos.
	</li>
	<li>
		Eles fornecem flexibilidade e escala para reduzir a latência do cliente.
	</li>
	<li>
		As regiões preservam a residência dos dados com uma oferta abrangente de conformidade.
	</li>	
</ul>


## Zonas de disponibilidade

<ul>
	<li>
		Fornece proteção contra tempo de inatividade devido a falha do datacenter.
	</li>
	<li>
		Separe fisicamente os datacenters dentro da mesma região.
	</li>
	<li>
		Cada datacenter é equipado com alimentação, resfriamento e rede independentes.
	</li>	
	<li>
		Conectadas por meio de redes privadas de fibra óptica.
	</li>	
</ul>


## Pares de Regiões

<ul>
	<li>
		No mínimo 300 milhas de separação entre pares de regiões.
	</li>
	<li>
		Replicação automática para alguns serviços.
	</li>
	<li>
		Recuperação de região priorizada em caso de interrupção.
	</li>	
	<li>
		As atualizações são distribuídas sequencialmente para minimizar o tempo de inatividade
	</li>	
	<li>
		Link da Web : https://aka.ms/PairedRegions-ptb 
	</li>	

</ul>

## Regiões soberanas do Azure

### Serviços Governamentais dos EUA

<ul>
	<li>
		Atende às necessidades de segurança e conformidade das agências federais, governos estaduais e locais dos EUA e seus provedores de soluções.
	</li>
</ul>

## Azure Governamental

<ul>
	<li>
		Instância separada do Azure.
	</li>
	<li>
		Fisicamente isolada de implantações que não sejam do governo dos EUA.
	</li>
	<li>
		Acessível somente a pessoal verificado e autorizado.
	</li>
</ul>

## Recursos do Azure

<ul>
	<li>
		Os recursos do Azure são componentes como armazenamento, máquinas virtuais e redes que estão disponíveis para criar soluções de nuvem.
	</li>
</ul>


## Grupos de recursos
<ul>
	<li>
		Um grupo de recursos é um contêiner que você usa para gerenciar e agregar recursos em uma única unidade.
	</li>
	<li>
		Os recursos podem existir em apenas um grupo de recursos.
	</li>
	<li>
		Os recursos podem existir em diferentes regiões.
	</li>
	<li>
		Os recursos podem ser movidos para diferentes grupos de recursos.
	</li>
	<li>
		Os aplicativos podem utilizar vários grupos de recursos.
	</li>	
</ul>

## Assinaturas do Azure
<ul>
	<li>
		Uma assinatura do Azure fornece a você acesso autenticado e autorizado às contas do Azure.
	</li>
</ul>

### Limite de cobrança: 
Gere relatórios de cobrança e faturas separados para cada assinatura.

### Limite do controle de acesso: 
Gerenciar e controlar o acesso aos recursos que os usuários podem provisionar com assinaturas específicas.

## Grupos de gerenciamento
<ul>
	<li>
		Os grupos de gerenciamento podem incluir várias assinaturas do Azure.
	</li>
	<li>
		As assinaturas herdam as condições aplicadas ao grupo de gerenciamento.
	</li>
</ul>

<h1>
    <span> Computação e Rede </span>
</h1>

## Serviços de computação do Azure
A Computação do Azure é um serviço sob demanda que fornece recursos de computação, como discos, processadores, memória, rede e sistemas operacionais.


## Máquinas virtuais do Azure


<ul>
	<li>
		As máquinas virtuais do Azure (VMs) são emulações de software de computadores físicos. 
	</li>
	<li>
		Inclui processador virtual, memória, armazenamento e rede.
	</li>
	<li>
		Cada datacenter é equipado com alimentação, resfriamento e rede independentes.
	</li>	
	<li>
		Oferta de IaaS que oferece personalização e controle total.
	</li>	
</ul>


## Conjuntos de dimensionamento de VMs
Os conjuntos de dimensionamento oferecem uma oportunidade de balanceamento de carga para dimensionar os recursos automaticamente. <br>
Dimensionamento (Scale Sets): Focado em escalabilidade automática e aumento da capacidade com várias VMs idênticas.

<ul>
	<li>
		Escalar horizontalmente quando o recurso precisar aumentar.
	</li>
	<li>
		Reduzir horizontalmente quando o recurso precisar diminuir.
	</li>
</ul>

### Exemplo:
Você está executando um site de e-commerce. Durante a Black Friday, quando o tráfego aumenta, o conjunto de dimensionamento automaticamente adiciona mais VMs para lidar com a carga. Após o pico, reduz o número de VMs para economizar custos.

## Conjuntos de disponibilidade de VM
São usados para garantir alta disponibilidade ao distribuir máquinas virtuais por múltiplas domínios de falha e domínios de atualização. Isso reduz o risco de todas as VMs ficarem indisponíveis por falha de hardware ou manutenção.<br>
Disponibilidade (Availability Sets): Focado em redundância e resiliência, garantindo que as VMs estejam distribuídas para minimizar impactos de falhas.

### Exemplo:
Você possui um banco de dados crítico. Para evitar indisponibilidade, suas VMs são distribuídas em um conjunto de disponibilidade. Mesmo que uma zona tenha uma falha, outras VMs continuarão funcionando.


## Área de Trabalho Virtual do Azure
A Área de Trabalho Virtual do Azure é uma virtualização de área de trabalho e aplicativo executada na nuvem.<br>
A Área de Trabalho Virtual do Azure (Azure Virtual Desktop - AVD) é um serviço que permite criar um ambiente de desktop remoto na nuvem. Ele oferece acesso seguro a desktops Windows ou aplicativos, que podem ser acessados de qualquer lugar, usando qualquer dispositivo com internet.<br>
É como ter o seu computador (desktop ou laptop) "rodando" na nuvem, em vez de estar fisicamente na sua mesa. Você pode acessar esse "computador virtual" de qualquer lugar, mantendo seus aplicativos e arquivos disponíveis de forma segura.<br>
O logon de vários clientes permite que vários usuários façam logon no mesmo computador na ao mesmo tempo

## Serviços de contêineres do Azure
Os contêineres do Azure fornecem um ambiente leve e virtualizado que não exige o gerenciamento do sistema operacional e pode responder a alterações sob demanda. <br>
Os Serviços de Contêineres do Azure são ferramentas e plataformas oferecidas pelo Azure para gerenciar, implantar e escalar aplicativos em contêineres. Um contêiner é como uma "caixa" que embala o aplicativo junto com tudo o que ele precisa para funcionar (bibliotecas, dependências, etc.), garantindo que ele rode de forma consistente em diferentes ambientes.<br>
Pense nos contêineres como "mini-servidores" portáteis que você pode mover e executar em qualquer lugar. O Azure oferece serviços que ajudam a rodar e gerenciar esses contêineres de maneira fácil e eficiente.

### Instâncias de Contêiner do Azure: 
Uma oferta de PaaS que executa um contêiner ou pod de contêineres no Azure.

### Aplicativos de Contêiner do Azure: 
Uma oferta de PaaS, como instâncias de contêineres, que pode balancear a carga e escalar.

### Serviço de Kubernetes do Azure:
Um serviço de orquestração para contêineres com arquiteturas distribuídas e grandes volumes de contêineres. 


## Azure Functions
Uma oferta de PaaS que dá suporte a operações de computação sem servidor. <br>
O código baseado em eventos é executado quando chamado, sem exigir uma infraestrutura de servidor durante períodos inativos.<br>
O Azure Function é um serviço de computação baseado em serverless (sem servidor). Ele permite que você execute pequenos pedaços de código (chamados de "funções") em resposta a eventos, sem se preocupar com a infraestrutura subjacente. O Azure gerencia automaticamente os servidores e recursos necessários para executar o código.<br>
Pense no Azure Function como um "assistente automático". Quando algo acontece, como um arquivo ser enviado ou uma mensagem chegar, ele executa o código necessário para lidar com essa ação. Você paga apenas pelo tempo que o código é executado.


## Serviços de Aplicativo do Azure
Os Serviços de Aplicativos do Azure consistem em uma plataforma totalmente gerenciada para criar, implantar e dimensionar aplicativos Web e APIs rapidamente. 

<ul>
	<li>
		Trabalha com .NET, .NET Core, Node.js, Java, Python ou PHP.
	</li>
	<li>
		Oferta de PaaS com requisitos de nível corporativo de desempenho, segurança e conformidade.
	</li>
</ul>

## Serviços de rede do Azure
A Rede Virtual do Azure (VNet) permite que os recursos do Azure se comuniquem uns com os outros, com a Internet e com as redes locais.<br>
Pontos de extremidade públicos, acessíveis de qualquer lugar na Internet.<br>
Pontos de extremidade privados, acessíveis somente de dentro da sua rede.<br>
As sub-redes virtuais segmentam sua rede para atender às suas necessidades.<br>
O emparelhamento de rede conecta suas redes privadas diretamente.

### Gateway de VPN
O Gateway de VPN permite criar uma conexão segura e criptografada entre sua rede local (ou outra rede virtual) e o Azure, usando a internet.<br>

#### Exemplo prático:
Uma empresa quer que seus funcionários acessem recursos na nuvem do Azure (como servidores ou bancos de dados) de forma segura a partir do escritório local. Eles configuram um Gateway de VPN para estabelecer uma conexão protegida via internet.

### ExpressRoute
O ExpressRoute cria uma conexão privada e dedicada entre sua rede local e o Azure, sem passar pela internet. É ideal para alta segurança, baixa latência e transferência de dados em grande escala.

#### Exemplo prático:
Uma instituição financeira com altos requisitos de segurança precisa transferir grandes volumes de dados entre seus servidores locais e o Azure. Ela usa o ExpressRoute para criar uma conexão privada e confiável.<br>

### Diferenças principais entre VPN Gateway e ExpressRoute:
<table border="1" style="border-collapse: collapse; width: 100%; text-align: left;">
  <thead>
    <tr>
      <th style="padding: 8px; background-color: #f2f2f2;">Aspecto</th>
      <th style="padding: 8px; background-color: #f2f2f2;">VPN Gateway</th>
      <th style="padding: 8px; background-color: #f2f2f2;">ExpressRoute</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 8px;">Tipo de conexão</td>
      <td style="padding: 8px;">Criptografada pela internet</td>
      <td style="padding: 8px;">Conexão privada e dedicada</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Segurança</td>
      <td style="padding: 8px;">Boa segurança</td>
      <td style="padding: 8px;">Muito alta segurança</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Velocidade/Latência</td>
      <td style="padding: 8px;">Latência maior, limitada pela internet</td>
      <td style="padding: 8px;">Latência baixa, conexão rápida</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Custo</td>
      <td style="padding: 8px;">Mais acessível</td>
      <td style="padding: 8px;">Mais caro, mas para demandas críticas</td>
    </tr>
  </tbody>
</table>


### DNS do Azure
O Azure DNS é um serviço que permite hospedar zonas DNS e gerenciar os registros DNS de seus domínios. Ele traduz nomes de domínio amigáveis, como www.exemplo.com, em endereços IP, que os computadores utilizam para se conectar.<br>
Com o Azure DNS, você pode configurar os registros DNS para os seus aplicativos, garantindo alta disponibilidade e desempenho.<br>

#### Exemplo prático:
Imagine que você tenha um aplicativo hospedado no Azure em um endereço IP, como 20.45.67.89.

<ul>
	<li>
		Você quer que os usuários acessem o aplicativo digitando www.meusite.com.
	</li>
	<li>
		Com o Azure DNS, você cria um registro A que aponta www.meusite.com para o endereço IP do seu aplicativo.
	</li>
</ul>
Agora, sempre que alguém digitar www.meusite.com, o DNS do Azure traduzirá automaticamente para 20.45.67.89, conectando o usuário ao seu aplicativo.
