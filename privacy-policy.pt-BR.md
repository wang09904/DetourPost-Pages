# Política de Privacidade do Detour Post

**Rascunho para revisão interna · atualizado em 6 de outubro de 2026 · não publicado nem vigente · revisões jurídica e linguística em andamento.**

---

## 1. Introdução

O Detour Post é operado por Yong Wang, uma pessoa física. Nesta política, “nós” se refere a Yong Wang, que determina como os dados pessoais são tratados para o serviço.

Esta Política de Privacidade explica quais informações coletamos, por que as processamos, como são tratadas e armazenadas, períodos de retenção e como você pode exercer seus direitos de privacidade.

Nosso princípio fundamental é simples: **Suas cartas são privadas entre você e o destinatário. Não podemos lê-las e não temos intenção de lê-las.**

## 2. Informações que processamos

### 2.1 Informações que você fornece ativamente

| Informação | Detalhes | Necessidade |
|---|---|---|
| Conta e identidade de login | Identificador da conta, identificador do provedor de login e e-mail verificado fornecidos pela Apple ou pelo Google | Necessários para criar e autenticar a conta |
| Credenciais de login | Tokens de autenticação da sessão; o serviço armazena um hash de cada token | Necessárias para acesso seguro |
| Mês e ano de nascimento e região selecionada | O app verifica no seu dispositivo o requisito de idade com base no mês e ano informados e na região escolhida | Necessários para o cadastro. O mês e o ano de nascimento ficam nos dados do app associados à sua conta no dispositivo, onde podem ser consultados e alterados; o mês e o ano de nascimento não são enviados nem armazenados em nossos servidores. O serviço mantém separadamente a versão da regra aplicada e a região de login |
| Nome de exibição | Nome visível para as pessoas com quem você troca cartas | Obrigatório para concluir o cadastro; pode ser alterado depois no perfil |
| Cidade | Cidade escolhida para enviar cartas, incluindo os dados do local salvos pelo app | Obrigatória para concluir o cadastro e enviar cartas |
| Informações de conexão | Status de relacionamento, códigos de convite e códigos secretos para receber cartas | Necessário para troca de cartas |
| Conteúdo da carta | Texto, papel de carta e decorações escolhidos, fotos anexadas, mensageiro e horário de entrega escolhido ou programado | Criado somente quando você escolhe enviar uma carta |
| Dados de denúncias | IDs de quem denuncia e da conta denunciada; tipo, origem e ID do alvo; motivo selecionado; ID de correlação para auditoria; status e data de criação. **Não incluem texto de cartas, fotos, texto livre ou coordenadas.** A denúncia também bloqueia a conta denunciada e encerra as cartas que essa pessoa enviou a você e que ainda não foram entregues | Criados somente quando você faz uma denúncia |
| Notas privadas | Notas que você escreve sobre um contato | Opcionais. Ficam no seu dispositivo e só são incluídas no backup pessoal do iCloud se você o ativar; não são enviadas ao nosso serviço |

**Criptografia de ponta a ponta de cartas e fotos.** O texto e as fotos das cartas são criptografados no seu dispositivo antes de serem enviados ao serviço. Para esse conteúdo, mantemos apenas dados criptografados, sem as chaves de descriptografia. Os demais dados de conta e do serviço descritos nesta Política são tratados separadamente. Veja a Seção 4.

### 2.2 Informações geradas automaticamente durante o uso

| Informação | Detalhes | Finalidade |
|---|---|---|
| Status da entrega | Partida, etapas da viagem, chegada, retirada e encerramento | Envio e entrega de cartas |
| Estado da conta e segurança | Situação da conta, listas de bloqueios recíprocos e status do tratamento de denúncias | Administração de contas e prevenção de abusos |
| Registros de compras e ativos | Pedidos, movimentações e saldos de moedas, estoque de selos e de unidades do serviço de agendamento de entrega, propriedade permanente de itens, assinaturas e estado da restauração de compras | Cobrança, prestação do serviço, restauração e reembolsos |
| Tokens push e de dispositivo | Tokens push do dispositivo e metadados necessários | Envio de notificações de status de cartas |
| Registros de serviço | Logs operacionais de API, rastreamentos de erros e diagnósticos de desempenho | Segurança, estabilidade e solução de problemas |

**Notificações push.** O aviso visível usa um texto genérico. Os dados enviados também incluem uma categoria de notificação e um identificador de evento opaco para abrir a tela correspondente; não incluem texto de cartas, fotos ou localização. Os registros operacionais podem conter detalhes técnicos de solicitações ou erros; veja a Seção 8.

### 2.3 O que NUNCA fazemos

- NÃO acessamos sua biblioteca completa de fotos, contatos ou localização GPS precisa;

- O app não usa identificadores de publicidade (IDFA/IDFV) para direcionamento de anúncios nem para rastreamento entre apps e não inclui SDK de publicidade.

