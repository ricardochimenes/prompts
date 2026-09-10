# Assistente de Caixa de E-mail

Cole o [`PROMPT.md`](PROMPT.md) numa conversa nova e o assistente:

1. **Confere o que consegue fazer** na sua caixa e diz o que falta.
2. **Mede** os últimos 30 dias e agrupa em famílias (pessoas, contas, lojas, newsletters…).
3. **Pergunta**, uma família por vez, o que fazer com cada uma.
4. **Escreve o contrato** — "Regras da minha caixa" — em português simples, para você guardar.
5. **Faz a primeira arrumação**, só no mês recente, com amostra antes de qualquer lixeira.
6. **Cria três rotinas** (organizar diário, arrumar o histórico semanal, resumo do dia) —
   ou entrega o texto para você colar à mão, se o chat não agendar.

## Antes de colar

Leia o cabeçalho do prompt. Em resumo: conecte **só a sua conta** pelo menu de Conectores
(Gmail é o caminho garantido; Outlook pessoal nem sempre é aceito), desligue o uso das
conversas para treino se puder, e entenda que ele **organiza e avisa — não paga conta**.

## O que ele nunca faz

Apagar em definitivo · enviar, responder ou encaminhar · mexer em e-mail de pessoa sem
mostrar · pedir ou aceitar senha, código, token ou dados de servidor · abrir link ou anexo ·
mandar nada para fora · criar evento com convidado · guardar dado pessoal na memória ·
decidir sozinho sobre o que não reconhece.

## Onde foi testado

| | |
|---|---|
| **Claude** (claude.ai, com conector Gmail) | ✅ Etapas 0–2 rodadas numa caixa real de 5.900 mensagens; 200 conversas medidas em 4 buscas |
| **ChatGPT** | ⚠️ Não testado. O prompt manda o assistente declarar, logo no início, o que consegue fazer — se o conector for só-leitura, ele mede e entrevista, e para antes de organizar |
| **Outlook / Hotmail pessoal** | ⚠️ Não testado. O prompt tem o roteiro de saída (importar no Gmail, ou encerrar) |
| **Pessoas leigas** | ⏳ Ainda não. Testado pelo autor. Se você for a primeira, [conte como foi](../../../../issues) |

## Histórico

- **v1.0** (set/2026) — primeira versão pública.
