# Política de distribuição

- O link `releases/latest/download/Sims4Updater-setup.exe` aponta para a versão
  recomendada. Nenhum usuário precisa escolher um instalador pelo histórico.
- Mantemos duas releases com arquivos: a atual e a anterior para recuperação
  orientada. Uma falha de segurança pode exigir a retirada antecipada de uma
  versão, independentemente dessa janela.
- Antes de retirar uma release, preservamos seus metadados e todos os assets em
  arquivo privado, conferidos por tamanho e SHA-256. O histórico resumido
  permanece no [CHANGELOG](CHANGELOG.md). Tags não são reescritas.
- Não retiramos a versão atual nem a anterior antes de validar a substituta,
  o instalador, a atualização e os downloads públicos.
- Novas releases são preparadas como rascunho e publicadas com imutabilidade.
  Todos os arquivos são enviados e conferidos antes de publicar. Correções de
  binários recebem outra versão; não substituímos assets de uma release pronta.
- Chaves privadas, credenciais, dumps, diagnósticos e arquivos do jogo não fazem
  parte deste repositório. Raiz pública, assinaturas e hashes podem ser públicos.

Retirar um download não apaga cópias já obtidas por terceiros. A atualização
assinada e a recomendação da versão atual continuam necessárias. Este repositório
não é um controle de licença, assinatura comercial ou autorização de conteúdo.
