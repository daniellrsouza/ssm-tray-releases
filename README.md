# SSM Tray para Windows

Gerenciador de túneis AWS Systems Manager na bandeja do Windows.

Este repositório distribui somente instaladores e arquivos de atualização. O código-fonte é mantido separadamente.

## Instalar

Baixe o instalador `.exe` da versão mais recente na página [Releases](https://github.com/daniellrsouza/ssm-tray-releases/releases). Requer Windows x64, AWS CLI v2 e Session Manager Plugin para conectar túneis.

O instalador não possui assinatura digital. O Windows poderá solicitar confirmação ou bloquear a execução conforme as políticas da máquina.

Novas instalações começam sem túneis. Crie suas conexões ou importe um arquivo JSON compartilhado pela sua equipe. Nenhum host, target ou perfil de ambiente real é distribuído com o app.

## Atualizações

A partir da versão 1.3.0, use Preferências → Atualizações para buscar, baixar e instalar versões novas. A instalação encerra as sessões de túnel e reinicia o app após confirmação. As configurações locais são preservadas.

Quem usa a versão 1.2.0 ou anterior precisa instalar a 1.3.0 manualmente para habilitar o mecanismo de atualização.
