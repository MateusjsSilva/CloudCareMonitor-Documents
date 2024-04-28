1.  **Título do Projeto**: Integração da Internet das Coisas e Computação em Nuvem na Melhoria da Assistência de Saúde: Coleta Eficiente de Dados de Pacientes e Análise em Tempo Real.
    
5.  **Resumo do Projeto**:
    
    *   Investigação da integração da Internet das Coisas (IoT) com plataformas de computação em nuvem para desenvolvimento de um sistema de monitoramento inteligente da saúde em tempo real.
    *   Coleta eficaz de dados de pacientes por dispositivos IoT e transmissão eficiente para sistemas em nuvem.
    *   Aplicação de algoritmos de inteligência artificial para análise dos dados, identificando rapidamente situações críticas e emitindo notificações imediatas.
    *   Desenvolvimento de um protótipo do sistema para demonstrar viabilidade e eficácia.
6.  **Arquitetura da API**:
    
    *   Dividida em 5 camadas: Domínio, Apresentação, Persistência, Infraestrutura e Aplicação.
    *   Utilização de CQRS (Command Query Responsibility Segregation) para separar as operações de leitura e escrita.
    *   Integração do Identity Framework na camada de Persistência para gerenciamento de autenticação e autorização.
7.  **Desenvolvimento da Aplicação MVC**:
    
    *   Implementação de funcionalidades de autenticação, como login, registro de usuários e recuperação de senha.
    *   Utilização de HTML, CSS e JavaScript para construção da interface de usuário.
8.  **Programação do ESP32**:
    
    *   Desenvolvimento de firmware para o ESP32 para coleta de dados de sensores de saúde.
    *   Integração com o broker para envio de mensagens para a infraestrutura da aplicação.
9.  **Broker**:
    
    *   Utilização de um broker para comunicação assíncrona entre os diferentes componentes da aplicação.
    *   Facilita a troca de mensagens entre os serviços e componentes de forma distribuída e resiliente.
