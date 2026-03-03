# 💸 App de Finanças Pessoais com Vibe Coding (Poupaí)

PRD refinado no Copilot Web:

```
📝 PRD – Projeto Poupaí

Contexto
Aplicativo de organização de finanças pessoais via conversas em linguagem natural, eliminando a complexidade de planilhas e formulários. O objetivo é que qualquer pessoa consiga controlar seus gastos de forma simples e intuitiva, apenas conversando com o app.

Problema
Apps atuais exigem muita entrada manual e não se adaptam ao usuário iniciante. Isso desmotiva quem quer começar a organizar suas finanças.

Objetivo
Oferecer uma experiência prática e acessível, onde o usuário fala sobre seus gastos e metas e recebe recomendações automáticas de economia.

Público-Alvo
Pessoas iniciantes no controle financeiro.

Usuários que buscam praticidade e não querem lidar com planilhas complexas.

Funcionalidades-Chave
Registrar gastos via chat em linguagem natural.

Classificação automática das transações.

Definição e acompanhamento de metas financeiras.

Recomendações de economia pelo “Agente Financeiro”.

Relatórios simples e personalizados.

Alternância entre Light Mode e Dark Mode: botão-chave que permite ao usuário mudar facilmente entre os modos de visualização.

Observações Importantes
Relatórios devem mostrar valores em BRL, totais por área e percentuais de uso.

Visual minimalista, com suporte a light mode e dark mode.

Interface user-friendly, acessível até para quem não entende nada de finanças.

Importação de registros externos com análise automática e fallback para categoria “Outros”.

Aplicar Design Universal:

Garantir acessibilidade para diferentes perfis de usuários.

Linguagem clara e inclusiva.

Navegação simples e consistente.

Compatibilidade com recursos de acessibilidade (ex.: leitores de tela).

Aplicar Material Design:

Uso de hierarquia visual clara (tipografia, cores e espaçamento para guiar o usuário).

Feedback visual consistente (animações e transições que mostram ao usuário o que está acontecendo).

Componentes padronizados para garantir uniformidade entre telas.

Acessibilidade integrada (contraste adequado, legibilidade, suporte a leitores de tela).

Minimalismo funcional: evitar excesso de elementos, mantendo foco na simplicidade e clareza.

🚀 MVP – Plano Inicial

Telas Principais

Tela de Conversa

Chat para registrar gastos e interagir com o Agente Financeiro.

Sugestões automáticas de categorias.

Tela de Metas

Definir objetivos (ex.: poupar R$200/mês).

Barra de progresso simples.

Tela de Relatórios

Visualização por área (mercado, lazer, delivery).

Percentuais e valores gastos vs. planejados.

Tela de Importação

Upload de lista de registros.

Classificação automática + confirmação do usuário.

Tela de Configurações

Botão-chave para alternar entre light mode e dark mode.

Ajustes de acessibilidade (tamanho da fonte, contraste).

Recursos Necessários

NLP (Processamento de Linguagem Natural) para interpretar entradas do usuário.

Banco de dados simples para armazenar transações e metas.

Motor de categorização automática com fallback para “Outros”.

UI minimalista com suporte a light/dark mode.

Princípios de Design Universal e Material Design aplicados em toda a interface.

Validação Inicial

Testar com grupo pequeno de usuários iniciantes e diversos perfis (incluindo pessoas com pouca familiaridade tecnológica).

Medir:

Facilidade de registrar gastos.

Clareza dos relatórios.

Utilidade das recomendações do Agente Financeiro.

Inclusividade e acessibilidade da interface.

Satisfação com alternância entre light/dark mode.
```

Interações com o Lovable:

> Crie um app de finanças pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

> Sim, adicione o lovable cloud, também inclua um botão para adicionar arquivos, sejam fotos, planilhas, arquivos de texto para passar várias informações para o chat entender e registrar nos registros.

> Quero que nos relatórios tenha um extrato geral de tudo o que foi registrado, abaixo do campo total gasto este mês que entrou e saiu e que caso clicasse em cada categoria, mostrasse o extrato por categoria. Também quero seja possível também incluir, editar e excluir cada registro que foi adicionado de entrada e saída, para que seja possível gerenciar cada movimentação Quero também que seja possível além de criar, editar e excluir as metas
Ah, um detalhe... todas as vezes que eu faço login, o aplicativo apenas mostra a mensagem de boas vindas, mas não faz login... é necessário atualizar a página pra entrar no aplicativo. Outro detalhe: por padrão, todas as vezes que for criada uma conta, todos os registros devem vir zerados

> Mais 2 problemas:
1 - Ao falar com o chat/bot/IA, nenhum registro está sendo adicionado quando eu peço pra registrar um gasto ou uma entrada, como se não estivesse conseguindo registrar nada 2 - Todo o histórico do chat está sendo apagado ao sair da tela do chat

