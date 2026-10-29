# Guia de Configuração - Servidor Bauhaus (NeoForge 1.21.1)

Bem-vindo! Este guia vai mostrar-lhe passo a passo como configurar o seu TLauncher, instalar o modpack e conectar-se ao nosso servidor.

## Passo 1: Criar a Instância no TLMods

Para garantir que não há conflito com outros mods que já tenha, vamos criar uma instalação limpa usando o gerenciador do TLauncher.

1. Abra o **TLauncher**.
2. No canto inferior direito, clique no botão **TL Mods** (ícone de uma pasta com engrenagem).
3. No menu superior da nova janela, clique em **Criar** (Create).
4. Preencha os campos da seguinte forma:
   * **Nome:** `BAUHAUS` *(Pode escolher outro nome se preferir, mas usaremos este no tutorial).*
   * **Versão do Jogo:** `1.21.1`
   * **Sistema de Mods:** Selecione `NeoForge`
   * **Versão do NeoForge:** `21.1.262`

<img width="1027" height="691" alt="image" src="https://github.com/user-attachments/assets/91a385a6-cdac-40be-b7a0-61dc68e5a65a" />

5. Clique no botão **Criar** na parte inferior. 
6. Feche a janela do TLMods para voltar à tela principal do TLauncher. Certifique-se de que a versão selecionada na lista suspensa seja a `BAUHAUS` (ou o nome que você escolheu).

## Passo 2: Baixar os Mods

Disponibilizamos todos os mods necessários compactados num único arquivo.

1. Acesse a aba **Releases** do nosso repositório no GitHub.
2. Baixe o arquivo `.zip` correspondente à versão mais recente.

## Passo 3: Instalar os Mods no TLauncher

Agora vamos colocar os mods na pasta correta que o TLMods acabou de criar.

1. Na tela principal do TLauncher, clique no **ícone da Pasta** (no canto inferior direito) para abrir o diretório do jogo (`.minecraft`).
2. Acesse a pasta `versions`.
3. Procure e abra a pasta com o nome da instância que você criou (ex: `pathfinder`).
4. Dentro dela, abra a pasta `mods`. 
   * *Atenção: Se houver algum arquivo dentro desta pasta, apague-o para evitar conflitos, caso ela não exista, crie a pasta.*
5. Extraia **todo o conteúdo** do arquivo `.zip` que baixou no Passo 2 diretamente para dentro desta pasta `mods`. (Os arquivos terminados em `.jar` devem ficar soltos aqui dentro).

<img width="756" height="927" alt="image" src="https://github.com/user-attachments/assets/73b11fdc-c95f-406d-8bfb-0a899ef4f036" />

## Passo 4: Conectar ao Servidor

Tudo pronto! Agora devemos configurar a conexão com o servidor através do Tailscale

Acesse: https://tailscale.com/download

Abra a aplicação e crie sua conta ou faça login. Após isso entre na rede do servidor através do convite abaixo:
https://login.tailscale.com/uinv/i3b6521bCT116ZQa33uQm11


1. Volte ao TLauncher e clique em **Entrar no Jogo**.
2. Aguarde o jogo carregar (o primeiro carregamento pode demorar um pouco devido aos mods).
3. No menu principal, clique em **Multijogador** (Multiplayer).
4. Clique em **Adicionar Servidor** (Add Server).
5. Preencha as informações:
   * **Nome do Servidor:** bauhaus (ou o que preferir)
   * **Endereço do Servidor:** `bauhaus`
6. Clique em **Concluído**, selecione o servidor na lista e clique em **Entrar no Servidor**.


Para fazer o acesso através do SKLauncher siga o processo abaixo:

Clique em adicionar nova instância:
<img width="582" height="768" alt="Captura de Tela 2026-10-28 às 21 31 38" src="https://github.com/user-attachments/assets/5018cf0a-35a1-43f3-ae52-2e747ff7be44" />

Mantenha a configuração exatamente como está abaixo:
<img width="1366" height="768" alt="Captura de Tela 2026-10-28 às 21 32 16" src="https://github.com/user-attachments/assets/f61b25f5-1bfb-451d-915f-91dd294a1e5c" />

Abra a pasta da instância e cole a pasta `mods` no local:
<img width="1366" height="768" alt="Captura de Tela 2026-10-28 às 21 34 09" src="https://github.com/user-attachments/assets/86e6d8f2-ffd3-4405-b3f8-b7744053c3a0" />


Siga o mesmo processo que estava acima para acessar o servidor através da rede do Tailscale.
