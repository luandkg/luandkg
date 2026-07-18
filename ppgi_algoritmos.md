# ⚙️ Algoritmos em Sistemas Distribuídos

Este documento lista os algoritmos que estou implementando em cada disciplina, com seus objetivos, critérios de aceitação e links para o código-fonte.

---

## 🗳️ Algoritmos de Eleição
- [ ] [**Bully Algorithm**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/bully)  
  Objetivo: escolher um coordenador entre processos distribuídos.  
  Critério: processo com maior ID eleito após falha do coordenador.

- [ ] [**Chang & Roberts**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/chang_roberts)  
  Objetivo: eleição eficiente em topologia anel.  
  Critério: líder eleito corretamente após propagação de mensagens.

---

## 🔒 Exclusão Mútua Distribuída
- [ ] [**Ricart–Agrawala**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/ricart_agrawala)  
  Objetivo: garantir acesso exclusivo à seção crítica sem servidor central.  
  Critério: processo só entra na CS após receber todas as respostas.

- [ ] [**Maekawa**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/maekawa)  
  Objetivo: reduzir número de mensagens necessárias para acesso à CS.  
  Critério: quóruns definidos corretamente e exclusão mútua garantida.

---

## ⏱️ Relógios Lógicos
- [ ] [**Relógios de Lamport**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/lamport)  
  Objetivo: estabelecer ordem consistente de eventos sem relógio global.  
  Critério: timestamps atualizados corretamente em cada evento.

- [ ] [**Relógios Vetoriais**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/vetoriais)  
  Objetivo: detectar relações de causalidade entre eventos.  
  Critério: vetores atualizados e comparados corretamente.

---

## 🤝 Consenso Distribuído
- [ ] [**Paxos**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/paxos)  
  Objetivo: garantir acordo entre múltiplos nós em um valor único.  
  Critério: consenso alcançado mesmo com falhas parciais.

- [ ] [**Raft**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/raft)  
  Objetivo: replicação de logs consistente entre servidores.  
  Critério: líder eleito e logs replicados corretamente.

---

## 📡 Protocolos de Replicação
- [ ] [**Quorum-based protocols**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/quorum)  
  Objetivo: manter dados replicados consistentes entre servidores.  
  Critério: leituras e escritas respeitam interseção de quóruns.

- [ ] [**Primary-backup**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/primary_backup)  
  Objetivo: garantir consistência e disponibilidade dos dados.  
  Critério: backups atualizados corretamente após operações no primário.

---

## 📤 Comunicação e Ordenação
- [ ] [**Total Order Broadcast**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/total_order_broadcast)  
  Objetivo: garantir que todos os processos recebam mensagens na mesma ordem.  
  Critério: mensagens entregues em ordem consistente.

---

## ❤️‍🩹 Detectores de Falhas
- [ ] [**Heartbeat**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/heartbeat)  
  Objetivo: identificar quando um nó deixa de responder.  
  Critério: falhas detectadas após ausência de batimentos.

- [ ] [**Gossip-based failure detector**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/gossip)  
  Objetivo: aumentar robustez e escalabilidade da detecção.  
  Critério: falhas propagadas corretamente entre nós.

---

## ⚖️ Balanceamento
- [ ] [**Balanceamento de carga**](https://github.com/luandkg/mestrado_unb_ppgi/tree/main/sd/algoritmos/balanceamento)  
  Objetivo: distribuir tarefas entre servidores.  
  Critério: tarefas distribuídas de forma equilibrada.
