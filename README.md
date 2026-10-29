# Sims 4 Updater — arquivos do cliente

Este repositório distribui instaladores, atualizações e hashes do aplicativo.
O código-fonte é mantido separadamente. Os arquivos do jogo não ficam neste repositório.

## Instalar e atualizar

Versão pública atual: **1.0.49**.

[Baixar o instalador para Windows x64](https://github.com/jstoreuser/updater-releases/releases/latest/download/Sims4Updater-setup.exe) · [Última versão e notas](https://github.com/jstoreuser/updater-releases/releases/latest)

O cliente é instalado somente para seu usuário, com atalho no menu Iniciar e desinstalação nas configurações do Windows. Requer Microsoft Edge WebView2 Runtime; o .NET já acompanha o aplicativo.

Ao abrir, o Updater confere sua atualização, prepara a nova versão autenticada e reinicia antes de liberar as operações do jogo. Se houver falha, mantém a recuperação e oferece ajuda e nova tentativa.
Enquanto aberto, também verifica atualizações e adia a preparação durante uma operação ativa. A saída normal usa o controlador de atualização; a versão anterior recente fica disponível para recuperação.
Não são criados serviços, tarefas agendadas ou inicialização automática com o Windows.

Se o aplicativo já estiver instalado, use sua atualização automática. O instalador inicial não sobrescreve uma instalação existente.
O ZIP é uma alternativa portátil; instalações portáteis antigas precisam passar pelo instalador para habilitar o gerenciamento automático.

## Diagnóstico e componentes

A ajuda permite revisar e salvar um relatório local. Nada é enviado automaticamente; revise o conteúdo antes de compartilhar no [suporte](https://github.com/jstoreuser/updater-releases/issues).
Os avisos de terceiros acompanham o ZIP, assim como o [inventário dos componentes](https://github.com/jstoreuser/updater-releases/releases/latest/download/components.spdx.json).

## Integridade e Windows

Os arquivos `.sha256` permitem comparar o download. `app-update.json`, `release.signed.json` e `root.json` são metadados públicos de autenticidade do aplicativo.
As chaves privadas não são distribuídas. Essas assinaturas internas não são certificados Authenticode.

O aplicativo e o instalador continuam sem assinatura pública de código. O GitHub não garante aceitação pelo SmartScreen ou Smart App Control.
Se houver bloqueio, registre a mensagem exata para análise. Não altere o Defender, exclusões ou políticas de segurança para executar o cliente.

A validação em outros ambientes Windows e no jogo continua em andamento. Os ensaios locais não substituem essa homologação.
