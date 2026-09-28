# Política de Privacidade do Milli

**Data de vigência:** 1º de agosto de 2026
**Última atualização:** 16 de setembro de 2026

## Resumo

O Milli não coleta seus dados. Não existe servidor do Milli, nem análises (analytics), nem publicidade, nem rastreamento, nem SDKs de terceiros. Tudo o que você insere permanece no seu dispositivo e — somente se você ativar a sincronização do iCloud — na sua própria conta particular do iCloud, à qual não temos acesso.

## Quem somos

O Milli ("o aplicativo") é desenvolvido por **IVAN CAYABYAB** ("nós", "nos").

Para qualquer dúvida sobre esta política ou sobre sua privacidade, entre em contato conosco pelo **ivnsjdev@gmail.com**.

## O que o Milli armazena, e onde

O Milli é um aplicativo de finanças pessoais. As informações que você insere ficam armazenadas no seu dispositivo, em um banco de dados local. Nunca as recebemos.

| O que você insere | Onde fica armazenado | Nós vemos isso? |
| --- | --- | --- |
| Transações, valores, notas, datas | No seu dispositivo | Não |
| Contas e livros-caixa | No seu dispositivo | Não |
| Categorias e orçamentos | No seu dispositivo | Não |
| Pagamentos recorrentes e lembretes | No seu dispositivo | Não |
| Valores de referência salarial que você insere | No seu dispositivo | Não |
| Foto de perfil | No seu dispositivo | Não |
| Configurações e preferências do aplicativo | No seu dispositivo | Não |
| Transações inseridas no Apple Watch | No seu Apple Watch e depois no iPhone | Não |

Não coletamos, transmitimos, vendemos, alugamos nem compartilhamos nada disso, porque o aplicativo não tem capacidade de enviar essas informações a lugar nenhum. O Milli não faz solicitações de rede a nenhum servidor operado por nós ou por terceiros.

## Sincronização com o iCloud (opcional)

Se você ativar a sincronização com o iCloud, o Milli usa o CloudKit da Apple para copiar seus dados para o **banco de dados privado da sua própria conta do iCloud**, para que apareçam nos seus outros dispositivos conectados com o mesmo Apple Account.

