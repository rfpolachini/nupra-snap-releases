# Nupra Snap

Captura de tela com marcações para Windows 10 e 11 (64 bits), da Nupra Studio.

## Instalar

1. Baixe o `NupraSnap-Setup.exe` da [versão mais recente](https://github.com/rfpolachini/nupra-snap-releases/releases/latest).
2. Abra o arquivo. Se aparecer "O Windows protegeu o computador", clique em **Mais informações** e depois em **Executar assim mesmo**. O app ainda não tem assinatura digital.
3. Clique em **Instalar**. Ele instala só na sua conta, sem pedir administrador, e já inicia com o Windows.

Depois de instalado, o Nupra Snap avisa sozinho quando sair uma versão nova: use **Atualizar** no menu do ícone perto do relógio. Para remover, use *Configurações › Aplicativos › Nupra Snap › Desinstalar*.

## Conferir o arquivo

Cada versão traz um `SHA256SUMS.txt`. No PowerShell, na pasta do download:

```powershell
Get-FileHash .\NupraSnap-Setup.exe
```

O código deve ser igual ao do arquivo publicado.

Este repositório guarda só os instaladores. Fontes embutidas: Manrope, licença SIL Open Font License 1.1.
