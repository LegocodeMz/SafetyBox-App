# SafetyBox App
O SafetyBox é um aplicativo de segurança pessoal que usa a tecnologia Twilio para enviar mensagens de texto e voz para contactos pré-definidos em intervalos regulares. Os usuários podem definir o intervalo de tempo que desejam receber as mensagens de segurança e, se não responderem, seus contactos de emergência são notificados para verificar seu estado de segurança e tomar as medidas necessárias. Além disso, o SafetyBox tem outras funcionalidades, como a possibilidade de informar emergências pressionando um botão no aplicativo, que enviará imediatamente a localização e informações de segurança do usuário para seus contactos de emergência. 

O aplicativo também possui um modo de segurança para situações de alto risco, que aumenta a frequência das mensagens de segurança para garantir a segurança do usuário. O SafetyBox pode ser usado por qualquer pessoa que deseje aumentar sua segurança pessoal e informar amigos e familiares sobre sua localização em tempo real.

Este repositório contém o código-fonte para o desenvolvimento do SafetyBox e está disponível para contribuições e sugestões de melhorias. Além disso, este repositório também contém documentação para auxiliar no uso do aplicativo.

# Roadmap Green SafetyBox

## Resumo

#### Autenticação: 
O usuário deve se autenticar no aplicativo para começar a usá-lo e definir seus contactos de emergência.

#### Configurações: 
O usuário deve ter a opção de definir o intervalo de tempo para receber as mensagens de segurança. A opção deve variar de 5 minutos a 12 horas.

#### Envio de Mensagens: 
O aplicativo deve ser capaz de enviar mensagens de texto ou voz aos contactos de emergência pré-definidos. O conteúdo da mensagem deve incluir a localização do usuário e informações de segurança relevantes.

#### Resposta: 
O usuário deve responder às mensagens de segurança no prazo determinado. Caso contrário, seus contactos de emergência serão notificados.

#### Modo de Emergência: 
O usuário deve ser capaz de ativar o modo de segurança em situações de alto risco. Isso aumentará a frequência das mensagens de segurança enviadas para seus contactos de emergência.

#### Botão de Emergência: 
O usuário deve ter a opção de pressionar um botão de emergência para enviar imediatamente a localização e informações de segurança aos seus contactos de emergência.

#### Histórico de Segurança: 
O usuário deve ter a opção de visualizar o histórico de mensagens de segurança enviadas e recebidas.

#### Personalização: 
O usuário deve ter a opção de personalizar a aparência do aplicativo, bem como escolher entre diferentes idiomas.

# Descritivo - Desenvolvimento em Fases

## Fase 1 - Desenvolvimento básico (3 meses)

- Desenvolvimento da estrutura básica do aplicativo e sua interface.
- Integração da tecnologia Twilio para o envio de mensagens de texto e voz.
- Implementação do envio de mensagens de segurança em intervalos definidos pelo usuário.
- Configuração dos contactos de emergência do usuário.

## Fase 2 - Adição de recursos avançados (3 meses)

- Implementação do modo de segurança para situações de alto risco.
- Adição do botão de emergência para envio imediato de informações de segurança e localização.
- Criação do histórico de segurança para visualização e rastreamento de incidentes anteriores.
- Desenvolvimento de uma API para integração com outros aplicativos de segurança.

## Fase 3 - Adição de pacotes de assinatura (3 meses)

- Criação dos pacotes de assinatura Normal, Platinum e Premium.
- Implementação de funcionalidades específicas para cada pacote, como envio de mensagens de voz, alertas personalizados e chamadas de emergência.
- Desenvolvimento do sistema de pagamento e gerenciamento de assinaturas.

## Fase 4 - Melhoria contínua e expansão (contínua)

- Monitoramento contínuo do aplicativo e solução de problemas.
- Adição de novas funcionalidades e recursos com base no feedback dos usuários.
- Expansão para novas regiões e idiomas.

# Possiveis Pacotes & Preços
## Pacotes
    
### Pacote Normal: 
O pacote normal pode incluir todas as funcionalidades mencionadas anteriormente, como envio de mensagens de segurança, modo de segurança, botão de emergência e histórico de segurança.

### Pacote Platinum: 
O pacote platinum pode incluir todas as funcionalidades do pacote normal, bem como funcionalidades adicionais, como o envio de mensagens de voz em vez de apenas mensagens de texto, e uma opção para configurar alertas de segurança personalizados com base em eventos específicos (por exemplo, chegada a um local específico).

### Pacote Premium: 
O pacote premium pode incluir todas as funcionalidades dos pacotes normal e platinum, bem como recursos adicionais, como a possibilidade de realizar chamadas de emergência diretamente pelo aplicativo, acesso a recursos de análise de segurança (por exemplo, gráficos de incidentes de segurança) e suporte prioritário.

## Preçarios

| Pacote   | Funcionalidades                 | Preço (MZN) |
| -------- | -------------------------------| ------------|
| Normal   | Mensagens de segurança regulares| 1000        |
|          | Modo de segurança               |             |
|          | Botão de emergência             |             |
| Platina  | Todas as funcionalidades do     | 3000        |
|          | pacote normal                   |             |
|          | Mensagens de segurança a cada 2 |             |
|          | minutos em modo de segurança    |             |
| Premium  | Todas as funcionalidades do     | 5000        |
|          | pacote platina                  |             |
|          | Suporte prioritário             |             |

