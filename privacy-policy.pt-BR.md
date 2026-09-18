# 

**Implicações:**

---

## 1. Introdução

Detour Post (doravante denominado "o Aplicativo") é operado por Yong Wang (doravante denominado "nós", "nos" ou "nosso"). Atuamos como controlador de dados de suas informações pessoais.

Esta Política de Privacidade explica quais informações coletamos, por que as processamos, como são tratadas e armazenadas, períodos de retenção e como você pode exercer seus direitos de privacidade.

Nosso princípio fundamental é direto: **Suas cartas são privadas entre você e seu destinatário. Não podemos lê-los e não temos intenção de lê-los.**

## 2. Informações que processamos

### 2.1 Informações que você fornece ativamente

| Informação | Detalhes | Necessidade |

|---|---|---|

| Identificador de conta | Identificador único obtido por meio de Login com Apple ou Google | Necessário para criação de conta |

| Credenciais de login | Tokens de autenticação de sessão | Necessário para acesso seguro |

| Data de nascimento e região | Utilizado no registo apenas para determinar a idade de elegibilidade | Obrigatório para registro. **A data de nascimento é utilizada apenas no momento da avaliação e imediatamente descartada; nunca a armazenamos.** Apenas a versão da regra e a região selecionada são retidas |

| Nome de exibição | Nome personalizado definido em seu perfil, visível para seus destinatários | Opcional |

| Cidade | Cidade selecionada como ponto de partida/chegada | Opcional, mas obrigatório para envio de cartas |

| Informações de conexão | Status de relacionamento, códigos de convite e códigos secretos de resgate de cartas | Necessário para troca de cartas |

| Conteúdo da carta | Texto da carta, escolha de papel de carta e decorações, fotos anexadas, correio, hora de chegada | Criado somente quando você escolhe enviar |

| Detalhes do relatório | Categoria de violação selecionada (Assédio, Spam, Segurança) e ID do alvo. **NÃO contém texto de carta, fotos, texto de formato livre ou coordenadas**; bloqueia automaticamente a festa simultaneamente | Criado somente quando você registra um relatório |

| Notas privadas | Notas privadas que você atribui a um contato | Opcional. **Armazenado estritamente no seu dispositivo local, nunca carregado** |

**Criptografia ponta a ponta de cartas e fotos.** O texto das cartas e as fotos são criptografados diretamente no seu dispositivo local antes da transmissão. Mantemos apenas texto cifrado e não possuímos chaves de descriptografia. Conseqüentemente, **não podemos ler, inspecionar ou fornecer o texto ou as fotos da sua carta a ninguém** — incluindo consultas policiais, onde apenas o texto cifrado pode ser fornecido. Consulte a Seção 4.

### 2.2 Informações geradas automaticamente durante o uso

| Informação | Detalhes | Finalidade |

|---|---|---|

| Status de entrega | Partida, marcos da viagem, chegada, recall, status de término | Alimentando o pipeline de entrega postal |

| Estado da conta e segurança | Situação da conta, listas de bloqueios recíprocos, situação de tratamento de relatórios | Administração de contas e prevenção de abusos |

| Livro de comércio | Registros de pedidos, saldos de moedas, propriedade permanente de itens, assinaturas ativas | Faturamento, atendimento e tratamento de reembolso |

| Tokens push e de dispositivo | Tokens push do dispositivo e metadados necessários | Envio de notificações de status de cartas |

| Registros de serviço | Logs operacionais de API, rastreamentos de erros e diagnósticos de desempenho | Segurança, estabilidade e solução de problemas |

**Sem segredos em registros ou notificações push.** Os registros operacionais nunca contêm texto de carta, fotos, códigos de convite ou coordenadas exatas. As notificações push carregam apenas frases de status genéricas (por exemplo, "Chegou uma carta") sem identificadores pessoais, texto de mensagem ou cidades.

### 2.3 O que NUNCA fazemos

- NÃO acessamos sua biblioteca completa de fotos, contatos ou localização GPS precisa;

- NÃO coletamos identificadores de rastreamento (IDFA/IDFV), incorporamos SDKs de anúncios nem realizamos rastreamento entre aplicativos;

