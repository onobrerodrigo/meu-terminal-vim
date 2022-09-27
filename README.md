## Configurações que uso no meu Terminal e no editor VIM

As configurações que utilizo no terminal e no VIM tornam o trabalho mais agradável e prático na hora do debug.

## Para o Terminal

**01. Instalação do pacote ZSH junto ao tema ```Powerlevel10k```.**
```bash
sudo apt install zsh -y
```
O tema [Powerlevel10k](https://github.com/romkatv/powerlevel10k), trás informações no terminal que ajudam a você saber onde você se encontra no momento.
```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
Após clonar o repositório acima para o local, basta copiar os arquivos que estão no diretório [files](/files) deste reposítório

