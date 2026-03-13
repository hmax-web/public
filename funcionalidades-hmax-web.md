# Funcionalidades do HMAX Web

## Recepção

- **Mapa de ocupação gráfico**
  - Com Triplo estado
  - Transferência de acomodação clicando e arrastando
  - Filtros
  - Ações rápidas (ver mais abaixo)
- **Mapa de ocupação textual**
  - Útil para daltônicos ou quem prefere ver texto em vez de gráficos coloridos
- **Ações rápidas das acomodações**:
  - Reservar
  - Interditar
  - Cadastrar Limpeza/Governança
  - Efetivar Checkin
  - Abrir Reserva
  - Incluir Consumo
  - Extrato
  - Fechar Conta
- **Lista de hóspedes**
  - Lista pesquisável
  - Versão para impressão com totalizadores
- **Filtro de Acomodações**
  - Por tipo de acomodação, status e exibição das acomodações virtuais
- **Ficha de Entrada**
  - Disponível para impressão durante a entrada, na listagem de reservas e dentro da reserva

---

## Reservas

- **Lista de reservas**
  - **Filtro** de período, código, nome, status, canal, tipo de acomodação e status
  - Acesso a **reserva** clicando no status ou menu Alterar
  - Possibilidade de fazer **check-in ou check-out** através desta lista
  - **Confirmação da reserva**
    - Possibilidade de enviar confirmação de reserva por email ou whatsapp mediante comando do usuário
    - Depende de prévia contratação e configuração
  - **Resumo/Sleep da Reserva**
- **Nova reserva** Confirmada, Pré-Reserva ou Na Casa através da Lista de Reservas, Recepção, Mapa de Reservas ou Atalha personalizado
- **Reserva Passo a Passo**
  - Permite pesquisar a disponibilidade de um período e reservar várias acomodações simultaneamente
- Interdição de Acomodação
- Estado de Limpeza/Governança
  - Possibilidade de colocar acomodação para Limpeza manualmente
  - Criação automática de estado de Limpeza após saída da acomodação
- **Detalhe da reserva**
  - Visualização de Alteração de reserva, ocupação, limpeza ou interdição
  - Pesquisa de Pessoa para definição do nome da reserva
  - **Hospedagens anteriores**
    - Indicador de existência de hospedagens anteriores (visível quando houver alguma)
    - Possibilidade de visualizar lista de hospedagens anteriores
  - **Veículos** da Reserva
    - Planca, Descrição e Cor
  - **Hóspedes** com possibilidade de criança ou consulta da cadastros
  - **Múltiplos tarifários** para seleção
  - **Conta da reserva**
    - Cálculo das Despesas à vista e a prazo, considerando seus Descontos
      - Taxa de Serviço
      - Taxa extra personalizável (Ex.: Taxa de ISS)
  - **Extrato de Conta da reserva**
    - Versões impressas do Extrato À Vista e A Prazo
  - **Consumos da Reserva**
    - Lista de consumos da reserva com indicador de cobrança à vista ou a prazo e possibildiade de mudar o valor do indicador
    - **Lançamento de Consumos na reserva**
      - Possibilidade de lançar produtos ou serviços na reserva diferenciando preços por ponto de venda
    - Estorno de consumo
    - Transferência de consumo
  - **Pagamentos da Reserva**
    - Lista de pagamentos da reserva
    - Inclusão de pagamento nas formas Dinheiro, Cheque, Cartão, Depósito Bancário, PIX (apenas no Brasil)
        - **Formas de pagamento** suportadas: **PIX**, **Cartão de Crédito/Débito**, **Dinheiro**, **Depósito bancário**, **Cheque** e **Cobrança A Prazo** (esta última tem caminho específico)
    - Cancelamento de pagamento
    - **Cobrança A Prazo (faturamento para pessoa autorizada)**
      - Possibilidade de definir uma pessoa para cobrança a prazo para valores de Hospedagem, Extras ou alcoólicos.
          - Se houver Financeiro irá gerar um título a Receber, senão, deve gerar um pagamento na lista de pagamentos, com status "não pago"
      - Depende ter Financeiro ativo e haver prazo definido no cadastro da pessoa
    - **Comprovante de pagamento**: Versão para impressão do comprovante de pagamento
    - Enviar **link de pagamento** (PIX/cartão): Depende de integração configurada
  - **Log de atividades da Reserva**