- NÃO usamos dados de cartas para treinar modelos de IA — não temos acesso ao conteúdo sem criptografia;

- NUNCA vendemos suas informações pessoais a terceiros.

## 3. Por que processamos informações

| Finalidade | Informações envolvidas |
|---|---|
| Envio e recebimento de cartas | ID da conta, nome de exibição, cidade, informações de relacionamento, carta criptografada e status de entrega |
| Compras no app, cumprimento e reembolsos | Registros de compras e ativos, status da assinatura |
| Notificações de entrega | Token push e status de entrega |
| Segurança, denúncias e prevenção de abuso | Status da conta e de segurança, dados de denúncias e registros operacionais |
| Diagnóstico e estabilidade do serviço | Registros operacionais |
| Solicitações de direitos e reclamações | Informações que você nos fornece |

A base legal de cada tratamento depende da legislação aplicável e das circunstâncias de cada operação. Este rascunho ainda não atribui uma base legal a cada finalidade. Essa análise deve ser concluída antes da publicação; não utilizaremos uma base que não seja aplicável conforme a legislação pertinente.

## 4. Criptografia ponta a ponta

Esta é a salvaguarda técnica mais crítica do Detour Post:

**A criptografia ocorre localmente no seu dispositivo.** Quando você toca em "Selar esta carta", todos os textos e fotos são criptografados no seu dispositivo antes da transmissão. As chaves de descriptografia são mantidas exclusivamente por você e pelo destinatário designado.

**Texto e fotos das cartas são mantidos apenas em formato criptografado.** Não possuímos suas chaves de descriptografia nem oferecemos recuperação manual de chaves. Também processamos os dados de conta e do serviço descritos nesta Política.

**Sem exceções.** Não mantemos backdoors administrativos, canais de inspeção de conteúdo ou exceções que permitam ao atendimento ao cliente acessar o conteúdo. Como não podemos visualizar texto simples, não podemos realizar filtragem automatizada de palavras-chave ou recomendação de conteúdo.

- Somente você poderá ver o conteúdo antes da entrega;

- Somente você e seu destinatário poderão ver o conteúdo após a entrega;

- Se você perder seu dispositivo e não tiver um backup pessoal do iCloud, não poderemos recuperar suas cartas – não temos as chaves;

- Uma denúncia de segurança registra o motivo selecionado e os identificadores de conta ou carta relacionados, aplica um bloqueio recíproco e encerra as cartas ainda não entregues que a pessoa denunciada enviou a você. A denúncia não revela o conteúdo das cartas. Se Yong Wang tomar conhecimento dela, fará esforços razoáveis para analisá-la e adotar medidas apropriadas quando necessário. Não há prazo específico de análise ou resposta prometido; outras medidas sobre a conta dependem de análise.

**Backup pessoal.** Se você o ativar, dados selecionados da sua bolsa postal — incluindo notas privadas de contatos, rascunhos, dados de convites pendentes e cartas salvas — são criptografados no dispositivo e copiados para seu iCloud pessoal pelo CloudKit. A chave do backup fica no Keychain do dispositivo. Após a verificação de um backup, uma chave de recuperação é armazenada no Keychain do iCloud para que possa estar disponível nos seus outros dispositivos Apple. Não recebemos nenhuma dessas chaves e não podemos descriptografar o backup.

## 5. Permissões do sistema

O app pode solicitar permissão para notificações depois da primeira carta enviada ou recebida; você também pode solicitá-la nos Ajustes. Ao escolher salvar uma imagem gerada do cartão de viajante na biblioteca de fotos, o app solicita permissão apenas para adicionar fotos.

| Permissão | Quando solicitado | Finalidade |
|---|---|---|
| Notificações | Após a primeira carta enviada ou recebida, ou ao ativar os avisos nos Ajustes | O aviso visível é genérico. Os dados enviados também incluem uma categoria e um identificador de evento opaco para abrir a tela correspondente, sem texto de cartas ou localização |
| Fotos (somente adicionar) | Ao escolher salvar um cartão de viajante gerado | Salva essa imagem na biblioteca sem permitir que o app navegue pelas suas fotos |

O app sincroniza suas preferências de notificação com o serviço, que as usa para decidir quais avisos enviar. A permissão de notificações do iOS controla a exibição dos avisos no dispositivo. Nenhuma dessas ações, por si só, exclui ou desativa o registro do token do dispositivo no serviço. Recusar uma permissão opcional não impede, por si só, o envio ou recebimento básico de cartas.

**Outros detalhes sobre permissões:**

- **Fotos:** Ao anexar uma foto à carta, o seletor de fotos do sistema dá ao app acesso apenas à imagem escolhida; o app não navega pela biblioteca completa. Salvar um cartão de viajante gerado usa a permissão separada de adicionar fotos e a solicitação correspondente do sistema.