- Esses dados ficam armazenados na sua Apple Account, não na nossa.
- Não temos acesso a eles nem capacidade de lê-los, exportá-los ou recuperá-los.
- A Apple processa esses dados conforme descrito na
  [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

Você pode desativar a sincronização com o iCloud a qualquer momento nas configurações do aplicativo, ou desativá-la em todo o sistema em **Ajustes → seu nome → iCloud** no seu dispositivo.

## Apple Watch

O Milli inclui um aplicativo para Apple Watch, disponível como parte dos recursos premium, para visualizar os números do dia e adicionar transações diretamente do pulso.

**Como os dados chegam até lá.** O aplicativo do relógio não tem banco de dados próprio, conta própria nem acesso próprio à rede. Tudo o que ele exibe vem diretamente do seu iPhone pareado, por meio do **WatchConnectivity** da Apple, o link do sistema entre um iPhone e o Apple Watch pareado com ele. Esse link é direto entre os dispositivos, gerenciado pelo iOS e pelo watchOS; ele não passa por nenhum servidor nosso, e nenhum dado do Milli é enviado a nós em momento algum.

**O que trafega nesse link.** Apenas o que a tela do relógio precisa: suas contas e seus nomes, ícones, cores e moedas; as transações do dia e o saldo líquido do dia dessas contas; os nomes e ícones das suas categorias; suas preferências de idioma e formato numérico; e se os recursos premium estão desbloqueados. Todo o seu histórico de transações, notas, orçamentos e a foto de perfil permanecem no iPhone. No sentido contrário, uma transação inserida no relógio chega ao iPhone como um valor, uma categoria e uma conta, e é salva no seu livro-caixa por lá.

**O que o relógio mantém.** O relógio armazena o instantâneo mais recente que recebeu, além de qualquer transação que você tenha inserido e que o iPhone ainda não tenha confirmado, no armazenamento privado do próprio aplicativo, no próprio relógio. É isso que permite que o aplicativo abra com números reais e que você registre gastos quando o iPhone estiver fora de alcance. Tudo o que for inserido enquanto os dois estiverem separados fica retido no relógio até que o iPhone volte a estar acessível, e então é entregue a ele.

- O aplicativo do relógio **não** usa o iCloud e não mantém nenhuma cópia dos seus dados fora do relógio.
- O aplicativo do relógio **não** faz solicitações de rede.
- Ele **não** acessa dados de saúde, atividade física, frequência cardíaca, treinos ou localização, e não solicita nenhuma dessas permissões.

**Para remover a cópia do relógio,** desinstale o Milli do relógio — no relógio, pressione e segure o ícone do aplicativo e remova-o, ou no iPhone, abra o aplicativo **Watch**, selecione o Milli e desative *Show App on Apple Watch*. Desparear o relógio também apaga seus aplicativos e os dados deles.

## Face ID, Touch ID e senha de acesso

Se você ativar o bloqueio do aplicativo, o Milli solicita ao iOS que o autentique. Seus dados biométricos são tratados inteiramente pelo Secure Enclave da Apple e **nunca são compartilhados com o aplicativo** — o iOS informa ao Milli apenas se a autenticação foi bem-sucedida ou não. Se você definir uma senha de acesso do aplicativo, ela fica armazenada somente no seu dispositivo.

## Câmera e biblioteca de fotos

O Milli solicita acesso à câmera ou à biblioteca de fotos apenas quando você opta por definir uma foto de perfil. A imagem fica armazenada no seu dispositivo (e no seu próprio iCloud, se a sincronização estiver ativada). O Milli não envia fotos para lugar nenhum e não acessa sua biblioteca em segundo plano.

## Notificações

Se você ativar lembretes para pagamentos recorrentes, o Milli agenda **notificações locais** no seu dispositivo. Elas são geradas localmente pelo iOS. Nenhum servidor de push está envolvido, e nenhum conteúdo do lembrete sai do seu dispositivo.

## Compras

O Milli oferece uma compra única no aplicativo para desbloquear os recursos premium. A compra é processada inteiramente pela **Apple**, por meio da App Store. Nunca recebemos seus dados de pagamento, número de cartão ou endereço de cobrança. O Milli apenas pergunta à Apple se a Apple Account atual possui a compra, para saber se deve desbloquear os recursos premium. O aplicativo do Apple Watch não consegue consultar a App Store sozinho, então o iPhone informa a ele, pelo mesmo link privado, se a compra está desbloqueada — um único valor de sim ou não, sem nenhuma informação de pagamento. As compras são regidas pelos
[Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).

## Backups que você exporta

O Milli permite exportar um arquivo de backup dos seus dados. Depois de exportado, esse arquivo fica sob seu controle, e esta política deixa de protegê-lo — onde quer que você o salve ou envie (Arquivos, iCloud Drive, e-mail, outro aplicativo), passam a valer os termos desse serviço. Trate um arquivo de backup como trataria um extrato bancário.

## Widgets

Os widgets do Milli na tela inicial leem uma pequena quantidade dos seus dados de uma área de armazenamento privada, compartilhada entre o aplicativo e sua própria extensão de widget no seu dispositivo. Nada nessa área compartilhada é transmitido para fora do dispositivo.

## O que NÃO fazemos

Para deixar explícito, o Milli **não**:

- coleta ou transmite seus dados pessoais ou financeiros para nós
- usa serviços de análise (analytics), relatório de falhas ou telemetria
- inclui publicidade ou identificadores de publicidade
- rastreia você em outros aplicativos ou sites, nem compartilha dados com corretores de dados
- cria contas de usuário, nem exige e-mail, telefone ou login
- lê dados de saúde, atividade física ou localização do seu iPhone ou Apple Watch
- usa seus dados para treinar modelos de aprendizado de máquina

O selo de privacidade do Milli na App Store reflete isso: **Data Not Collected (dados não coletados)**.

## Comunicações de suporte

Se você nos enviar um e-mail de suporte, recebemos seu endereço de e-mail, sua mensagem e qualquer informação sobre dispositivo, versão do aplicativo, captura de tela ou outra informação que você optar por incluir. Usamos isso apenas para responder, investigar o problema e melhorar o Milli. Não nos envie seu livro-caixa, extratos ou outros registros financeiros — não precisamos deles para responder a uma pergunta de suporte.

Onde o GDPR ou o UK GDPR se aplicam, tratamos os e-mails de suporte com base em nosso interesse legítimo em responder às pessoas que nos escrevem e em corrigir os problemas relatados. Não há outro tratamento para o qual seja necessário buscar uma base legal, porque o Milli não nos envia nada por conta própria.

O e-mail de suporte é opcional e acontece fora do Milli. Ele é processado pelo seu provedor de e-mail e pelo Google, que hospeda nossa caixa de suporte, conforme a
[Google Privacy Policy](https://policies.google.com/privacy). Os servidores de e-mail do Google ficam localizados nos Estados Unidos, então uma mensagem de suporte enviada a nós é processada lá. Mantemos as mensagens de suporte por até 24 meses, e por mais tempo apenas quando exigido por obrigação legal, de segurança ou de manutenção de registros. Você pode nos pedir para excluir sua correspondência de suporte enviando um e-mail para o endereço abaixo.

## Retenção e exclusão de dados

O Milli não nos envia nada, então não temos nenhum dos seus dados financeiros e não há nada para reter ou excluir. A única exceção é o e-mail de suporte que você opta por nos enviar, abordado acima.

- **Para excluir dados locais:** exclua o aplicativo do seu dispositivo ou use as próprias opções de redefinição/exclusão do aplicativo.
- **Para excluir dados no seu Apple Watch:** remova o Milli do relógio, conforme descrito na seção sobre o Apple Watch acima.
- **Para excluir dados sincronizados:** desative a sincronização com o iCloud e remova os dados do aplicativo em **Ajustes → seu nome → iCloud → Gerenciar Armazenamento da Conta**.

Excluir o aplicativo não remove automaticamente os dados já sincronizados com sua conta do iCloud; use a etapa acima para isso. Excluir o aplicativo no iPhone também remove seu complemento para Apple Watch.

## Seus direitos

Dependendo de onde você mora, você pode ter direitos garantidos pelo GDPR, UK GDPR, CCPA/CPRA ou leis semelhantes — incluindo o direito de acessar, corrigir, exportar ou excluir seus dados pessoais, e o direito de não ser discriminado por exercê-los.

O Milli foi projetado para que você exerça esses direitos diretamente: seus dados estão no seu próprio dispositivo e na sua própria conta do iCloud, sob seu controle o tempo todo. Não temos nenhuma cópia, então não podemos produzir, alterar ou apagar uma em seu nome. Não vendemos nem compartilhamos dados pessoais, e nunca o fizemos.

Se você acredita que não cumprimos nossas obrigações, pode entrar em contato conosco pelo endereço acima, e tem o direito de registrar uma reclamação junto à autoridade de proteção de dados do seu país.

## Crianças

O Milli não é direcionado a crianças e não coleta intencionalmente nenhuma informação de ninguém, incluindo crianças menores de 13 anos (ou a idade mínima equivalente no seu país). Como o aplicativo não coleta nenhum dado, nenhuma informação desse tipo pode ser transmitida a nós.

## Alterações nesta política

Se esta política mudar, atualizaremos esta página e revisaremos a data de "Última atualização" acima. Mudanças relevantes também serão mencionadas nas notas de versão do aplicativo. Recomendamos que você revise esta página periodicamente.

## Contato

Dúvidas, preocupações ou solicitações:

**ivnsjdev@gmail.com**