- **Ações Dento do Detalhe da Reserva**
  - Check-in
  - Check-out
  - Transferência de acomodação
  - Cancelamento de reserva
  - **Fechamento de conta**
    - Apresenta o resumo da conta separando À Vista de A Prazo
    - Listagem de pagamentos com inclusão e cancelamento durante o fechamento de conta
    - Saldo de conta com moedas estrangeiras
      - Depende de configuração e cotação para as moedas
  - Cadastro de **Limpeza**/Governança
  - **Interdição de acomodação**
- **Lançamento automático de diárias**
- **Mapa de reservas**
  - Permite reservar, interditar, transferir de acomodação ou perído, estender ou encurdar estadia, podendo arrastar a reserva para um período fora dos limites exibidos devido ao auto-scroll, desde que dentro do período selecionado.
- **Mapa de reservas por Tipo de acomodação**
  - Envio de disponbilidade para Reservas Online. Depende de ter integração

---

## Movimento de Caixa

- **Caixa da Recepção/Estabelecimento**
  - Entrada e Saída manual do caixa da recepção
  - Também entram nesse caixa, os pagamentos feitos em Dinheiro ou Cheque
- **Lista de movimentos anteriores**
- **Lista de contas fechadas**
    - Acesso ao extrato À Vista ou A Prazo da conta fechada
- **Relatório do Movimento de Caixa**
  - Visualizão e versão para impressão
  - Contém as contas fechadas e respetivos pagamentos
- **Encerramento de Caixa**
  - Prevê transferência de valores para o caixa seguinte para eventual fundo de caixa.

---

## Gerência

- **Dashboard de Gerência**
  - Contém métricas comuns de hospedagem
- **BOH**
    - Filtro de período
    - Versão para impressão
- **Produção de Venda**
    - Filtro de período
- **Listagem de Pagamentos**
  - Lista de pagamentos com totalizações por forma de pagamento e bandeira de cartão
  - Alterar status de pago
  - Acesso a reserva vinculada ao pagamento
  - Cancelamento de pagamento
  - Filtro: Status, perído, vencimento, código da reserva e forma de pagamento
- **Listagem de consumos**:
  - Filtros: Período, Ponto de Venda, Usuário e Tipo (Produto/Serviço)
  - Totalização por ponto de venda
- **Estornos**
  - Listagem de estornos
  - Vizualização do motivo do estorno
  - Permite arquivar estornos já esclarecidos
- **Relatórios de Produtos/serviços mais vendidos**
  - Filtros de período, ponto de venda, tipo (produto/serviço) e pela descrição

---

## Financeiro

- **Dashboard Financeiro**
  - Resumos de contas, contas a receber e pagar, reservas na casa, etc
- **Contas/Transações**
  - Listagem de Transações de Contas Financeiras (Caixa, banco, etc), incluindo a conta Caixa da Recepção
  - Inclusão de Transação em aberto ou efetivada, com descontos e acréscimos
  - Filtro por período, tipo de período (Data de competência, vencimento, pagamento, criação), tipo (receita, despesa, transferência), status, categoria, documento, valor e pessoad
  - **Lançamento manual de transação** (receber e pagar)
    - Repetiçãod e transação
- **Contas a Receber e Pagar**
  - Listagem de contas a pagar e a receber
  - Filtros: Mesmos filtros de Contas/Transações
- **Relatório de Receitas e despesas**
  - Agrupado mês a mês por categoria
- **Relatório de receitas e despesas detalhado**
  - Mostra as transações financeiras de receita e despesa em suas categorias
- **DRE**: Demonstrativo de Resultados do Exercício
  - Agrupada mês a mês por categoria
  - Mapeamento de categorias de DRE com categorias Financeiras
- **Categorias Financeiras**
  - Listagem e Cadastros de categorias de Receitas e Despesas (não inclui Ativo e Passivo)
