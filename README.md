# Projeto-SuaVez

SuaVez! – Sistema Inteligente de Gestão de Filas
para Clínicas e Hospitais
Resumo
O SuaVez! é uma plataforma web desenvolvida para modernizar e otimizar o gerenciamento de
filas em clínicas, hospitais e centros de atendimento médico.
 O sistema organiza atendimentos em
tempo real e integra recursos de Inteligência Artificial para auxiliar profissionais e melhorar a
experiência dos pacientes.

Objetivos do Projeto
• Reduzir o tempo de espera dos pacientes.
• Automatizar o controle de filas.
• Disponibilizar informações em tempo real.
• Integrar Inteligência Artificial ao fluxo operacional.
• Garantir segurança e rastreabilidade das ações.

Arquitetura da Solução
O sistema segue o modelo cliente-servidor, sendo composto por Front-end, Backend desenvolvido
em NestJS e Banco de Dados Firebase Firestore, permitindo sincronização em tempo real.

Tecnologias Utilizadas
• NestJS para APIs REST, regras de negócio e WebSockets.
• Firebase para autenticação, banco de dados e hospedagem.
• Groq com modelos LLaMA e Mixtral para Inteligência Artificial.

Estrutura dos Módulos
AuthModule, PatientsModule, ProfessionalsModule, QueueModule e AIAdvisorModule.

Segurança
• Firebase Auth.
• JWT validado pelo backend.
• Controle de permissões.
• Auditoria de ações.

Implantação
Compatível com Cloud Run, Railway ou Vercel Serverless, utilizando Firestore e Firebase Hosting.

Testes e Qualidade
Foram realizados testes unitários, validação de endpoints, testes de integração e validação da IA.

Resultados Obtidos
Sistema web funcional, painel de recepção, painel público, integração com IA, documentação
técnica e scripts de instalação.

Conclusão
O SuaVez! demonstra como tecnologias modernas e Inteligência Artificial podem ser utilizadas
para otimizar processos de atendimento em ambientes de saúde, proporcionando mais eficiência,
organização e qualidade.
