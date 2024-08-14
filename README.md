# IAC AMBIENTE LINUX

O projeto infraestrutura como código (IaC) em Ansible oferece uma solução automatizada para configurar ambientes de forma rápida e eficiente.
Através de playbooks e papéis cuidadosamente definidos, ele automatiza tarefas como atualização do sistema operacional,
instalação de pacotes essenciais como htop, net-tools, zabbix-agent, docker e docker-compose, além de configuração de
serviços básicos como zabbix-agent e docker. Essa abordagem proporciona uma estrutura modular e organizada, permitindo
uma fácil adaptação às necessidades específicas do ambiente e simplificando o processo de provisionamento e manutenção.

## Adição de Suporte para Oracle Linux

Mudança Importante: Devido à descontinuação do CentOS, o suporte para Oracle Linux foi adicionado ao projeto. A configuração agora inclui a instalação específica para Oracle Linux, refletida no arquivo oracle.yml. O suporte para CentOS ainda está disponível, mas o foco é garantir que o projeto seja compatível com Oracle Linux, que é uma alternativa robusta e amplamente utilizada.



## Funcionalidades Extras

- playbooks separados para inserir e excluir usuarios, do sistema.
- Implementa uma pagina Web, instalando o Nginx e copiando o html com origem na pasta Files
