# ⚙️ Algoritmos em Sistemas Distribuídos

Este documento lista os algoritmos que estou implementando em cada disciplina, com seus objetivos e critérios de aceitação.

---

## 🗳️ Algoritmos de Eleição
- [ ] **Bully Algorithm**  
  Objetivo: escolher um coordenador entre processos distribuídos.  
  Critério: processo com maior ID eleito após falha do coordenador.

- [ ] **Chang & Roberts**  
  Objetivo: eleição eficiente em topologia anel.  
  Critério: líder eleito corretamente após propagação de mensagens.

---

## 🔒 Exclusão Mútua Distribuída
- [ ] **Ricart–Agrawala**  
  Objetivo: garantir acesso exclusivo à seção crítica sem servidor central.  
  Critério: processo só entra na CS após receber todas as respostas.

- [ ] **Maekawa**  
  Objetivo: reduzir número de mensagens necessárias para acesso à CS.  
  Critério: quóruns definidos corretamente e exclusão mútua garantida.

---

## ⏱️ Relógios Lógicos
- [ ] **Relógios de Lamport**  
  Objetivo: estabelecer ordem consistente de eventos sem relógio global.  
  Critério: timestamps atualizados corretamente em cada evento.

- [ ] **Relógios Vetoriais**  
  Objetivo: detectar relações de causalidade entre eventos.  
  Critério: vetores atualizados e comparados corretamente.

---

## 🤝 Consenso Distribuído
- [ ] **Paxos**  
  Objetivo: garantir acordo entre múltiplos nós em um valor único.  
  Critério: consenso alcançado mesmo com falhas parciais.

- [ ] **Raft**  
  Objetivo: replicação de logs consistente entre servidores.  
  Critério: líder eleito e logs replicados corretamente.

---

## 📡 Protocolos de Replicação
- [ ] **Quorum-based protocols**  
  Objetivo: manter dados replicados consistentes entre servidores.  
  Critério: leituras e escritas respeitam interseção de quóruns.

- [ ] **Primary-backup**  
  Objetivo: garantir consistência e disponibilidade dos dados.  
  Critério: backups atualizados corretamente após operações no primário.

---

## 📤 Comunicação e Ordenação
- [ ] **Total Order Broadcast**  
  Objetivo: garantir que todos os processos recebam mensagens na mesma ordem.  
  Critério: mensagens entregues em ordem consistente.

---

## ❤️‍🩹 Detectores de Falhas
- [ ] **Heartbeat**  
  Objetivo: identificar quando um nó deixa de responder.  
  Critério: falhas detectadas após ausência de batimentos.

- [ ] **Gossip-based failure detector**  
  Objetivo: aumentar robustez e escalabilidade da detecção.  
  Critério: falhas propagadas corretamente entre nós.

---

## ⚖️ Balanceamento
- [ ] **Balanceamento de carga**  
  Objetivo: distribuir tarefas entre servidores.  
  Critério: tarefas distribuídas de forma equilibrada.
