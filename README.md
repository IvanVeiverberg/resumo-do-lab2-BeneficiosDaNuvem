# Benefícios da Nuvem Azure
---
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab Criando Máquinas Virtuais na Azure e Benefícios da Nuvem Azure na plataforma DIO

---
## Introdução

Neste laboratório foram apresentados os principais benefícios oferecidos pela nuvem Azure. Desde alta disponibilidade e escalabilidade até segurança e governança, a plataforma permite que organizações aumentem sua eficiência, otimizem custos e mantenham a confiabilidade de seus serviços.

---
## Alta Disponibilidade
- Recursos disponíveis globalmente, sempre que necessário, com garantias de disponibilidade oferecidas pela Microsoft.
- SLA (Acordo de Nível de Serviço): A Microsoft garante 99%, 99.9% ou 99.95% de tempo disponível. Se houver indisponibilidade acima do limite, o usuário pode receber créditos (estorno).
- É possível verificar no portal a situação dos serviços em caso de degradação e consultar as localidades globais para monitorar falhas.
  
## Escalabilidade e Elasticidade
- **Escalabilidade**: Capacidade de expandir recursos verticalmente, por exemplo, adicionando mais espaço de armazenamento. O pagamento é feito apenas pelos recursos usados.
- **Elasticidade**: Permite ajuste automático dos recursos conforme a demanda, ideal para cenários como a Black Friday. Aumenta ou reduz recursos de acordo com o uso, mantendo os custos otimizados.

## Confiabilidade e Resiliência
- Relacionada à recuperação de falhas e continuidade de operação.
- Os recursos podem ser criados globalmente onde a Azure tem datacenters, proporcionando alta disponibilidade.
  
## Previsibilidade
- **Desempenho e Custo**: A migração para a nuvem deve manter a confiança no desempenho constante e custos controlados.
- Empresas que têm processos antigos precisam dessa confiança ao migrar para a nuvem, com casos de sucesso ajudando nessa transição.

## Segurança
- **Responsabilidade Compartilhada**: A segurança na nuvem é uma responsabilidade tanto da Microsoft quanto do usuário.
- A Microsoft oferece ferramentas e serviços para proteger contra ataques e manter os recursos funcionando, mas a implementação dessas medidas é responsabilidade do usuário.

## Governança
- Relacionada à gestão de recursos conforme as normas corporativas e regulatórias.
- Permite o estabelecimento de regras específicas, como a criação de bloqueios de regiões ou limites de criação de recursos. 
- Exemplo: Indústrias farmacêuticas podem precisar seguir regras internas e governamentais rigorosas.

## Gerenciabilidade
- Facilita o gerenciamento de recursos, incluindo escalabilidade automática, criação de alertas e monitoramento de serviços via portal.
- Para uma administração mais avançada, o usuário pode utilizar APIs, linha de comando ou PowerShell.

---

### Considerações Adicionais sobre SLA e Criação de Recursos
- O SLA varia conforme o tipo de recurso. Para recursos nativos com SLA garantido pela Microsoft, caso ultrapasse o limite de inatividade, há ressarcimento. No caso de recursos que o usuário configura, como máquinas virtuais, o ressarcimento pode não ser aplicável.
- O tempo de inatividade permitido varia com o SLA. Recursos com mais "9"s no SLA oferecem menos inatividade.
- Na criação de máquinas virtuais, é possível ajustar a disponibilidade e redundância, o que impacta o SLA e o custo.
- A replicação de dados em várias regiões ou datacenters, como em contas de armazenamento, também influencia a disponibilidade e o SLA, ajudando em situações de desastres e melhorando o tempo de recuperação.
- Falta de alinhamento com o orçamento pode elevar custos, por isso é importante criar uma estratégia bem definida.
