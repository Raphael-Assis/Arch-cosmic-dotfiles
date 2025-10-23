# 🚀 Raphael-Assis/Arch-cosmic-dotfiles 🚀

![Screenshot do Setup COSMIC Arch](screenshots/cosmic-arch-rice.png) 

## Setup de Dotfiles Pioneiro: COSMIC DE no Arch Linux

Este repositório contém as configurações (dotfiles) para o ambiente de desktop **COSMIC** (em desenvolvimento pela System76) rodando de forma estável no **Arch Linux**.

Esta combinação é rara e exige um setup manual de componentes cruciais.

## Por que este Setup é Valioso?

* **Pioneirismo Arch + COSMIC:** É um dos primeiros setups organizados de dotfiles para o COSMIC DE rodando de forma estável no Arch.
* **Design de Painel Otimizado:** O layout do painel superior é puramente funcional e minimalista, utilizando um design de dock centralizado (apenas Data/Hora) e mantendo as áreas de trabalho e lançadores no canto esquerdo para um fluxo de trabalho limpo.
* **Segmentação Lógica:** O painel é dividido em três segmentos (Inicial, Central, Final) para máxima organização, facilitando o acesso rápido a áreas de trabalho, lançadores e a bandeja de sistema (Som, Bluetooth, Notificações).
* **Gerenciamento de Energia Corrigido:** Inclui o pacote `system76-power` e o arquivo de serviço necessário (resolvendo o erro de "Gestor de energia não encontrado" e o problema de dreno rápido de bateria em laptops).

## O que está incluído?

* `pacman-pkgs.txt`: Lista de pacotes dos repositórios oficiais.
* `aur-pkgs.txt`: Lista de pacotes instalados via AUR (incluindo `yay` e `system76-power`).
* `com.system76.PowerDaemon.service`: Arquivo essencial para a ativação do serviço de energia.

## 🛠️ Como Instalar e Restaurar o Setup (Guia Rápido)

Este guia assume que você está em uma instalação nova do Arch Linux.

### 1. Clonar o Repositório

Primeiro, clone este repositório para sua pasta pessoal:

```bash
git clone [https://github.com/Raphael-Assis/Arch-cosmic-dotfiles.git](https://github.com/Raphael-Assis/Arch-cosmic-dotfiles.git)
cd Arch-cosmic-dotfiles
