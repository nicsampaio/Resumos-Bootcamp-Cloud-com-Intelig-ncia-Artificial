# Resumos-Bootcamp-Cloud-com-Inteligencia-Artificial
Repositório para armazenar resumos, anotações e dicas sobre o uso da Azure

# Introdução a Nuvem

## O que é Cloud?

- A **computação em nuvem** é um modelo de entrega de **serviços de tecnologia** em que recursos como **armazenamento**, **processamento de dados**, **software**, **redes** e muito mais são fornecidos pela internet, em vez de ficarem em servidores e data centers próprios.
- Com a nuvem, empresas e usuários podem acessar e utilizar esses recursos sob demanda, pagando apenas pelo que utilizam. Isso elimina a necessidade de investir em **infraestrutura física** cara e difícil de manter.
- A computação em nuvem permite **escala**, **flexibilidade** e **agilidade**, além de possibilitar o acesso a esses recursos de qualquer lugar e a qualquer momento.
- Os principais tipos de nuvem incluem a **pública**, a **privada** e a **híbrida**, cada uma com suas características e aplicações específicas.

## Infraestrutura

- Infraestrutura refere-se ao conjunto de recursos físicos ou virtuais necessários para o funcionamento de sistemas de TI. Inclui servidores, redes, armazenamento, e outras tecnologias essenciais para suportar aplicativos e operações de uma organização. Modelos de infraestrutura podem variar entre on-premise, cloud, ou híbrida, dependendo das necessidades e estratégias da empresa.

### **On-Premise (Local)**

- O modelo **on-premise** refere-se à **infraestrutura física** e aos sistemas de **TI** que são instalados, mantidos e gerenciados dentro das instalações da própria empresa, ou seja, em um **data center local**.
- Nesse modelo, todas as operações e dados ficam sob o **controle total** da empresa, que é responsável pela compra, manutenção e operação de **servidores**, **software**, **rede** e outros recursos.
- Apesar de oferecer maior **controle** e **segurança** (pois os dados ficam dentro da empresa), o modelo on-premise exige **investimentos altos** em equipamentos, espaço físico e mão de obra especializada para manutenção.
- **Vantagens**: Maior controle e personalização.
- **Desvantagens**: Custos altos de manutenção e necessidade de espaço físico.

### **Modelo Cloud (Nuvem)**

- O **modelo cloud** (ou modelo de nuvem) é uma **infraestrutura baseada na internet**, onde a empresa ou o usuário utiliza **recursos de TI** de um provedor externo.
- Em vez de ter servidores, bancos de dados e outros sistemas dentro de suas instalações, as empresas **alugam** esses serviços de **fornecedores de nuvem**, como **Amazon Web Services (AWS)**, **Microsoft Azure** ou **Google Cloud**. Isso permite a **escalabilidade**, ou seja, é possível aumentar ou diminuir a capacidade dos serviços de acordo com a necessidade, sem a necessidade de investir em infraestrutura própria.
- Além disso, o modelo de nuvem permite **reduzir custos**, melhorar a **agilidade** e **acessar serviços avançados** que seriam difíceis de implementar localmente.
- **Vantagens**: Custos mais baixos, escalabilidade e flexibilidade.
- **Desvantagens**: Dependência da conexão com a internet.

### **Modelo Hybrid (Híbrido)**

- O modelo **híbrido** combina os benefícios dos modelos **on-premise** e **cloud**. Nesse caso, uma empresa mantém parte de sua infraestrutura local, enquanto usa **serviços de nuvem** para outras operações, criando uma combinação de **recursos internos e externos**.
- Por exemplo, uma empresa pode manter dados sensíveis em servidores próprios (on-premise) e, ao mesmo tempo, usar a nuvem para hospedar aplicativos ou serviços que exigem mais escalabilidade.
- O modelo híbrido oferece **flexibilidade**, permitindo que as empresas escolham o que é melhor em cada situação. No entanto, esse modelo também exige **gestão mais complexa**, pois é necessário integrar e monitorar tanto a infraestrutura local quanto os recursos na nuvem.
- **Vantagens**: Flexibilidade de escolher o que fica onde, de acordo com as necessidades.
- **Desvantagens**: Complexidade na gestão.

## **Serviços**

### **O que são os Modelos de Serviço em Nuvem?**

- Modelos de serviço em nuvem definem o nível de controle que a empresa tem sobre a infraestrutura e os serviços fornecidos pelo provedor de nuvem. Eles ajudam a escolher a solução mais adequada às necessidades do negócio, podendo envolver diferentes níveis de abstração e responsabilidades.

- **Golden Rules**: Regras universais para escolher e implementar os modelos de serviço com base nas necessidades de controle, custo e escalabilidade.
Exemplo: "Escolha o modelo de serviço adequado conforme o nível de controle necessário."
- **House Rules**: Regras específicas para cada organização com base em sua arquitetura e objetivos. Exemplo: "Para aplicativos mais complexos, prefira PaaS para abstração e gerenciamento facilitado."



# Introdução aos Conceitos Básicos do Microsoft Azure

## Comparar CapEx e OpEx

- Despesas de capital (CapEx):

> O gasto inicial de dinheiro em infraestrutura física.
> 

> As despesas do CapEx têm um valor que se reduz com o tempo.
> 
- Depesas operacionais (OpEx)

> Gastar com produtos e serviços conforme necessário, pagmento conforme o uso.
> 

> Seja cobrado imediatamente.
> 

## **Modelo baseado em consumo**

- Os provedores de serviços em nuvem operam em um modelo baseado no consumo,  o que significa que os usuários finais pagam somente pelos recursos que usam.
- Melhor previsão de custos.
- São fornecidos preços para recursos e serviços individuais.
- A cobrança é feita com base no seu uso real.



# Benefícios da NUVEM

## Alta disponibilidade

- A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.
- O Azure é um ambiente de nuvem altamente disponível com garantias de tempo de atividade, dependendo do serviço.
- Essas garantias fazem parte dos SLAs (Contratos de Nível de Serviço).

## Escabilidade

- A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda.
- A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
- O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços.
- Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa.
- Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.
- Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual.

## Elasticidade

- Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente).
- Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão.
- Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).

## Confiabilidade

- Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente.
- Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo.
- Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.

## Previsibilidade

- A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework.

## Segurança

- A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.
- Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção.
- Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.

## Governança

- A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação.
- Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
- Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

## Gerenciabilidade

- Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem que você aprenderá nesta série e ambos trazem excelentes benefícios.

**O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Por exemplo:**

- Escalar automaticamente a implantação de recursos com base na necessidade.
- Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.

**O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Por exemplo:**

- Por meio de um portal da Web.
- Usando uma interface de linha de comando.
- Usando APIs.
- Usando o PowerShell.
