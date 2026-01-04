# 💸 Finança Fácil – Organização de Finanças Pessoais
by Paulo Cesar

## 📌 Resumo do Projeto
Aplicativo de finanças pessoais com interface conversacional, criado a partir de um PRD refinado com Copilot e prototipado no Lovable. O objetivo é simplificar o controle financeiro por meio de linguagem natural, sem exigir conhecimento técnico.

## 🎯 Objetivos de Aprendizagem
- Praticar elaboração de PRD.
- Explorar prototipagem com IA (Lovable).
- Refletir sobre limitações e potencial de ferramentas de IA em projetos reais.

## 🛠 Stack Tecnológico
- **Frontend:** Angular (LTS), PrimeNG, PrimeFlex, PrimeIcons.
- **Backend:** NestJS (LTS).
- **Ferramentas:** Copilot, Lovable.

## 📑 PRD
```
# PRD – App de Organização de Finanças Pessoais

## 1. Contexto
Criar um aplicativo de organização de finanças pessoais que funcione por meio de conversas em linguagem natural e acessível.  
O objetivo é simplificar o controle financeiro sem exigir formulários complexos ou conhecimento técnico, tornando a experiência mais próxima de um bate-papo.

## 2. Problema
Muitos usuários desistem de controlar seus gastos porque:
- Os apps atuais exigem muita entrada manual.  
- Há pouca personalização e recomendações práticas.  

Solução proposta: oferecer uma experiência conversacional com dicas automáticas de economia e sugestões para mitigar ou quitar dívidas e créditos em atraso.

## 3. Público-Alvo
- Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação.  
- Principalmente iniciantes que não têm familiaridade com termos técnicos ou planilhas.

## 4. Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Receber recomendações para reduzir juros e organizar dívidas.  
6. Visualizar relatórios simples e personalizados.  
7. Histórico financeiro: acompanhar gastos e receitas passadas em linha do tempo.  
8. Previsão de gastos: estimar despesas futuras com base em padrões anteriores.  
9. Projeção financeira futura: simular cenários (ex.: quanto posso economizar em 6 meses se reduzir gastos em lazer).

## 5. Critérios de Sucesso (KPIs iniciais)
- Número médio de gastos registrados por semana.  
- Percentual de usuários que conseguem definir metas sem ajuda.  
- Nível de satisfação com as dicas recebidas (feedback simples).  
- Engajamento com histórico e relatórios (quantas vezes acessam).  
- Acurácia percebida das previsões/projeções financeiras.  

## 6. Fluxo do Usuário (User Journey)
1. Usuário entra no app e recebe uma explicação simples.  
2. Registra um gasto via conversa.  
3. O app sugere categorização automática.  
4. Usuário acompanha relatórios básicos e histórico.  
5. Recebe dicas personalizadas para economia ou redução de juros.  
6. Visualiza previsões e projeções financeiras futuras.  

## 7. Requisitos Não-Funcionais
- Interface simples e intuitiva.  
- Linguagem acessível e popular.  
- Garantia de privacidade dos dados financeiros.  
- Design responsivo: deve funcionar bem em diferentes aparelhos (smartphones, tablets, desktops).  
- Usabilidade universal: acessível para diferentes perfis de usuários, com foco em clareza e simplicidade.  
- Tecnologias obrigatórias:  
  - Frontend: Angular (LTS) com bibliotecas PrimeNG, PrimeIcons e PrimeFlex.  
  - Backend: NestJS (LTS).  
- Performance: respostas rápidas no chat e carregamento leve dos relatórios.  

## 8. Exemplos de Interações
- Usuário: “Paguei 120 reais no cartão de crédito ontem.”  
- App: “Ok, registrei como pagamento de dívida. Quer que eu acompanhe os juros desse cartão?”  
- Usuário: “Quanto devo gastar em supermercado no próximo mês?”  
- App: “Com base nos últimos 3 meses, sua média é R$450. Posso sugerir meta de R$400 para economizar.”  

## 9. Entregável da IA
Gerar um plano de MVP com:
- Principais telas.  
- Recursos necessários.  
- Esboço de validação inicial.  

Tom educativo e linguagem acessível em português.
```

## 🔄 Interações com Lovable
```
1. Crie um app de finanças através do seguinte PRD (Product Requirements Document): {Informei o PRD}
2. Notei que ao conversar com o agente e tentar registrar um gasto ele nao identificou e aparentemente esta apresentando respostas pré-definidas, não registrou meu gasto no histórico nem ajustou os dashboards, Também gostaria de uma tela de cadastro e login, os botões também não estão todos funcionando, não consegui criar uma nova meta por exemplo.
3. (Créditos acabaram)
```

## ✅ Resultado Final
https://conversa-rica-ai.lovable.app

## 🤔 Reflexão
### O que funcionou bem
- Refinamento do PRD com Copilot.
- Protótipo rápido com Lovable.

### O que não funcionou
- IA do agente não registrou gastos corretamente.
- Botões e metas com falhas de funcionamento.

### O que aprendi
- Importância de validar requisitos antes da prototipagem.
- Limitações atuais de IA em fluxos complexos.
- Valor da prototipagem rápida para demonstrar ideias.

## 📈 Roadmap
- Corrigir IA do agente financeiro.
- Adicionar tela de login/cadastro.
- Refinar dashboards e metas.
