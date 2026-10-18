# Sims 4 Updater — arquivos do cliente

Este repositório distribui instaladores, atualizações e hashes do aplicativo.
O código-fonte é mantido separadamente. Os arquivos do jogo não ficam neste repositório.

## Instalar e atualizar

Baixe o `Sims4Updater-<versão>-setup.exe` na [última versão](https://github.com/jstoreuser/updater-releases/releases/latest).
O cliente é instalado somente para seu usuário, com atalho no menu Iniciar e desinstalação nas configurações do Windows.

O aplicativo verifica e baixa atualizações enquanto está aberto. A troca da versão acontece ao usar **Sair**, depois que a operação atual terminou.
Também é possível usar **Reiniciar** quando uma atualização estiver preparada. A versão anterior fica disponível para recuperação.
Não são criados serviços, tarefas agendadas ou inicialização automática com o Windows.

O ZIP é uma alternativa portátil. Clientes portáteis antigos precisam passar pelo instalador para habilitar esse gerenciamento automático.
Se o aplicativo já estiver instalado, use sua atualização automática. O instalador inicial não sobrescreve uma instalação existente.

## Integridade e Windows

Os arquivos `.sha256` permitem comparar o download. `app-update.json`, `release.signed.json` e `root.json` são metadados públicos de autenticidade do aplicativo.
As chaves privadas não são distribuídas. Essas assinaturas internas não são certificados Authenticode.

Esta versão continua sem assinatura pública de código. Um instalador ou o GitHub não garantem aceitação pelo SmartScreen ou Smart App Control.
Se houver bloqueio, registre a mensagem exata para análise. Não altere o Defender, exclusões ou políticas de segurança para executar o cliente.

Esta entrega é destinada ao piloto acompanhado. A validação local não substitui o teste no computador participante.
