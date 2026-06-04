# cisco-packet-tracer-aaa-email-ftp-lab
Cisco Packet Tracer Lab: configuração de AAA/RADIUS, SMTP, POP3, FTP, DNS e DHCP. Inclui autenticação centralizada, serviços corporativos, troubleshooting, análise de causa raiz e validação operacional dos serviços em ambiente de rede simulado.

# Cisco Packet Tracer Lab – Configuração de Controle de Acesso, E-mail e FTP

## Descrição

Este laboratório foi desenvolvido no Cisco Packet Tracer com o objetivo de implementar e validar serviços essenciais presentes em ambientes corporativos, incluindo autenticação centralizada, correio eletrônico e transferência de arquivos.

Além da configuração dos serviços, o projeto envolveu atividades de troubleshooting, validação funcional e análise de inconsistências entre a documentação do laboratório e o comportamento real dos serviços.

## Objetivos do Laboratório

* Configurar e utilizar credenciais de autenticação AAA
* Configurar e validar serviços de e-mail (SMTP e POP3)
* Configurar e utilizar serviços FTP
* Implementar autenticação centralizada via RADIUS
* Validar resolução DNS e atribuição DHCP
* Executar troubleshooting e análise de falhas

## Tecnologias Utilizadas

* Cisco Packet Tracer
* AAA / RADIUS
* SMTP
* POP3
* FTP
* DHCP
* DNS
* Wireless Authentication
* Network Troubleshooting

## Principais Atividades

### AAA – Authentication, Authorization and Accounting

Configuração do servidor RADIUS para autenticação centralizada de usuários wireless.

### Serviço de E-mail

Configuração de:

* SMTP
* POP3
* Contas corporativas
* Resolução DNS

### Serviço FTP

Criação de usuários com diferentes níveis de permissão:

* Read
* Write
* Delete
* Rename
* List

## Troubleshooting Realizado

Durante a execução do laboratório foram identificadas inconsistências entre a documentação fornecida e a configuração efetivamente necessária para o funcionamento dos serviços.

### Problema 1 – Serviço de E-mail

A documentação indicava o servidor:

email.cyberhq.com

Entretanto, o domínio efetivamente configurado no servidor era:

mail.cyberhq.com

Após a identificação da divergência, os clientes de e-mail foram corrigidos e os serviços SMTP e POP3 passaram a operar normalmente.

### Problema 2 – DHCP Wireless

Mesmo após a obtenção correta dos endereços IP, o sistema de avaliação do laboratório continuava indicando falha.

Após testes de renovação DHCP, reconexão wireless e validação AAA, verificou-se que o Packet Tracer somente atualizou corretamente o Assessment após a reabertura do laboratório.

## Resultados

✅ Autenticação AAA funcional

✅ Resolução DNS operacional

✅ Serviço SMTP funcional

✅ Serviço POP3 funcional

✅ Serviço FTP funcional

✅ DHCP operacional

✅ Comunicação wireless autenticada

✅ Assessment concluído com sucesso

## Aprendizados

Este laboratório reforçou a importância de:

* Validação prática dos serviços
* Análise de causa raiz
* Troubleshooting estruturado
* Interpretação crítica da documentação
* Diagnóstico de falhas em ambientes corporativos

Mais importante do que concluir o laboratório foi desenvolver o raciocínio analítico necessário para identificar problemas, validar hipóteses e implementar soluções de forma estruturada, competências fundamentais para profissionais de Infraestrutura, Redes e Cibersegurança.

---

**Autor:** Márcio Amorim
**Projeto:** Alpha7 SmartTech Labs
**Área de Estudo:** Redes, Infraestrutura e Cibersegurança