- **Localização:** Você escolhe a cidade de cada carta. Não coletamos a localização do dispositivo nem rastreamos deslocamentos. O app inclui um catálogo limitado de nomes e coordenadas de países e cidades para sugestões de busca local, resultados offline limitados e rótulos no mapa. Primeiro consulta esse catálogo; quando encontra uma cidade, usa o resultado localmente e não envia o termo de busca ao MapKit. Se não encontra, solicita resultados de lugares ao Apple MapKit. Quando o catálogo não tem o centro do país ou região escolhidos, o app pode enviar o nome à Apple pelo Core Location para posicionar o mapa. O Core Location também é usado para geocodificar ao contrário um ponto escolhido no mapa. Se a Apple não retornar um resultado, o app pode usar uma cidade próxima do catálogo como alternativa limitada. A Apple recebe o texto da busca, o nome do país ou região ou as coordenadas do ponto no mapa envolvido. Esses recursos não exigem permissão de localização.

- **Contatos, Câmera, Microfone e Rastreamento de Apps (ATT):** Essas permissões não são solicitadas e não há código correspondente.

## 6. Terceiros

Não vendemos informações pessoais. Os prestadores necessários às funções que você usa processam os dados correspondentes. Para o armazenamento e processamento do texto e das fotos das cartas nos servidores do serviço, esses prestadores recebem dados criptografados; não fornecemos a eles as chaves de descriptografia.

