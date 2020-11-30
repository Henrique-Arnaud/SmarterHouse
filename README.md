# SmarterHouse

## Visão Geral

**Smarter House** é um projeto de uma casa automatizada por meio de comandos passados pela internet. Seu app mobile tem a função de se logar com a conta de sua casa e liberar as funções, sendo elas: acender e apagar as lâmpadas, abrir ou fechar cortinas, abrir ou fechar o portão da garagem, definir uma temperatura para que o ventilador possa ligar sozinho caso alcance tal temperatura, ou simplesmente ligá-lo no mesmo momento. Conta também com um sistema de biometria para cadastrar e reconhecer a digital de quem mora na casa.
Já o aplicativo web tem como função ver os planos e seus custos, ter uma visão geral do produto, cadastrar sua casa ou acessá-la. Ao acessar, o usuário terá acesso a um gráfico de uso dos módulos instalados, facilitando o gerenciamento de recursos, como energia, e tendo ciência do que acontece em sua casa em tempo real.

## Recursos Técnicos

No o desenvolvimento do aplicativo mobile foi usada a framework Xamarin.Forms, que utiliza da linguagem C# para a criação de aplicativos cross-platform. A consulta e inserção de valores no banco de dados foi feito por meio do consumo de uma API em PHP, criada e hospedada para esse projeto. A comunicação com o Arduino foi feita por meio do protocolo TCP, utilizando um servidor local como intermediador, o qual recebia um pacote em json e enviava para o arduino interpretar conforme foi programado.
