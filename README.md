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

