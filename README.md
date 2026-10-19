# 🫀 Anatomia de um Pico

Jogo em pixel art, estilo anos 90, que reencena atendimentos **reais** registrados pelo sistema multiagente **CardioIA**, projeto acadêmico da FIAP (Graduação em Inteligência Artificial · Fase 6).

## ▶️ Jogar

**https://flahbocchino.github.io/anatomia-de-um-pico/**

Funciona no navegador do computador e do celular. Não é preciso instalar nada.

## 🎮 Como jogar

1. Clique em **PRESS START** e escolha um paciente.
2. Chute o risco dele: **baixo**, **moderado** ou **alto**.
3. Acompanhe a equipe correndo pelo corredor do Hospital Graça Cardíaca. Pule as macas com **espaço**, **seta para cima** ou um **toque** na tela.
4. Em cada sala, uma caixa de diálogo mostra o que o sistema fez de verdade: a ferramenta chamada, o handoff entre agentes e os números do atendimento.
5. No final, veja o resultado completo e o placar **Interno vs CardioIA**.

## 🏥 A equipe do plantão

| Personagem | Papel no sistema |
|---|---|
| Dr. Ricardo Uéber | Orquestrador: recebe o paciente e encaminha o caso |
| Dra. Cristiana Yeng | Analista de Risco: consulta o modelo de Machine Learning |
| Dra. Mirandinha Beilei | Especialista em Protocolos: aplica as regras clínicas |
| Dra. Meredite Grei | Planejadora de Resposta: monta a recomendação final |
| Dr. Burco | Validação de saída e auditoria (a "Caixa-Preta") |

## 📼 De onde vêm os dados

O jogo **não chama nenhuma API** e **não contém chaves**. Ele apenas lê os registros gravados pela "Caixa-Preta", o log de governança do sistema, que guarda para cada atendimento a probabilidade de risco, a classificação, os protocolos (com o motivo de cada um), os agentes acionados e o resultado da auditoria.

Cada paciente traz um selo:
- **MODO AGENTES:** atendimento feito pela equipe completa de agentes de IA.
- **MODO SEGURANÇA:** a API do modelo de linguagem estava indisponível; o modelo de ML e as regras continuaram funcionando, e o motivo ficou registrado.

## 👩‍💻 Autora

**Flavia Bocchino** · FIAP · Graduação em Inteligência Artificial

---

> ⚠️ Protótipo acadêmico com **dados 100% sintéticos**. Apoio à decisão; **não substitui avaliação médica**.
> Os personagens são paródia/homenagem, sem fins comerciais e sem afiliação com nenhuma série.