- **Contas Financeiras**
  - Listagem e cadastro de contas financeiras (contas bancárias, cartões, caixa)

---

## 8. Outros Cadastros

- **Pessoas**
  - Lista com Filtro
    - Ficha de Hospedagem preenchida
    - Ficha de Hospedagem em branco
    - Histórico de hospedagens da pessoa
  - Cadastro de Pesoas
    - Permitindo múltiplos documentos, emails e telefones
    - Consulta de CEP para pessoas do Brasil
    - Categorização de Pessoas
    - Definição de dias para cobrança a prazo e items a serem cobrados a prazo
    - Definição de desconto padrão para a pessoa
- **Usuários**
  - Lista e Cadastro
  - Controle de acesso definido por papéis
- **Produtos e Serviços**: 
  - Lista e Cadastro
- **Pontos de venda**
  - Lista e Cadastro
- **Múltiplos Tarifários**
  - Lista e Cadastro
  - Lista de Tarifas
  - Ferramenta de atualização de tarifas
- **Tipos de acomodação**
  - Lista e Cadastro com imagens e descrição da acomodação
- **Acomodações**
  - Lista e Cadastro
  - Inclusão de faixa numérica de acomodações
- **Moedas**
  - Definição de cotação de moeda (o cadastro é feito globalmente apenas por super usuário)
  - Opção para carregamento automátco da cotação do ínicio do dia
- **Cartões/Taxas**
  - Definição de taxas de cartão de crédito/débito

---

## Outros

- **Log Atividades**
  - Com filtro de perído, usuário e descrição, o que permite filtrar praticamente tudo no log
- **Notificação de Novidades** da aplicação
- **Atalhos Personalizados**
  - Acessíveis por ícone sempre visível no topo.
  - Com este recurso é possível, por exemplo, fazer uma reserva a partir de qualquer tela do sistema
- **Modo claro ou Escuro**
- Login, logout, bloqueio de usuário simultâneo, recuperar/redefinir senha, confirmação de conta, cadastro.
- **Multi-Idioma**
- **Perfil do usuário**
  - Redefinição de senha por parte do próprio usuário
  - Idioma por usuário
- **Assinatura**
  - Visualização do plano e recursos contratados
  - Alteração de assinatura
  - Cancelamento de assinatura (Apenas proprietário e administrador de assinaturas)
  - Visualização de Pagamentos da assinatura
  - Visualização dos Termos de Uso atuais
- **Troca de Empresa** caso o usuário esteja vinculado a mais de uma ou seja um super usuário
- **Chat HMAX**
  - Para falar com o suporte técnico ou comercial
- **Login/Logout/Redefinição e Recuperação de senha**
- **Wizard** 
  - Para inicialização de dados de nova empresa
  - Inicializa tipos de acomodações e acomodações
- **Inicialização com Dados Fictícios**
  - Permite um novo lead inicializar sua base de dados com dados fictícios, assim ele pode vero mapa de reservas populado e as reservas com lançamentos e outros detalhes, sem ter que ele mesmo criá-las.
  - Também gera dados financeiros
- **Termos de uso**
  - Link público para ser acessado por qualquer pessoa
  - Acessível também para o assinante dentro do sistema
  - Envio de novo termo para o email de clientes
- **Fluxo de Demonstração**
  - Para os leads testarem a aplicação
- **Fluxo de assinatura**
  - Para os Leads assinarem nosso produto ou atualizarem sua assinatura contrantando ou cancelando recursos.
- **Envio de emails**
  - Boas-Vindas
  - Primeira senha definida com sucesso
  - Redefinição de Senha
  - Assinatura realizada com sucesso
  - Mudanças no termo de uso
  - Confirmação/Cancelamento de reserva
  - Senha de Fechadura eletrônica
  - Link de pagamento
  - Código de autenticação em duas etapas (para o Concierge)

---

## Configurações

