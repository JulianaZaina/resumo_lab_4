# resumo_lab_4
Resumo de aprendizagem Lab 4: Construindo Arquiteturas no Azure (módulo 2)

## Bootcamp Microsoft Azure Essentials AZ-900
  
Lab 4: Módulo2 Arquitetura e serviços Azure - componentes de arquiteturas do Azure: regiões e zonas de disponibilidade; assinaturas e grupos de recursos.
  Componentes de Arquitetura do Microsoft Azure:
  -  Regiões, pares de regiões, regiões soberanas do Azure
  -  Zonas de disponibilidade
  -  Datacenters do azure
  -  Os recursos e os grupos de recursos do Azure
  -  As assinaturas
  -  Grupos de gerenciamento
  -  A hierarquia de grupos de recursos, assinaturas e grupos de gerenciamento
    Contas do Azure
  - Conta do Azure (individual) Contas gratuitas do Azure (nem todos os benefícios, regiões estão disponíveis)
  - Conta de estudante gratuita do azure
  - Área restrita do Microsoft Learn (laboratórios e apoio à trilhas de certificação)
 Regiões: criar recursos em qualquer lugar, abrangência global.
  - As regiões são compostas de um ou mais datacenters muito próximos, fornecem flexibilidade e escala para reduzir a latência do cliente.
  - As regiões preservam a residência dos dados com uma oferta abrangente de conformidade. Observação quanto à situações de desastre, recorrer para uma região par.
  - Lei de Geral de Proteção de Dados (LGPD) não pode colocar fora do Brasil as Zonas de Disponibilidade (Z1, Z2, Z3) computadores físicos (máquinas- host)
  - Cada datacenter é equipado com alimentação, resfriamento e redes independentes, conectadas por meio de redes privadas (microsoft) de fibra óptica.
  - Pares de Regiões: No mínimo 300 milhas de separação entre pares de regiões, com replicação automática para alguns serviços.
  - Recuperação de região priorizada em caso de interrupção. Uma região par para cada região existente.
  - Desastre recovery, opção de mantê-lo ativo em outra região e Plano de desastre, caso tenha um, senão esperar o tempo de maturidade passar.
