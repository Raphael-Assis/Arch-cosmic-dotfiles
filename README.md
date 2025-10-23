# 🚀 Raphael-Assis/Arch-cosmic-dotfiles 🚀

## Setup de Dotfiles Pioneiro: COSMIC DE no Arch Linux

Este repositório contém as configurações (dotfiles) para o ambiente de desktop **COSMIC** (em desenvolvimento pela System76) rodando de forma estável no **Arch Linux**.

Esta combinação é rara e exige um setup manual de componentes cruciais.

## Por que este Setup é Valioso?

* **Pioneirismo:** Um dos primeiros setups organizados e funcionais de dotfiles para o COSMIC DE no Arch.
* **Gerenciamento de Energia Corrigido:** Inclui a solução para o problema de dreno rápido de bateria em laptops (como o Ideapad), que exige o pacote `system76-power` do AUR e a ativação manual do serviço.
* **Base de Restauração:** Permite que outros usuários (ou você mesmo em uma futura instalação) restaurem rapidamente o ambiente.

## O que está incluído?

* `pacman-pkgs.txt`: Lista de pacotes dos repositórios oficiais.
* `aur-pkgs.txt`: Lista de pacotes instalados via AUR (incluindo `yay` e `system76-power`).
* `com.system76.PowerDaemon.service`: Arquivo essencial para a ativação do serviço de energia.
