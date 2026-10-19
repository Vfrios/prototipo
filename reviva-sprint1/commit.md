# Arquivos para commit por responsável — Sprint 1

Este documento divide os arquivos da cópia `reviva-sprint1` conforme as frentes definidas no [README.md](./README.md). Cada pessoa deve incluir no seu commit somente os arquivos da própria frente que foram alterados.

Os caminhos abaixo são relativos à raiz `reviva-sprint1/`. Não incluir `.env`, `atlas-credentials.env`, `node_modules/`, `dist/` ou `target/` nos commits.

## Brayan — Descoberta e detalhes

### Frontend

- `reviva-frontend/src/conjuntos/Brayan-descoberta-detalhes/discoveryScreens.jsx`
- `reviva-frontend/src/conjuntos/Brayan-descoberta-detalhes/itensDetalhes.jsx`

### Backend — consulta de CEP

- `reviva-api/src/main/api/conjuntos/Brayan-descoberta-detalhes/busca-descoberta/EnderecoResponse.java`
- `reviva-api/src/main/api/conjuntos/Brayan-descoberta-detalhes/busca-descoberta/GeoController.java`
- `reviva-api/src/main/api/conjuntos/Brayan-descoberta-detalhes/busca-descoberta/GeoService.java`

## Gustavo — Publicação e gestão inicial

### Frontend

- `reviva-frontend/src/conjuntos/Gustavo-publicacao-gestao/cadastroItem.jsx`
- `reviva-frontend/src/conjuntos/Gustavo-publicacao-gestao/gerenciarItens.jsx`

### Backend

- `reviva-api/src/main/api/conjuntos/Gustavo-publicacao-gestao/cadastro-item/ItemController.java`
- `reviva-api/src/main/api/conjuntos/Gustavo-publicacao-gestao/cadastro-item/ItemRequest.java`
- `reviva-api/src/main/api/conjuntos/Gustavo-publicacao-gestao/cadastro-item/ItemService.java`
- `reviva-api/src/main/api/conjuntos/Gustavo-publicacao-gestao/comum/Item.java`
- `reviva-api/src/main/api/conjuntos/Gustavo-publicacao-gestao/comum/ItemRepository.java`
- `reviva-api/src/main/api/conjuntos/Gustavo-publicacao-gestao/comum/ItemResponse.java`

## João — Comunidades e favoritos

### Frontend

- `reviva-frontend/src/conjuntos/João-comunidades-favoritos/communityScreens.jsx`
- `reviva-frontend/src/conjuntos/João-comunidades-favoritos/favoritos.jsx`

### Backend

- `reviva-api/src/main/api/conjuntos/João-comunidades-favoritos/comunidades/Comunidade.java`
- `reviva-api/src/main/api/conjuntos/João-comunidades-favoritos/comunidades/ComunidadeController.java`
- `reviva-api/src/main/api/conjuntos/João-comunidades-favoritos/comunidades/ComunidadeRepository.java`
- `reviva-api/src/main/api/conjuntos/João-comunidades-favoritos/comunidades/ComunidadeResponse.java`
- `reviva-api/src/main/api/conjuntos/João-comunidades-favoritos/favoritos/Favorito.java`
- `reviva-api/src/main/api/conjuntos/João-comunidades-favoritos/favoritos/FavoritoController.java`
- `reviva-api/src/main/api/conjuntos/João-comunidades-favoritos/favoritos/FavoritoRepository.java`

## Tang — Endereços e segurança básica

### Frontend

- `reviva-frontend/src/conjuntos/Tang-endereco-seguranca/enderecos.jsx`
- `reviva-frontend/src/conjuntos/Tang-endereco-seguranca/seguranca.jsx`

### Backend

- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/endereco-salvo/Endereco.java`
- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/endereco-salvo/EnderecoController.java`
- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/endereco-salvo/EnderecoRepository.java`
- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/endereco-salvo/EnderecoRequest.java`
- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/endereco-salvo/EnderecoService.java`
- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/seguranca-termos/Notificacao.java`
- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/seguranca-termos/NotificacaoController.java`
- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/seguranca-termos/NotificacaoRepository.java`
- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/seguranca-termos/NotificacaoResponse.java`
- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/seguranca-termos/NotificacaoService.java`
- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/seguranca-termos/PreferenciasNotificacao.java`
- `reviva-api/src/main/api/conjuntos/Tang-endereco-seguranca/seguranca-termos/SegurancaController.java`

## Thiago — Perfil e reputação inicial

### Frontend

- `reviva-frontend/src/conjuntos/Thiago-perfil-reputacao/accountScreens.jsx`

### Backend

- `reviva-api/src/main/api/conjuntos/Thiago-perfil-reputacao/perfil/PerfilPublicoResponse.java`
- `reviva-api/src/main/api/conjuntos/Thiago-perfil-reputacao/perfil/PerfilRequest.java`
- `reviva-api/src/main/api/conjuntos/Thiago-perfil-reputacao/perfil/Usuario.java`
- `reviva-api/src/main/api/conjuntos/Thiago-perfil-reputacao/perfil/UsuarioController.java`
- `reviva-api/src/main/api/conjuntos/Thiago-perfil-reputacao/perfil/UsuarioRepository.java`
- `reviva-api/src/main/api/conjuntos/Thiago-perfil-reputacao/perfil/UsuarioResponse.java`
- `reviva-api/src/main/api/conjuntos/Thiago-perfil-reputacao/reputacao/Avaliacao.java`
- `reviva-api/src/main/api/conjuntos/Thiago-perfil-reputacao/reputacao/AvaliacaoRepository.java`
- `reviva-api/src/main/api/conjuntos/Thiago-perfil-reputacao/reputacao/AvaliacaoResponse.java`
- `reviva-api/src/main/api/conjuntos/Thiago-perfil-reputacao/reputacao/AvaliacaoService.java`
- `reviva-api/src/main/api/conjuntos/Thiago-perfil-reputacao/reputacao/PontuacaoService.java`

## Vitor — Solicitação e conversa

### Frontend

- `reviva-frontend/src/conjuntos/Vitor-solicitacao-chat/solicitacao.jsx`
- `reviva-frontend/src/conjuntos/Vitor-solicitacao-chat/tradeScreens.jsx`

### Backend

- `reviva-api/src/main/api/conjuntos/Vitor-solicitacao-chat/chat-negociacao/Mensagem.java`
- `reviva-api/src/main/api/conjuntos/Vitor-solicitacao-chat/chat-negociacao/MensagemController.java`
- `reviva-api/src/main/api/conjuntos/Vitor-solicitacao-chat/chat-negociacao/MensagemRepository.java`
- `reviva-api/src/main/api/conjuntos/Vitor-solicitacao-chat/chat-negociacao/MensagemRequest.java`
- `reviva-api/src/main/api/conjuntos/Vitor-solicitacao-chat/chat-negociacao/MensagemResponse.java`
- `reviva-api/src/main/api/conjuntos/Vitor-solicitacao-chat/solicitacao/Solicitacao.java`
- `reviva-api/src/main/api/conjuntos/Vitor-solicitacao-chat/solicitacao/SolicitacaoController.java`
- `reviva-api/src/main/api/conjuntos/Vitor-solicitacao-chat/solicitacao/SolicitacaoRepository.java`
- `reviva-api/src/main/api/conjuntos/Vitor-solicitacao-chat/solicitacao/SolicitacaoRequest.java`
- `reviva-api/src/main/api/conjuntos/Vitor-solicitacao-chat/solicitacao/SolicitacaoResponse.java`
- `reviva-api/src/main/api/conjuntos/Vitor-solicitacao-chat/solicitacao/SolicitacaoService.java`

## Arquivos compartilhados

Os arquivos abaixo dão suporte a mais de uma frente. O responsável pelo commit deve ser quem fez a alteração; combinar a inclusão quando mais de uma pessoa os modificar.

### Frontend compartilhado

- `reviva-frontend/src/App.jsx`
- `reviva-frontend/src/api.js`
- `reviva-frontend/src/auth/authScreens.jsx`
- `reviva-frontend/src/index.css`
- `reviva-frontend/src/main.jsx`
- `reviva-frontend/src/shared/shared.jsx`

### Backend compartilhado

- `reviva-api/src/main/api/RevivaApiApplication.java`
- `reviva-api/src/main/api/auth/AuthController.java`
- `reviva-api/src/main/api/auth/LoginRequest.java`
- `reviva-api/src/main/api/auth/RecuperarSenhaRequest.java`
- `reviva-api/src/main/api/auth/RegistroRequest.java`
- `reviva-api/src/main/api/auth/TokenResponse.java`
- `reviva-api/src/main/api/shared/config/CachingDbRefResolver.java`
- `reviva-api/src/main/api/shared/config/CarregadorEmLote.java`
- `reviva-api/src/main/api/shared/config/DbRefCache.java`
- `reviva-api/src/main/api/shared/config/DevDataSeeder.java`
- `reviva-api/src/main/api/shared/config/MongoConfig.java`
- `reviva-api/src/main/api/shared/config/MongoDbRefCacheConfig.java`
- `reviva-api/src/main/api/shared/config/RestClientConfig.java`
- `reviva-api/src/main/api/shared/config/SecurityConfig.java`
- `reviva-api/src/main/api/shared/exception/GlobalExceptionHandler.java`
- `reviva-api/src/main/api/shared/operational/Bloqueio.java`
- `reviva-api/src/main/api/shared/operational/BloqueioRepository.java`
- `reviva-api/src/main/api/shared/operational/BloqueioService.java`
- `reviva-api/src/main/api/shared/operational/HealthController.java`
- `reviva-api/src/main/api/shared/security/JwtAuthFilter.java`
- `reviva-api/src/main/api/shared/security/JwtService.java`

### Configuração da cópia

Alterações nestes arquivos afetam o projeto inteiro e devem ser combinadas com a equipe:

- `.gitignore`
- `package.json`
- `pnpm-lock.yaml`
- `pnpm-workspace.yaml`
- `start-backend.cjs`
- `reviva-frontend/package.json`
- `reviva-api/pom.xml`
- `reviva-api/src/main/resources/application.yml`

O README e este arquivo são documentação geral da Sprint 1; incluí-los no commit de quem fizer a alteração documental, sem duplicar o mesmo arquivo em commits concorrentes:

- `README.md`
- `commit.md`
