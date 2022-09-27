## Configurações que uso no meu Terminal e no editor VIM

As configurações que utilizo no terminal e no VIM tornam o trabalho mais agradável e prático na hora do debug.

## Para o Terminal

**01. Instalação do pacote ZSH junto ao tema ```Powerlevel10k```.**
```bash
sudo apt install zsh -y
```
**02. Instalação das Fontes necessárias para que o tema funcione corretamente.**

- [MesloLGS NF Regular](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Regular.ttf)
- [MesloLGS NF Bold](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold.ttf)
- [MesloLGS NF Italic](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Italic.ttf)
- [MesloLGS NF Bold Italic](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold%20Italic.ttf)

[Fonte original](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k)

O tema [Powerlevel10k](https://github.com/romkatv/powerlevel10k), trás informações no terminal que ajudam a você saber onde você se encontra no momento.
```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

Após clonar o repositório este repositório para local, basta copiar todos os arquivos para $HOME
e reiniciar o zsh.
```bash
exec zsh
```
**03. Configuração do tema ```Powerlevel10k```.**
Execute o seguinte comando para começar a configurar o tema:
```bash
pk10 configure
```

**03. Nas próximas janelas, configure conforme a sua necessidade.**

## Para o Vim

**01. Copie o arquivo ```vimrc``` deste repositório para o diretório $HOME.**


**02. Instale o pacote vim-plug.**

```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

**03. Abra o arquivo ```vimrc``` com o ```vim``` aprte ```ESC``` e em seguida execute o seguinte comando:**
```bash
:PlugInstall
```

Após isso, ele irá realizar a instalação dos Plugins que estão inseridos no arquivo ```vimrc.``
