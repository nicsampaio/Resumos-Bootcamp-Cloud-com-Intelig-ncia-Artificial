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