- **Configurações da empresa**
  - **Conta** 
    – Dados da empresa
    - Logomarca para relatórios
    - Horários padrão de entrada e saída
    - Horário lançamento automático
    - Definição de políticas
    - Idioma do estabelecimento
    - País do estabelecimento
    - Moeda padrão
    - Outras Moedas aceitas
    - Fuso-horário
    - Taxa de serviço: Definição de percentual
    - Taxa extra: nome e percentual de taxa extra. Ex: 'Taxa de ISS'
  - **Reservas**
    - Textos de Confirmação de reserva, Pré-reseva e Cancelamento de reserva nos 3 idiomas principais
    - Definição de Ponto de venda e produto/serviço de hospedagem
    - Tarifário padrão
    - Regime de alimentação padrão
  - **Financeiro**
    – Conta bancária padrão
    - Conta bancária de PIX
    - Cartão de crédito padrão para reservas online
    - Categoria Financeiras para Desconto
    - Categoria Financeira para Acréscimos
  - **Integrações**
    - Definição de email remetente para envios de email
    - Pré ativação de integrações de Web Check-in, Fechadura eletrônica, Confirmação/cancelamento de reseva por e-mail e/ou WhatsApp, e  Link de Pagamento

---

## Recursos para Super Usuários

- **Demonstrações**
  - Listagem de Leads com uma cópia demonstração do Hmax Web
  - Utilizada pelo comercial para acompanhamento dos leads que estão testando a aplicação
- **Empresas**
  - Lista pesquisável e Cadastro manual de empresas
  - Ativação manual de recursos da empresa. (Ex.: Financeiro)
- **Assinaturas**
  - Lista e cadastro
  - Lista de pagamentos da assinatura
  - Sincronia de pagamentos de assinatura
- **Termos de uso**
  - Cadastro de Termos de Uso
  - Envio de email informando clientes sobre atualizações nos termos
- **Cadastros**
  - Organizações/Redes
  - Pessoas (para vínculo com empresas)
  - Super usuários
  - Planos de Assinatura
  - Novidades da aplicação
  - Recursos da aplicação
  - Canais de venda
  - Integradores (Ex. Omnibees, Omnitec, PmWeb, Motor Hmax, etc)
  - **Ativação de Integrações**
    - Reservas Online, Hub, Web Check-in, Pagamento, etc
- **Cadastros Globais**
  - Cadastros comuns utilizados por todos os estabelecimentos
    - Cartões de Crédito/Débito
    - Cidades
    - Estados
    - Países
    - Bancos (Instituições Financeiras)
    - Moedas

---

## Integrações

- **Asaas** 
  - Criação/Alteração/Cancelamento de assinaturas
  - Listagem de assinatura
  - Listagem de pagamentos de assinatura
- **Reservas Online**
  - Sincronia de reservas com o serviços de reservas online
  - Consequentemente também recebe Reservas do HMAX AI
- **Web Check-in**
  - Email/Whatsapp de Web check-in
  - Recebimento de dados da pessoa preenchidos no web-checkin
- **Link de Pagamento**
- **Concierge**
  - Sincronia de Reservas
  - Extrato de Reservas na Casa
  - Inclusão de Limpeza
  - Check-in
  - Consulta de senha da fechadura
- **Fechadura Eletrônica** Omnitec
- **Tarifário do Motor** de Reservas
  - Recebe valores de tarifário do motor de reservas
- **RD Station**
  - Envio de vários gatilhos solicitados pelo comercial
    - Primeira definição de senha de uma demonstração
    - Primeira acesso de uma demonstração
    - Dados demonstração inicializados (wizard ou dados fictícios)
    - Atualização de recursos contratados
    - Demonstrações ociosas
- **Discord**
  - Recebemos notificações de erro e outros monitoramentos direto no Discord, assim podemos nos antecipar e corrigir problemas, como já fizemos pra resolver um problema de overbooking por exemplo.

---

## Páginas Públicas Seguras

- **Confirmação de reserva segura**
  - Hóspede pode receber um link seguro para visualizar a confirmação de sua reserva direto no Hmax Web, sem prencisar de um login.
  - Isto garante que só o hóspede com o respectivo contato do Whatsapp consiga visualizar e apenas por um tempo limitado após sua saída
- **Extrato da reserva seguro**
  - Link de extrato da reserva com os mesmos tratamentos do item anterior

---