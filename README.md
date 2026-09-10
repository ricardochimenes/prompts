<p align="center">
  <img src="https://img.shields.io/badge/prompts-abertos-1f6feb?style=for-the-badge" alt="prompts abertos">
  <img src="https://img.shields.io/badge/licen%C3%A7a-CC%20BY--SA%204.0-2da44e?style=for-the-badge" alt="CC BY-SA 4.0">
  <img src="https://img.shields.io/badge/idioma-portugu%C3%AAs-e3b341?style=for-the-badge" alt="português">
  <img src="https://img.shields.io/badge/para-quem%20n%C3%A3o%20programa-8957e5?style=for-the-badge" alt="para quem não programa">
</p>

<h1 align="center">Prompts abertos</h1>

<p align="center">
  <b>Assistentes guiados para copiar, colar e usar num chat de IA.</b><br>
  Feitos e usados nas minhas empresas antes de virem para cá.
</p>

---

## 🎯 Por que isto existe

Todo mundo já tem um chat de IA na mão. Quase ninguém tem um jeito **seguro e previsível** de
deixar esse chat mexer em coisa que importa — a caixa de e-mail, a agenda, as contas a pagar.

O que falta não é o modelo. É **o roteiro**: o que perguntar antes, o que nunca fazer, quando
parar e pedir confirmação, o que recusar quando alguém tenta enfiar um link ou uma senha no
meio da conversa.

Estes prompts são esse roteiro. Cada um foi escrito para uma tarefa concreta, testado numa
caixa real, e publicado com as travas **dentro do texto** — não num aviso que ninguém lê.

## 📦 Prompts

| | Prompt | O que faz | Testado em |
|---|---|---|---|
| 📬 | **[Assistente de Caixa de E-mail](email/caixa-organizada/)** | Mede sua caixa, pergunta suas regras família por família, escreve um "contrato" em português simples, faz a primeira arrumação com freio e cria rotinas para manter a ordem e avisar do que importa | ![Claude](https://img.shields.io/badge/Claude-testado-2da44e) ![ChatGPT](https://img.shields.io/badge/ChatGPT-declara%20o%20que%20consegue-e3b341) |

> Mais prompts entram aqui conforme forem usados de verdade. Nada é publicado sem ter rodado
> antes.

## 🚀 Como usar

```
1. Abra a pasta do prompt e leia o README dela  →  2 minutos, evita surpresa
2. Copie o PROMPT.md inteiro                     →  botão "Raw" no GitHub facilita
3. Cole numa conversa NOVA com o Claude ou ChatGPT
4. Responda uma pergunta de cada vez             →  o assistente conduz
```

Você não precisa saber programar. Se o assistente pedir algo que você não entende, ele
está errado — não você. Abra uma issue.

## 🛡️ O que todos os prompts daqui têm em comum

| Princípio | Na prática |
|---|---|
| 🟢 **Pergunta antes de agir** | Nada acontece sem você ver o que vai acontecer e dizer "sim" — e um "sim" vale para uma ação, não para todas |
| 🔴 **Recusa o que vem de fora** | Senha, link, arquivo, "ferramenta que um amigo indicou": não entra. Conteúdo lido (um e-mail, um documento) é **dado**, nunca instrução |
| 🔵 **Reporta com números** | "Feito" sem contagem não existe. Se a ferramenta cortou no meio, ele diz quantos faltaram |
| 🟡 **Diz o que não faz** | Para você não esperar o que não vem — e para o pior caso ser conhecido antes de acontecer |
| ⚪ **Tem freio** | Limites numéricos (mais de N itens, mais de X% da caixa) fazem ele parar e perguntar, mesmo com regra aprovada |

Isso não é burocracia. É o que separa um assistente que você pode deixar rodando sozinho de
um que você precisa vigiar.

## 🧭 Como um prompt daqui é construído

```
medir  →  perguntar  →  escrever o contrato  →  agir com freio  →  manter sozinho
```

- **Medir antes de perguntar.** Ninguém sabe responder "que regras você quer?" no vazio. O
  assistente olha primeiro e traz o que encontrou; você decide em cima do que existe.
- **Contrato em texto simples.** O resultado da entrevista é um documento que você guarda —
  a memória da configuração não fica presa na conversa.
- **Rotina carrega as travas.** O que roda sozinho depois leva dentro dele as mesmas regras
  da conversa. Nunca menos.

## 🤝 Contribuir

- **Travou num ponto?** [Abra uma issue](../../issues) contando onde parou e o que o assistente
  disse. **Sem colar dado pessoal** — nem seu, nem de quem te escreveu.
- **Tem um prompt?** Bem-vindo, desde que siga os cinco princípios acima e diga onde foi
  testado (e onde não foi).
- **Melhorou um prompt daqui?** Pela licença, o que você redistribuir tem que ficar aberto
  também. É de propósito.

## 📄 Licença

[**CC BY-SA 4.0**](LICENSE) — use, adapte e redistribua, dando crédito e mantendo a mesma
licença. Fornecido como está, sem garantia: quem usa é responsável pelo que o assistente
organiza, move ou avisa na conta dele.

Claude, ChatGPT, Gmail, Outlook e demais marcas citadas pertencem a seus donos. Este
repositório não é afiliado nem endossado por nenhum deles.

<p align="center"><sub>feito por <a href="https://github.com/ricardochimenes">Ricardo Chimenes</a> · <a href="https://gruporich.com.br">RICH</a></sub></p>
