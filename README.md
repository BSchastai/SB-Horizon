# S&B Horizon

Launcher e gerenciador de mods para **Stardew Valley**, em português.

Instala o SMAPI, instala e atualiza mods, confere as dependências antes de jogar, faz backup dos
saves e ajuda a traduzir os mods para português.

> Versão beta. Pode ter bugs: faça backup dos seus saves (o próprio Horizon faz um antes de mexer
> nos mods) e avise se algo der errado na aba Issues.

## Download

Baixe na página de [Releases](../../releases/latest).

| Sistema | Arquivo |
|---|---|
| **Windows 10 e 11** (recomendado) | `SB.Horizon_x.y.z_x64-setup.exe` |
| Windows sem instalar | `SB-Horizon-x.y.z-portable-x64.zip` |
| **Linux**, qualquer distro | `SB.Horizon_x.y.z_amd64.AppImage` |
| Ubuntu, Mint, Debian, Pop!_OS | `SB.Horizon_x.y.z_amd64.deb` |
| Fedora, openSUSE | `SB.Horizon-x.y.z-1.x86_64.rpm` |
| Arch, Manjaro, EndeavourOS | `PKGBUILD` (pacote `sb-horizon-bin`) ou o AppImage |

Os arquivos `.sig`, `latest.json` e `SB-Horizon-x.y.z-portable.exe` são usados pela atualização
automática. Não precisa baixar.

### Linux

- **AppImage:** baixe, dê permissão de execução (`chmod +x SB.Horizon_*.AppImage` ou pelas
  propriedades do arquivo) e abra. Ele se atualiza sozinho.
- **.deb / .rpm:** instale com o gerenciador da sua distro. Também se atualiza pelo aviso.
- **Arch:** baixe o `PKGBUILD` da release numa pasta vazia e rode `makepkg -si`. Nesse caso quem
  atualiza é o pacman (o Horizon só avisa).
- Para guardar as chaves do Nexus e da IA, o Horizon usa o cofre de senhas do sistema (GNOME
  Keyring ou KWallet), que já vem na maioria das distros.

### O Windows mostrou "O Windows protegeu o computador"

É normal em programas novos sem assinatura digital paga. Clique em **Mais informações** e depois
em **Executar assim mesmo**. O aviso aparece só na primeira vez.

## O que ele faz

**Jogo e SMAPI**
- Acha o jogo da Steam ou do GOG sozinho (ou você escolhe a pasta).
- Instala e atualiza o SMAPI em um clique e abre o jogo pelo SMAPI.
- Antes de jogar, confere se falta alguma dependência ou se algum mod está desatualizado.
- Se o jogo fechar com erro, mostra o que mudou desde a última vez que funcionou e oferece
  desativar os mods novos.

**Mods**
- Ativar e desativar com aviso de dependências.
- Instalar arrastando .zip, .7z ou .rar, inclusive:
  - traduções avulsas (só o arquivo de tradução), que vão para o mod certo;
  - variações que substituem arquivos de outro mod (retratos e roupas alternativos);
  - pacotes de retratos do Portraiture.
- Avisos de atualização e de incompatibilidade, "Atualizar todos" com o changelog de cada mod e
  a opção de segurar a versão de um mod.
- Configuração dos mods em formulário, com os nomes em português e miniaturas das opções de
  textura.
- Detector de conflitos entre pacotes do Content Patcher.
- Perfis de mods por fazenda e modpacks para compartilhar.

**Explorar (Nexus Mods)**
- Busca de mods e coleções com os mesmos filtros do site, descrição, imagens, dependências,
  traduções, changelog e mods que usam cada um.
- Instalar direto no app. Com Nexus Premium o download é automático; com conta gratuita o botão
  "Mod Manager Download" do site manda o mod para o Horizon.

**Tradução**
- Traduz os textos dos mods com Google Tradutor (grátis), DeepL, IA (com a sua chave) ou pelo chat
  de uma IA, sem gastar cota de API.
- Português padrão, sem censura, mantendo os códigos do jogo.
- Editor de tradução e traduções que sobrevivem às atualizações dos mods.

**Saves e espaço**
- Backup automático dos saves, com linha do tempo e voltar um save.
- Limpeza de espaço: mostra o que ocupa e o que dá para apagar com segurança.

**Visual**
- Temas das estações (Primavera, Verão, Outono, Inverno), Noite e Claro, ou automático pela
  estação da sua fazenda.

## Conta do Nexus

Para buscar e baixar pelo Explorar, cole a sua chave pessoal da API do Nexus em Configurações
(o link para pegar a chave está lá). A chave fica guardada só no seu computador, no cofre de senhas
do sistema.

## Atualizações do Horizon

Quando sai uma versão nova, aparece um aviso com **Atualizar**, **Agora não** e **Pular esta
versão**. Nunca é obrigatório. Em Configurações dá para ligar a instalação automática ou desligar
o aviso.

## Perguntas

**Preciso do SMAPI instalado antes?**
Não. O Horizon instala.

**Meus mods e saves ficam onde?**
No lugar de sempre: os mods na pasta `Mods` do jogo e os saves na pasta de saves do Stardew. O
Horizon só organiza.

**Funciona no Linux ou no Mac?**
No Linux sim (Steam nativo, Flatpak da Steam ou GOG). No Mac ainda não.


---

S&B Horizon é gratuito. Não é afiliado à ConcernedApe, ao SMAPI nem ao Nexus Mods.
Stardew Valley é marca da ConcernedApe LLC.
