# Sistema KanBam
 Sistema de Organização de Tarefas
  Este é um software de gestão de tarefas desenvolvido em Python, com foco em equipes e ambientes colaborativos.
  
 O sistema permite que os usuários gerenciem suas tarefas de forma simples e eficiente, movendo-as entre diferentes status (pendente, em andamento, concluído), registrando a quantidade de itens concluídos, e gerenciando históricos diários e mensais.
 
 FUNCIONALIDADES PRINCIPAIS
 
  Gestão de Tarefas: Os usuários podem adicionar tarefas, mover tarefas entre status (pendente, em andamento, concluído), e registrar a quantidade de itens concluídos.
  Tarefas Repetidas: O administrador pode configurar tarefas para se repetirem em intervalos específicos (diários, semanais, mensais).
  Tarefas Predefinidas: O administrador pode cadastrar tarefas predefinidas que podem ser facilmente adicionadas pelos usuários com um único clique (evitando a necessidade de digitar cada tarefa).
  Histórico: O sistema mantém um histórico diário e mensal das tarefas concluídas.
  Administração: O administrador pode cadastrar novas tarefas, adicionar usuários a salas e gerenciar o sistema de tarefas.
  Salas de Trabalho: Usuários podem ser adicionados a salas específicas, onde podem acessar e gerenciar tarefas compartilhadas.
  
 FUNCIONALIDADES DO ADMIN
 
  Cadastro de Tarefas Predefinidas: O admin pode criar tarefas predefinidas para facilitar a adição de tarefas comuns entre os usuários.
  Cadastro de Tarefas Repetidas: O admin pode definir tarefas que se repetem automaticamente após um período (diário, semanal ou mensal).
  Gerenciamento de Usuários e Salas: O admin pode adicionar ou remover usuários das salas de trabalho e gerenciar o fluxo de tarefas.
  
 TECNOLOGIAS UTILIZADAS 
 
  Back-end: Python, FastAPI ou Django 
  Front-end: Kivy (para versões desktop e mobile)
  Banco de Dados: SQLite (para protótipo) ou PostgreSQL/MySQL (para produção)
  Sincronização em Tempo Real: WebSockets (para atualizações instantâneas de status)
  
 Outras Ferramentas:
 
  Git, Docker (opcional), Figma (para design da interface)
