# Tríade CIA

## Objetivo

A tríade CIA é uma das bases da Segurança da Informação e está dividida em três pilares: confidencialidade, integridade e disponibilidade.

A confidencialidade busca impedir o acesso não autorizado aos dados. A integridade procura evitar alterações indevidas, preservando a exatidão das informações. A disponibilidade busca manter sistemas e dados acessíveis aos usuários autorizados quando necessário.

Um ataque DDoS, por exemplo, ameaça a disponibilidade ao sobrecarregar um serviço, podendo causar interrupções e prejuízos para uma organização.

## Confidencialidade

### Definição

A confidencialidade protege as informações contra acessos e divulgações não autorizadas. Cada usuário deve acessar somente os dados necessários para executar suas atividades, seguindo o princípio do menor privilégio.

### Exemplo

Em um aplicativo, credenciais e informações pessoais dos usuários devem ser protegidas. Somente pessoas e sistemas autorizados podem acessar os dados necessários, conforme suas funções.

### Ameaça

Uma ameaça ocorre quando um usuário recebe permissões maiores do que deveria. Caso essa conta seja comprometida por phishing ou por um infostealer, o invasor poderá utilizar os privilégios excessivos para acessar informações sensíveis, aumentando o impacto de um possível vazamento de dados.

### Medida de proteção

A organização deve auditar os níveis de acesso, verificar se as permissões estão de acordo com as funções dos usuários e aplicar o princípio do menor privilégio.

Também pode utilizar autenticação multifator, armazenamento seguro de senhas e treinamentos de conscientização contra phishing e outros ataques de engenharia social.

## Integridade

### Definição

Integridade é a garantia de que os dados permaneçam corretos, completos e consistentes. As informações podem ser atualizadas, mas somente de maneira autorizada e controlada, sem alterações acidentais ou maliciosas.

### Exemplo

Um prontuário médico deve armazenar corretamente as informações de saúde do paciente. Caso um registro importante, como a informação de que o paciente possui diabetes, seja removido ou modificado indevidamente, uma equipe médica poderá tomar decisões utilizando informações incorretas, causando riscos ao paciente.

### Ameaça

A integridade pode ser ameaçada por ações externas ou internas. Um invasor pode modificar informações após comprometer o sistema, mas também pode ocorrer um erro de preenchimento, uma falha da aplicação ou a concessão incorreta de permissão para um usuário.

### Medida de proteção

O sistema deve utilizar controles de acesso para permitir alterações somente por usuários autorizados. Também deve validar os dados inseridos e manter logs de auditoria que registrem quem realizou cada modificação e quando ela ocorreu.

Hashes e assinaturas digitais podem ajudar a verificar alterações e autenticidade em situações adequadas. Backups também devem ser mantidos para permitir a recuperação de informações após erros ou incidentes.

## Disponibilidade

### Definição

Disponibilidade é a garantia de que sistemas e dados estejam acessíveis aos usuários autorizados quando forem necessários. Como não é possível impedir todas as interrupções, a organização deve reduzir o tempo de indisponibilidade e estar preparada para recuperar os serviços.

### Exemplo

Se um sistema de pagamentos ficar indisponível durante duas horas, a empresa responsável poderá sofrer perdas financeiras, reclamações e danos à sua reputação. Clientes, lojas e parceiros que dependem do serviço também poderão ser prejudicados.

### Ameaça

A disponibilidade pode ser afetada por ataques DDoS, aumento inesperado de usuários, falhas de hardware, erros de configuração, interrupções de energia ou problemas de rede.

A falta de capacidade ou a existência de apenas um servidor também pode criar um ponto único de falha.

### Medida de proteção

A organização deve monitorar continuamente o serviço para identificar falhas, sobrecargas e comportamentos anormais. A infraestrutura precisa ter capacidade adequada, proteção contra DDoS e redundância para evitar que a falha de um único servidor interrompa todo o sistema.

Servidores secundários podem ser configurados com mecanismos de failover para assumir o serviço quando necessário. Também devem existir fontes alternativas de energia, manutenção preventiva, atualizações, backups testados e um plano de recuperação de desastres.

## Relação entre os três pilares

## Aprendizados