| Terceiro | Dados processados | Finalidade | Observações |
|---|---|---|---|
| Apple | Identificador de login e e-mail verificado, compras e assinaturas no app, token push e entrega de notificações, backups criptografados do cofre pessoal no iCloud e chaves de recuperação quando ativados, termos enviados nas buscas de lugares do MapKit, nomes de países ou regiões enviados para posicionar o mapa quando o catálogo não tem um centro e coordenadas de pontos do mapa enviadas para geocodificação inversa do Core Location | Login, pagamentos, notificações, backup e recursos de mapa e busca | Aplica-se a [Política de Privacidade da Apple](https://www.apple.com/legal/privacy/) |
| Google | Identificador do provedor de login e e-mail verificado, quando fornecido | Login opcional com Google | Consulte a [Política de Privacidade do Google](https://policies.google.com/privacy) |
| Serviço de notificações push da Apple (APNs) | Token push, texto genérico do aviso, categoria da notificação e identificador de evento opaco | Envio de notificações | Os dados enviados não incluem texto de cartas, fotos ou localização precisa |
| Cloudflare | Cartas criptografadas, dados de conta e login, cidade selecionada, compras e entregas, tokens push e registros do serviço | Computação em nuvem, banco de dados e armazenamento de objetos | Consulte a [Política de Privacidade da Cloudflare](https://www.cloudflare.com/privacypolicy/) |

O aplicativo iOS não contém SDKs de rastreamento, publicidade ou análise de terceiros.

## 7. Armazenamento de dados e transferências internacionais

- **No seu dispositivo:** Cartas, rascunhos, notas privadas de contatos e preferências.

- **No seu iCloud pessoal:** Se ativado, um backup criptografado de dados selecionados da bolsa postal, incluindo notas privadas de contatos, rascunhos, dados de convites pendentes e cartas salvas.

- **Nos nossos servidores:** Identificadores de conta e login, e-mail verificado, nomes de exibição, dados salvos da cidade selecionada, relações e entregas, cartas criptografadas, compras, tokens push e registros do serviço. Nossa infraestrutura fica fora do país ou da região de alguns usuários, de modo que esses dados podem ser processados internacionalmente.

## 8. Períodos de retenção de dados

| Informação | Prazo de retenção |
|---|---|
| Mês e ano de nascimento | O mês e o ano de nascimento ficam nos dados do app associados à conta no seu dispositivo, onde podem ser consultados e alterados; o mês e o ano de nascimento não são enviados nem armazenados em nossos servidores |
| Conta e identidade de login | A exclusão da conta a desativa, revoga as sessões e remove dados do perfil e das notificações. O desenho atual do serviço mantém o registro da conta excluída e o ID do provedor de login; ainda não foi definido um prazo fixo para exclusão. |
| Conteúdo criptografado das cartas | A limpeza da cópia criptografada no servidor começa após a confirmação de que o dispositivo do destinatário salvou a carta completa. Sem essa confirmação, a carta fica indisponível 90 dias depois que a carta ficar disponível para o destinatário (para cartas programadas, a partir do horário marcado) e entra no processo de limpeza. O término desse prazo não restaura a conta excluída do remetente. |
| Registros de compras e cumprimento | Mantidos para administrar compras, reembolsos e entregas já iniciadas. Ainda não há um prazo fixo definido. |
| Tokens push | As preferências no app determinam quais avisos são enviados; a permissão de notificações do iOS controla sua exibição no dispositivo. A exclusão da conta remove o token do dispositivo; tokens que o APNs informar como inválidos são desativados. |
| Denúncias de segurança | Motivo selecionado, IDs da conta ou da carta relacionada, status e data de criação. Ainda não foram definidos prazo fixo nem critério de exclusão. |
| Registros do serviço | Podem ser criados para segurança, confiabilidade e diagnóstico e incluir detalhes técnicos de solicitações ou erros. Ainda não há um prazo fixo definido. |

Os prazos de retenção ou critérios de exclusão de registros de contas excluídas e IDs de provedores, compras e cumprimento, denúncias de segurança e registros do serviço ainda não foram definidos. Essas regras e a base legal de cada finalidade precisam ser avaliadas antes da publicação.

## 9. Seus direitos de privacidade

Dependendo de onde você mora, a legislação aplicável pode lhe dar direitos de acessar, corrigir, excluir ou obter uma cópia de informações pessoais, opor-se a certos tratamentos, restringi-los ou retirar seu consentimento. Esta Política não limita os direitos que a lei lhe assegura. Envie solicitações para detourpost@aivolo.studio; podemos pedir informações necessárias para confirmar sua identidade.

| Direito | Como exercer |
|---|---|
| Acesso ou cópia | Abra “Eu” para consultar dados da conta, compras e ativos; entre em contato para solicitações não disponíveis no app |
| Correção | Abra “Eu” → “Perfil” para alterar nome de exibição e cidade; entre em contato sobre outros dados |
| Exclusão | Use o recurso "Excluir conta" do aplicativo ou entre em contato conosco para solicitações de dados específicas |
| Retirada do consentimento | Escreva para detourpost@aivolo.studio para retirar o consentimento de um tratamento que dependa dele; a legislação aplicável determina os efeitos sobre o tratamento anterior |
| Exclusão de conta | Abra “Eu” → “Excluir Conta” → “Excluir conta” |
| Perguntas e dúvidas | Contate detourpost@aivolo.studio |

**Ao excluir a conta:** A conta é desativada, as sessões são revogadas e os dados de perfil e notificações são removidos. Cartas que ainda não partiram são encerradas; as que já partiram seguem o plano de entrega existente. Excluir a conta no app não cancela uma assinatura cobrada pela Apple; gerencie ou cancele-a nos ajustes de assinaturas da sua conta Apple. O serviço mantém atualmente um registro da conta excluída e a identidade do provedor de login; veja a Seção 8.

Trataremos as solicitações de acordo com a legislação aplicável. O prazo dependerá da natureza da solicitação; não prometemos um prazo geral.

## 10. Menores

O app é destinado a pessoas que atendam à idade mínima aplicável, que é de pelo menos 16 anos (15 anos na Coreia do Sul) e pode variar em algumas regiões. No cadastro, o app verifica no seu dispositivo, com base no mês e ano de nascimento informados e na região escolhida, se você atende ao requisito de idade aplicável. O mês e o ano ficam nos dados do app no seu dispositivo e não são enviados nem armazenados em nossos servidores.

Se você acredita que alguém talvez não tenha a idade mínima aplicável, escreva para detourpost@aivolo.studio. Se Yong Wang tomar conhecimento do caso, fará esforços razoáveis para analisá-lo e tomar as medidas exigidas pela legislação aplicável. Não há prazo fixo de análise ou resposta prometido. Responsáveis legais também podem escrever para esse endereço.

## 11. Medidas de segurança

- Criptografia ponta a ponta para texto de cartas e fotos;

- Canais de transporte criptografados (TLS/HTTPS);

- Credenciais e chaves armazenadas em armazenamento seguro do sistema (iOS Keychain);

- O app usa armazenamento protegido pelo dispositivo para credenciais e chaves de criptografia locais.

Nenhuma medida pode garantir segurança absoluta. Se ocorrer um incidente de segurança de dados, forneceremos os avisos e tomaremos as medidas exigidas pela legislação aplicável.

## 12. Atualizações de políticas

Podemos atualizar esta Política. O texto atual e a data da atualização estarão nesta página. Não usaremos informações pessoais para finalidades incompatíveis com as descritas aqui. Quando a legislação aplicável exigir aviso sobre uma mudança relevante ou um novo uso dos dados, daremos esse aviso por um meio apropriado.

## 13. Contate-nos e reclamações

- **Operador:** Yong Wang

- **E-mail:** detourpost@aivolo.studio

Para perguntas ou reclamações, escreva para detourpost@aivolo.studio. Se Yong Wang tomar conhecimento da mensagem, fará esforços razoáveis para analisá-la e responder quando apropriado. Não há prazo específico prometido. Você também pode apresentar uma reclamação à autoridade de proteção de dados competente para o seu caso.