- NÃO alimentamos dados de cartas em modelos de treinamento de IA – não temos acesso a texto simples;

- NUNCA vendemos suas informações pessoais a terceiros.

## 3. Por que processamos informações

| Finalidade | Informações Envolvidas | Base Jurídica |

|---|---|---|

| Entrega e recepção postal | ID da conta, nome de exibição, cidade, informações de conexão, carta criptografada, status de entrega | Execução do contrato de serviço |

| Compras e reembolsos no aplicativo | Livro de compras, validade da assinatura | Execução do contrato de serviço |

| Notificações push de entrega | Token push, estado de entrega | O seu consentimento (revogável a qualquer momento) |

| Segurança, prevenção de abusos e denúncias | Estado de segurança, detalhes do relatório, registros operacionais | Interesse legítimo e obrigação legal |

| Diagnóstico e estabilidade de serviço | Registos operacionais | Interesse legítimo |

| Tratamento de direitos e dúvidas do usuário | Informações fornecidas por você | Obrigação legal |

## 4. Criptografia ponta a ponta

Esta é a salvaguarda técnica mais crítica do Detour Post:

**A criptografia ocorre localmente no seu dispositivo.** Quando você toca em "Selar esta carta", todos os textos e fotos são criptografados no seu dispositivo antes da transmissão. As chaves de descriptografia são mantidas exclusivamente por você e pelo destinatário designado.

**Retemos apenas texto cifrado.** Nossos servidores armazenam apenas blobs criptografados. Não retemos chaves de descriptografia de nenhuma forma, nem fornecemos recuperação manual de chaves.

**Sem exceções.** Não mantemos backdoors administrativos, canais de inspeção de conteúdo ou substituições de atendimento ao cliente. Como não podemos visualizar texto simples, não podemos realizar filtragem automatizada de palavras-chave ou recomendação de conteúdo.

- Somente você poderá ver o conteúdo antes da entrega;

- Somente você e seu destinatário poderão ver o conteúdo após a entrega;

- Se você perder seu dispositivo e não tiver um backup pessoal do iCloud, não poderemos recuperar suas cartas – não temos as chaves;

- Os relatórios de segurança desencadeiam bloqueios de relacionamento e penalidades de conta, sem que operadores humanos leiam o conteúdo da carta.

**Backup pessoal.** Os backups de dados de cartas ocorrem exclusivamente através do seu iCloud pessoal, se ativado. Os backups residem inteiramente no ecossistema do seu ID Apple. Não temos acesso ao seu backup do iCloud ou às chaves do Keychain.

## 5. Permissões do sistema

O App solicita apenas uma permissão do sistema:

| Permissão | Quando solicitado | Finalidade |

|---|---|---|

| Notificações | Quando você opta por receber alertas de cartas | Alerta você quando cartas partem ou chegam. As cargas contêm apenas frases genéricas |

Desativar notificações não afeta o envio ou recebimento de cartas.

**Permissões que NÃO solicitamos:**

- **Fotos:** A seleção de fotos usa o seletor de fotos do sistema nativo. Apenas a única imagem selecionada é passada para o App; o acesso completo à biblioteca de fotos não é solicitado nem obrigatório.

- **Localização:** As cidades são selecionadas manualmente em uma lista. Nunca rastreamos as coordenadas do seu dispositivo.

- **Contatos, Câmera, Microfone, Rastreamento de Aplicativo (ATT):** Não solicitado e não existe código correspondente.

## 6. Terceiros

Nunca vendemos dados pessoais. As informações são compartilhadas estritamente com os provedores de infraestrutura necessários:

| Terceiros | Dados Processados ​​ | Finalidade | Notas |

|---|---|---|---|

