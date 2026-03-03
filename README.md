# 💸 App de Finanças Pessoais com Vibe Coding (Poupaí)

---

## 📝 PRD Refinado no Copilot Web

## 📸 Interações com o Lovable

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

**Resultado final no Lovable:**  
[https://app-poupai.lovable.app](https://app-poupai.lovable.app)

<img width="1864" height="920" alt="image" src="https://github.com/user-attachments/assets/318026f4-d87e-4c8f-9c28-8740d8b17ca8" />

---

## 📱 Resumo do App – Poupaí

O **Poupaí** é um aplicativo de organização de finanças pessoais que funciona por meio de conversas em linguagem natural.  
Ele foi projetado para ser simples, acessível e inclusivo, seguindo os princípios de **Design Universal** e **Material Design**.

### ✨ Funcionalidades Principais
- **Chat Financeiro**: registro de gastos via conversa, classificação automática e dicas do Agente Financeiro IA.  
- **Metas Financeiras**: criação e acompanhamento de objetivos com barra de progresso.  
- **Relatórios**: resumo mensal de receitas, despesas e saldo, com extrato detalhado por categoria.  
- **Configurações**: alternância entre light/dark mode e opções de acessibilidade.  

### 🎨 Princípios de Design
- **Design Universal**: acessibilidade para diferentes perfis de usuários, linguagem clara e compatibilidade com leitores de tela.  
- **Material Design**: hierarquia visual clara, feedback interativo, componentes padronizados e minimalismo funcional.  

### 🚀 MVP Validado
Inclui telas de **Chat**, **Metas**, **Relatórios** e **Configurações**, todas acessíveis pela barra inferior de navegação.  

---

## 🤔 Reflexão

### O que funcionou bem?  
O refinamento feito no Copilot ajudou muito a criar toda a base do app. A maioria das funcionalidades foi implementada e os erros/melhorias solicitados foram atendidos exatamente como esperado.  

### O que não funcionou como o esperado?  
Gostaria de ter mais interações diárias gratuitas no Lovable. Os créditos acabaram rápido e não deu para concluir tudo em 3 dias.  

### O que aprendeu sobre conversar com IAs?  
Aprendi que é basicamente igual a conversar com uma pessoa: quanto mais detalhes eu dava, melhor a IA entendia e aplicava as melhorias conforme solicitado.  
