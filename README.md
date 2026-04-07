# Infraestrutura de Rede Corporativa – Arquitetura Multi-Filiais

![Topologia da Rede](./A3.png)

## Visão Geral
Este projeto apresenta o planejamento e a implementação de uma infraestrutura de rede corporativa, conectando uma matriz a três filiais (Alfa, Beta e Gama).

A arquitetura foi desenvolvida com foco em organização, escalabilidade e comunicação eficiente entre as unidades, utilizando uma estrutura centralizada e distribuição lógica dos recursos de rede.

---

## Arquitetura da Rede
A rede é composta por:

- 1 Matriz atuando como núcleo central  
- 3 Filiais (Alfa, Beta e Gama)  
- Roteador central responsável pela interconexão das unidades  
- Roteadores locais em cada filial  
- Switches para distribuição interna  
- Servidores para serviços de rede  
- Estações de trabalho (PCs) em cada unidade  

Cada filial possui sua própria rede local, mantendo independência estrutural, mas com comunicação garantida entre todas as unidades.

---

## Topologia
A topologia segue um modelo **hierárquico e distribuído**, onde:

- A matriz centraliza a comunicação  
- As filiais se conectam através de roteamento  
- Cada unidade possui sua própria organização interna  

---

## Gerenciamento de Endereçamento IP
Para otimizar a configuração da rede, foi implementado:

- Atribuição automática de endereços IP via servidor  
- Redução de configuração manual  
- Padronização do endereçamento entre os dispositivos  

Essa abordagem aumenta a eficiência e reduz falhas de configuração.

---

## Tecnologias Utilizadas
- Cisco Packet Tracer  
- Conceitos de roteamento  
- Segmentação de redes (LAN/WAN)  
- Arquitetura cliente-servidor  
- Endereçamento IP automatizado  

---

## Principais Funcionalidades
- Comunicação entre matriz e filiais  
- Estrutura de rede organizada e escalável  
- Automação na atribuição de IPs  
- Separação lógica entre redes locais  
- Base para expansão futura da infraestrutura  

---

## Estrutura do Projeto

Matriz
├── Servidor
├── Switch
├── Computadores
└── Conexão com roteador central

Filiais (Alfa, Beta, Gama)
├── Roteador local
├── Servidor
├── Switch
├── Computadores
└── Conexão com a rede principal


---

## Aplicação
Este projeto simula um cenário real de ambiente corporativo, onde múltiplas unidades precisam se comunicar de forma eficiente, mantendo organização e possibilidade de expansão.