| Maçã | ID da conta, compras no StoreKit, envio push, geocodificação MapKit | Autenticação, cobrança no aplicativo, notificações, exibição de mapas | Sujeito à [Política de Privacidade da Apple](https://www.apple.com/legal/privacy/) |

| Google | ID da conta | Autenticação opcional | Sujeito à [Política de Privacidade do Google](https://policies.google.com/privacy) |

| Serviço de notificação push da Apple (APNs) | Token push, carga útil de alerta genérico | Envio de notificação | As cargas úteis não contêm texto de carta ou identidades de destinatários |

| Provedores de infraestrutura em nuvem | Blobs de cartas criptografadas, razão de contas | Computação em nuvem e armazenamento seguro | Processado estritamente sob nossas instruções |

O aplicativo iOS não contém SDKs de rastreamento, publicidade ou análise de terceiros.

## 7. Armazenamento de dados e transferências internacionais

- **No seu dispositivo:** Cartas, rascunhos e preferências locais.

- **Em seu iCloud pessoal:** Backups de banco de dados criptografados em sua conta privada da Apple.

- **Em nossos servidores:** IDs de contas, nomes de exibição, cargas úteis de cartas criptografadas e registros de transações armazenados em infraestrutura de nuvem segura no exterior. Os dados podem ser transferidos e processados ​​internacionalmente sob estritas salvaguardas contratuais.

## 8. Períodos de retenção de dados

| Informação | Período de retenção |

|---|---|

| Data de Nascimento | Não armazenado. Avaliado uma vez no momento do registo e eliminado imediatamente |

| ID da conta, nome de exibição, cidade, conexões | Duração do ciclo de vida da conta; excluído ou irreversivelmente anonimizado após exclusão da conta |

| Texto cifrado de letras | Excluído imediatamente após confirmação de entrega pelo destinatário; cartas não reclamadas limpas após 90 dias |

| Livro de compras | Retido conforme exigido pelas leis financeiras, fiscais e de proteção ao consumidor |

| Empurrar Tokens | Removido dos servidores imediatamente após cancelamento de notificação ou exclusão de conta |

| Registros de serviço | Retido por uma breve janela de diagnóstico e excluído automaticamente. Não contém segredos privados |

## 9. Seus direitos de privacidade

Você pode exercer os seguintes direitos em relação às suas informações pessoais:

| Certo | Como fazer exercícios |

|---|---|

| Acesso e Portabilidade | Visualize perfil, compras e ativos em “Meu Perfil”; solicitar exportação via detourpost@aivolo.studio |

| Retificação | Edite o nome de exibição e a cidade nas configurações do perfil; contacte-nos para outros registos |

| Exclusão | Use o recurso "Excluir conta" do aplicativo ou entre em contato conosco para solicitações de dados específicas |

| Retirar consentimento | Desative as notificações nas configurações do aplicativo ou nas configurações do sistema iOS |

| Exclusão de conta | Navegue até "Meu perfil" → "Exclusão e isolamento de conta" → "Excluir conta" |

| Perguntas e dúvidas | Contate detourpost@aivolo.studio |

**O que acontece na exclusão da conta:** As cartas não enviadas são encerradas; as cartas que partiram continuam até seu destino; registros de perfil, relações de bloco e tokens de dispositivo são apagados imediata e permanentemente.

Respondemos a todas as solicitações de privacidade em **48 horas**.

## 10. Menores

O aplicativo é destinado a usuários com 13 anos ou mais (ou mais, dependendo dos requisitos da jurisdição local). Não coletamos intencionalmente dados pessoais de menores com idade inferior à idade de registro aplicável. Se você acredita que um menor se registrou sem autorização, entre em contato com detourpost@aivolo.studio e excluiremos imediatamente a conta.

## 11. Medidas de segurança

- Criptografia ponta a ponta para texto de cartas e fotos;

- Canais de transporte criptografados (TLS/HTTPS);

- Credenciais e chaves armazenadas em armazenamento seguro do sistema (iOS Keychain);

- Princípio do menor privilégio para infraestrutura de servidores;

- Verificação contínua de vulnerabilidades e auditorias de configuração.

## 12. Atualizações de políticas

Poderemos atualizar esta Política de Privacidade periodicamente. Mudanças significativas serão notificadas com destaque no aplicativo. Se você discordar dos termos modificados, poderá excluir sua conta.

## 13. Contate-nos e reclamações

- **Operador:** Yong Wang

- **E-mail:** detourpost@aivolo.studio

Respondemos às perguntas dentro de **48 horas**. Você também tem o direito de apresentar uma reclamação à autoridade supervisora ​​local de proteção de dados.

© 2026 Yong Wang. Todos os direitos reservados.

---

© 2026 Yong Wang. All rights reserved.
