# 🖥️ MiniPC Ryzen9

## ⚙️ Configurações Iniciais
- Validar Windows
- Windows Update
- Drivers

## 🪟 Configurações Windows
- Deixar o tema escuro (Iniciar → Temas)

## 🌐 Chrome
  - [Google Chrome](https://www.google.com/chrome/)
 
## 📝 Txt
- [Sublime Text](https://www.sublimetext.com/)
  - Configurar a variável de ambiente: `C:\Program Files\Sublime Text`
  - Criar um novo exec com o nome `sublime`

## 📶 WiFi e Bluetooth
- Drivers Intel Wi-Fi 6E AX210
  - Local: `S:\Softwares\MiniPC\S500\drivers\Intel - Wi-Fi 6E AX210`
  - [Download](https://www.intel.com.br/content/www/br/pt/products/sku/204836/intel-wifi-6e-ax210-gig/downloads.html)

## 🛡️ Segurança
- [Kaspersky](https://my.kaspersky.com/)

## 🔴 AMD
- Baixar atualizações de detecção automática para Radeon™ e Ryzen™
  - [Download](https://www.amd.com/en/support)

## 📂 Diretório de Usuários
- Configurar diretório de arquivos do usuário, exemplo D:\Users 
- Erros na alteração
  - [Falha na operação para alterar a localização de uma pasta pessoal no Windows](https://support.microsoft.com/pt-br/topic/falha-de-operação-para-alterar-um-local-de-pasta-pessoal-no-windows-ffb95139-6dbb-821d-27ec-62c9aaccd720)
    - Alterar as chaves HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\User Shell Folders
    - Rodar registro: `S:\Softwares\MiniPC\S500\Diretório de Usuários - D.reg`
  
## 🗜️ Aplicativos
- 🗜️ [WinRAR](https://www.win-rar.com/start.html?&L=9)
- ⌨️ [Logitech MK540](https://support.logi.com/hc/en-za/articles/360024850313--Downloads-MK540-ADVANCED-Wireless-Keyboard-and-Mouse-Combo)
- 📸 [LightShot](https://app.prntscr.com/pt-br/help.html)
- 📺 [VLC Player](https://www.videolan.org)
- ☕ [Java](https://www.oracle.com/java/technologies/downloads/)
- 🌐 Browsers
  - [Brave](https://brave.com/)
  - [Firefox](https://www.mozilla.org/pt-BR/firefox/new/)
- 📄 [Adobe Acrobat Reader](https://www.adobe.com/br/acrobat/pdf-reader.html)
- 🎵 [Spotify](https://www.spotify.com/br-pt/download/windows/)
- Personal Finances


## ⚡ Inicialização Automática de Aplicativos

### Configurar Chrome e Sublime Text para iniciar automaticamente:

#### Chrome
1. Pressione `Win + R`, digite `shell:startup` e pressione Enter
2. Clique com o botão direito > Novo > Atalho
3. Cole o caminho:  
   `"C:\Program Files\Google\Chrome\Application\chrome.exe"`
4. Nomeie como "Google Chrome"

#### Sublime Text
1. Na mesma pasta de inicialização, crie um novo atalho
2. Cole o caminho:  
   `"C:\Program Files\Sublime Text\sublime_text.exe"`
3. Nomeie como "Sublime Text"

### Métodos Gerais:

#### Método 1: Pasta de Inicialização (Recomendado)
1. Pressione `Win + R`, digite `shell:startup` e pressione Enter
2. Crie atalhos dos programas desejados nesta pasta
3. Os programas serão iniciados quando o Windows iniciar

#### Método 2: Gerenciador de Tarefas
1. Pressione `Ctrl + Shift + Esc` para abrir o Gerenciador de Tarefas
2. Vá para a aba "Inicializar"
3. Clique com o botão direito no programa e selecione "Ativar"

> 💡 Dica: Use o método 1 para programas como Chrome e Sublime Text, e o método 2 para programas que precisam de privilégios de administrador.



## 📊 [Office 365 Family](https://account.microsoft.com/services/microsoft365/details?ocid=PROD_Office_CONS_Growth_RET_ClientManageAccount&clid=pt-BR&client=excel.exe&cv=16&p1=1&isredacted=0&refd=account.microsoft.com)
  - Conta: alv.storage@outlook.com

## 🔑 KeePass
- [Download](https://keepass.info/download.html)
- Instalar plugins de `S:\Softwares\Keepass\plugins`
- Configurar pattern de senhas

## 🤖 AutoHotkey
- [Download](https://www.autohotkey.com/)
- Local dos scripts: `S:\Softwares\AutoHotkey`
- Configuração de inicialização automática:
  1. Instalar o AutoHotkey
  2. Criar atalho do script `.ahk` desejado
  3. Pressionar `Win + R`, digitar `shell:startup` e Enter
  4. Mover o atalho para a pasta de inicialização que abrir
  5. Reiniciar o computador para testar

## 🛡️ Segurança
- [Kaspersky](https://my.kaspersky.com/)

## 💾 Backup - SyncBack
- [Download](https://www.2brightsparks.com/freeware/index.html)
- Perfil em: `S:\Softwares\Backup\SyncBack\Perfil\`

## ☁️ Google Drive
- Instalar e configurar

## ⬇️ uTorrent
- [Download](https://www.utorrent.com/intl/pt_br/desktop/)
- Configurar diretórios

## 📚 Kindle
- [Download](https://www.amazon.com.br/b?ie=UTF8&node=17877530011&brr=1&rd=1)

## 🖱️ Logitech Options
- [Download](https://support.logi.com/hc/en-nz/articles/360025141274)
- Drivers em: `S:\Softwares\Teclado e Mouse\Logitech`

## 💽 EaseUS Partition Master
- [Download](https://br.easeus.com/partition-manager/partition-master-free.html)

## 📷 Câmera
- [Logitech C922](https://support.logi.com/hc/pt-br/articles/360024699934--Downloads-C922-Pro-Stream-Webcam)
- [Logitech Capture](https://www.logitech.com/pt-br/software/capture.html)

## 🔊 Áudio
- [Equalizer APO + Peace Equalizer](https://www.softdownload.com.br/equalize-audio-computador-equalizer-apo.html)
- Arquivos em: `S:\Softwares\Audio\Equalizador`

## 🖨️ Impressora
- HP Photosmart c4700 series
  - [HP Smart](https://apps.microsoft.com/store/detail/hp-smart/9WZDNCRFHWLH)
  - Usuário: Vanessa

� Optimização
- [Otimizar Windows](http://www.softdownload.com.br/10-dicas-deixar-windows-10-rapido.html)
- Configurar usuário como administrador
  - [Guia](https://answers.microsoft.com/pt-br/windows/forum/all/colocar-um-usu%C3%A1rio-comum-como-adiministrador/9add7a79-3730-47d4-911c-2320d895850b)

## 💾 Backup de Imagem
- Local: `R:\Backup`
- Ferramentas:
  - EaseUS
  - Macrium Reflect

## 📊 Monitoramento
- [CPU-Z](https://www.cpuid.com/)
- [HWMonitor](https://www.cpuid.com/softwares/hwmonitor.html)
- [GPU-Z](https://www.techpowerup.com/download/techpowerup-gpu-z/)

## ⚙️ Configurações Avançadas
### 🖥️ Barra de Tarefas - Múltiplos Monitores
- Configurar janelas individuais:
  1. Clique com o botão direito na barra de tarefas
  2. Selecione "Configurações da barra de tarefas"
  3. Role até "Comportamentos da barra de tarefas"
  4. Marque "Mostrar meus botões da barra de tarefas em..."
  5. Selecione "Somente na barra de tarefas onde a janela está aberta"

### 🎯 Gadgets
- [Win10 Widgets](https://win10widgets.com/)
- [Rainmeter](https://www.rainmeter.net/)
- [Open Hardware Monitor](https://openhardwaremonitor.org/downloads/)
  - Instalar em: `C:\Program Files\OpenHardwareMonitor`
  - Adicionar à inicialização do Windows:
    - `%AppData%\Microsoft\Windows\Start Menu\Programs\Startup`
    - `C:\Users\alvar\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`

### 🖥️ Monitor
- [AOC i-Menu](https://my.aoc.com/index/explore/route/softwares)

### 💬 WhatsApp Desktop
- [Download](https://www.whatsapp.com/features)

### 🔄 VMware
- Instalar versão de `S:\Softwares\VM Ware\Instalador\VMware workstation 2015 with key`
- Atualizar para a versão 15.5.7

## ⚙️ Serviços
- Desativar serviços desnecessários em `services.msc`
- Desativar todos os serviços de VM não utilizados

## 🖨️ Configurações de Impressão
- Configurar impressão em preto e branco:
  - Impressoras → Configurações → Preferências de Impressão

## 🔊 Configurações de Áudio Bluetooth
- Desativar modo "Hands Free"
  - Painel de Controle\Hardware e Sons\Dispositivos e Impressoras
  - Selecionar dispositivo → Serviços
  - Referências:
    - [Fórum Microsoft](https://answers.microsoft.com/en-us/windows/forum/all/fix-for-bluetooth-headphones-or-speaker-using/7023c43b-c001-42e9-9ec9-95a8f96a4b4c)
    - [Guia de solução](https://visser.io/2013/09/fix-for-poor-a2dp-quality-for-bluetooth-headphones-under-windows-8/)

� Drivers e Softwares Adicionais
- Impressora Epson L3250: `S:\Softwares\Impressoras\Epson\L3250`
- Planos de Energia: `S:\Softwares\Planos de Energia`
- AutoHotkey: `S:\Softwares\AutoHotkey`
  - Script para movimentação de janelas

## ❌ Não Instalados
- AnyDesk (desativar serviço em `services.msc`)
- [IObit Driver Booster](https://www.iobit.com/pt/driver-booster.php)

## 📌 Pendências
### 🎥 Vídeos e Gravações
- Configurar diretório: `R:\Videos - Gravações`
  - Deletar arquivos desnecessários do notebook
  - Ajustar backup do notebook

### 💻 Notebook
- Atualizar backups do SyncBack
- Exportar configurações do MiniPC e importar no notebook
