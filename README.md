# Gestão de Lotações (SUPORTE) — Script Tampermonkey para o eProc

Script para Tampermonkey que reúne, em um só lugar, diversas ferramentas para facilitar a administração de lotações de usuários no sistema eProc. Desenvolvido para tornar as tarefas de busca, inclusão e exclusão de lotações mais rápidas, intuitivas e eficientes.

---

## Pré-requisitos

### 1. Instalar o Tampermonkey

Abra a loja de extensões do seu navegador (Chrome, Edge ou Firefox), procure por **Tampermonkey** e instale a extensão. Após instalar, confirme que o ícone do Tampermonkey apareceu próximo à barra de endereço.

### 2. Ativar o modo desenvolvedor no navegador

Isso é necessário para o Tampermonkey rodar o script sem bloqueio.

- Vá em **Configurações → Extensões**
- No canto superior direito, ative **Modo do desenvolvedor**

### 3. Configurações do Tampermonkey

- Clique no ícone do Tampermonkey → **Painel** → **Configurações**
- Confirme que estas opções estão ativas:
  - Permitir scripts de usuário
  - Permitir acesso a abas
  - Permitir requisições remotas
  - Modo estrito desativado *(se existir no seu navegador)*

---

## Instalação do script

1. Instale a extensão Tampermonkey no seu navegador *(veja os pré-requisitos acima)*
2. Clique no link abaixo para instalar o script:

👉 [Instalar script](https://raw.githubusercontent.com/rsalvessap/Gestao-de-Lotacoes-EPROC/main/eproc-busca-lotacao.user.js)

3. O Tampermonkey abrirá uma tela de confirmação → clique em **Instalar**

---

## Funcionalidades

### 🔍 Busca de lotações *(todas as páginas)*

- Campo de busca por nome da lotação disponível diretamente na barra superior do sistema
- Não é necessário saber o código da lotação
- Busca inteligente por múltiplas palavras, ignorando acentos e maiúsculas/minúsculas
- Histórico de navegação entre lotações com botões de voltar e avançar
- Botão de atalho para alternar rapidamente para a lotação **Administrador do Sistema**

### ➕ Inclusão de lotações em lote *(tela de usuário)*

- Seleção prévia do tipo de perfil antes da inclusão
- Lista completa de lotações disponíveis com campo de filtro
- Seleção múltipla com opção de marcar ou desmarcar tudo
- Contador em tempo real das lotações selecionadas

### ➖ Exclusão de lotações em lote *(tela de usuário)*

- Lista das lotações vinculadas ao usuário, com indicação do perfil
- Filtro por nome da lotação e por tipo de perfil
- Barra de progresso durante a exclusão, mostrando qual lotação está sendo removida
- Histórico das lotações já excluídas durante a sessão

---

## Requisitos

- Navegador Chrome, Firefox ou Edge
- Extensão Tampermonkey instalada
- Acesso ao sistema eProc (`*.jus.br`)