> Percebi que ao pedir para o chat criar uma meta e já colocar algum saldo, ele só está registrando a saída do saldo, mas não cria a meta
Preciso que o histórico dos registros sejam separados por mês
O chat tem que ter autonomia total pra entender o que eu peço quando falo pra editar, excluir e adicionar registros... ele realmente faça e não só responda no chat.
O chat tem que conseguir ler imagens e inserir registros, caso não entenda os registros, dizer que não entendeu e perguntar ao usuário o que fazer.

> Crie um checkbox de recorrência na tela de inclusão de registro, onde o nome será Entrada recorrente para quando for um registro de entrada e Saída recorrente para quando for um registro de saída.
Não existe um botão Criar ou Salvar para quando eu quero criar um novo registro ou meta e para quando quero editar um registro ou meta, respectivamente. Crie esses botões, por favor

> Então temos um grande problema: os botões não estão aparecendo… muito provavelmente estão ficando abaixo do menu inferior, não sendo possível clicar neles

> O botão de recorrência não está funcionando, faça o seguinte:
Ao criar um registro recorrente, seja de entrada ou saída, faça com que todos os meses pra frente, na mesma data, esse mesmo registro seja criado. Crie também outro campo de data abaixo do checkbox, de nome fim da recorrência, para que o usuário possa selecionar quando a recorrência irá acabar, para não ficar constando infinitamente e poluir o banco de dados

> Ao clicar pra editar e excluir um registro, caso ele seja recorrente… crie uma caixa de diálogo perguntando ao usuário se quer editar ou excluir apenas o registro selecionado ou todos os registros da recorrência

Resultado final no Lovable: https://app-poupai.lovable.app

<img width="1864" height="920" alt="image" src="https://github.com/user-attachments/assets/318026f4-d87e-4c8f-9c28-8740d8b17ca8" />

# 📱 Poupaí – Assistente Financeiro com IA

O **Poupaí** é um aplicativo de organização de finanças pessoais que funciona por meio de conversas em linguagem natural.  
Ele foi projetado para ser simples, acessível e inclusivo, seguindo os princípios de **Design Universal** e **Material Design**.

---

## ✨ Funcionalidades Principais

### 💬 Chat Financeiro
- Registro de gastos via conversa em linguagem natural.  
- Classificação automática das transações.  
- Interação com o **Agente Financeiro IA**, que dá dicas de economia e acompanha seu progresso.

### 🎯 Metas Financeiras
- Criação e acompanhamento de objetivos (ex.: viagem, poupança).  
- Barra de progresso visual e percentual de conclusão.  
- Exibição clara do valor já guardado, meta total e quanto falta.  

### 📊 Relatórios
- Resumo mensal de receitas, despesas e saldo.  
- Quebra por categorias (moradia, lazer, mercado, etc.).  
- Extrato detalhado das movimentações.  
- Interface minimalista com indicadores visuais intuitivos.  

### ⚙️ Configurações
- Alternância entre **Light Mode** e **Dark Mode** via botão-chave.  
- Ajustes de acessibilidade: tamanho da fonte e alto contraste.  
- Informações da conta conectada e versão do app.  

---

## 🎨 Princípios de Design
- **Design Universal**: acessibilidade para diferentes perfis de usuários, linguagem clara, navegação simples e compatibilidade com leitores de tela.  
- **Material Design**: hierarquia visual clara, feedback interativo, componentes padronizados e minimalismo funcional.  

---

## 🚀 MVP Validado
O MVP já inclui:
- Tela de **Chat** para registro de gastos.  
- Tela de **Metas** para acompanhar objetivos financeiros.  
- Tela de **Relatórios** para visualizar receitas, despesas e saldo.  
- Tela de **Configurações** com alternância de tema e opções de acessibilidade.  

---

## 📌 Navegação
- **Chat** | **Metas** | **Relatórios** | **Ajustes**  
Barra inferior simples e intuitiva para acessar todas as funcionalidades.

---

## 🎯 Público-Alvo
- Pessoas iniciantes no controle financeiro.  
- Usuários que buscam praticidade sem planilhas complexas.  
- Quem deseja organizar suas finanças de forma natural e acessível.  

## Reflexão

### O que funcionou bem?  
O refinamento feito no Copilot ajudou muito a criar toda a base do app, também já fez a grande maioria das funcionalidades, também todas os erros e melhorias que eu solicitei foram feitas exatamente como eu queria

### O que não funcionou como o esperado?  
Gostaria de ter mais interações diárias gratuitas no Lovable, pois eu pedia 2 linhas de comando e já iam uns 3.5 créditos e não deu pra fazer tudo em 3 dias, precisei de mais

### O que aprendeu sobre conversar com IAs?
Aprendi que é basicamente igual a conversar com uma pessoa, porém quanto mais detalhes eu ia dando, melhor ele ia me entendendo e fazer as melhorias e modificações conforme eu ia pedindo.
