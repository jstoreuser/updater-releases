# Sims 4 Updater — downloads

**Versão recomendada: 1.0.52 · Windows x64**

[**Baixar o instalador atual**](https://github.com/jstoreuser/updater-releases/releases/latest/download/Sims4Updater-setup.exe)
· [Notas da versão](https://github.com/jstoreuser/updater-releases/releases/latest)
· [Conferir SHA-256](https://github.com/jstoreuser/updater-releases/releases/latest/download/Sims4Updater-setup.exe.sha256)

Este repositório distribui o cliente do projeto, suas atualizações e metadados
públicos. O código-fonte é privado. Os arquivos do jogo não são hospedados aqui.

## Instalar e atualizar

O instalador inclui .NET, bibliotecas nativas e o instalador oficial do WebView2,
preparado quando necessário. A instalação é por usuário, com atalho no menu
Iniciar e desinstalação pelo Windows.

**Já tem o aplicativo? Abra-o para receber a atualização automática.** O
instalador inicial não sobrescreve uma instalação existente. O ZIP da release é
uma alternativa portátil; instalações antigas precisam do instalador para
habilitar o gerenciamento automático.

A atualização do cliente verifica assinatura, hash, validade e sequência antes
da troca. Uma falha mantém a recuperação. O programa não cria serviço ou
inicialização automática próprios; o WebView2 mantém o atualizador da Microsoft.

## Versões e recuperação

Use sempre o link de download acima. Mantemos a versão atual e uma anterior
para recuperação orientada. A anterior não é a recomendação para uma nova
instalação. Versões mais antigas têm seus downloads retirados depois do
arquivamento privado e da validação da substituta.

[Histórico](CHANGELOG.md) · [Política de releases](RELEASE-POLICY.md)

As novas releases são imutáveis: os binários publicados não podem ser
substituídos silenciosamente. Metadados de assinatura, raiz pública, inventário
SPDX e checksums são públicos por projeto; chaves privadas não são distribuídas.

## Ajuda e segurança

[Dúvidas e problemas comuns](https://github.com/jstoreuser/updater-releases/issues)
· [Relatar uma vulnerabilidade em privado](https://github.com/jstoreuser/updater-releases/security/advisories/new)

O diagnóstico é local e nada é enviado automaticamente. Revise-o antes de
compartilhar; não publique saves, Mods, dados pessoais, tokens ou credenciais.

O aplicativo e o instalador ainda não possuem certificado Authenticode. As
assinaturas internas não equivalem à assinatura de código do Windows. Se houver
bloqueio, registre a mensagem para análise sem desativar proteções do sistema.
A homologação ampla em outros ambientes Windows e no jogo segue em andamento.
