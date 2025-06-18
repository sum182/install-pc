# 🖥️ MiniPC Ryzen9

---
## ⚙️ Configurações Iniciais
- Ativar Windows
- Windows Update

## 🌍 Chrome
- [Google Chrome](https://www.google.com/chrome/)

## 📝 Arquivos Texto
- [Sublime Text](https://www.sublimetext.com/)
  - Configurar a variável de ambiente: `C:\Program Files\Sublime Text`
  - Criar um novo exec com o nome `sublime`
- Na pasta de inicialização, crie um novo atalho
- Cole o caminho:  
   `"C:\Program Files\Sublime Text\sublime_text.exe"`

## 🪟 Tema
- Deixar o tema escuro (Iniciar → Temas)

## 📂 Diretório de Usuários
- Configurar diretório de arquivos do usuário, exemplo D:\Users
- Erros na alteração
  - [Falha na operação para alterar a localização de uma pasta pessoal no Windows](https://support.microsoft.com/pt-br/topic/falha-de-operação-para-alterar-um-local-de-pasta-pessoal-no-windows-ffb95139-6dbb-821d-27ec-62c9aaccd720)
    - Alterar as chaves HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\User Shell Folders
    - Rodar registro: `S:\Softwares\MiniPC\S500\Diretório de Usuários - D.reg`

---

## 🖥️ Drivers e Segurança

### 📶 WiFi e Bluetooth
- Drivers Intel Wi-Fi 6E AX210
  - Local: `S:\Softwares\MiniPC\S500\drivers\Intel - Wi-Fi 6E AX210`
  - [Download](https://www.intel.com.br/content/www/br/pt/products/sku/204836/intel-wifi-6e-ax210-gig/downloads.html)

### 🛡️ Segurança
- [Kaspersky](https://my.kaspersky.com/)

### 🔴 AMD
- Baixar atualizações de detecção automática para Radeon™ e Ryzen™
  - [Download](https://www.amd.com/en/support)
---

## 🗜️ Aplicativos 
- 🗜️ [WinRAR](https://www.win-rar.com/start.html?&L=9)
- 📸 [LightShot](https://app.prntscr.com/pt-br/help.html)
- 📺 [VLC Player](https://www.videolan.org)
- ☕ [Java](https://www.oracle.com/java/technologies/downloads/)
- 📚 [Kindle](https://www.amazon.com.br/b?ie=UTF8&node=17877530011&brr=1&rd=1)
- 💬 [WhatsApp](https://www.whatsapp.com/features)
- 🌐 Browsers
  - [Brave](https://brave.com/)
  - [Firefox](https://www.mozilla.org/pt-BR/firefox/new/)
- 📄 [Adobe Acrobat Reader](https://www.adobe.com/br/acrobat/pdf-reader.html)
- 🎵 [Spotify](https://www.spotify.com/br-pt/download/windows/)
- 🖱️ [Redragon](https://www.redragon.com.br/downloads)
  - Local: `S:\Softwares\Teclado e Mouse\Redragon`
- Personal Finances


## 📊 Office 365 Family
### Download e Instalação
- [Download](https://www.microsoft.com/microsoft-365/buy/compare-all-microsoft-365-products)
- Faça login com a conta: alv.storage@outlook.com
- Após a compra/ativação, acesse: [Minha Conta](https://account.microsoft.com/services/)

### Ativação
- O Office deve ativar automaticamente após o login
- Se necessário, abra qualquer aplicativo do Office > Conta > Entrar
- Use: alv.storage@outlook.com

## 🔑 KeePass
- [Download](https://keepass.info/download.html)
- Instalar plugins de `S:\Softwares\Keepass\plugins`
- Configurar pattern de senhas
  - Basta abrir o grupo keepass, copiar o pattern e salvar como "Password Generator Pattern"

## 🤖 AutoHotkey
- [Download](https://www.autohotkey.com/)
- Local dos scripts: `S:\Softwares\AutoHotkey`
- Configuração de inicialização automática:
  1. Instalar o AutoHotkey
  2. Criar atalho do script `.ahk` desejado
  3. Pressionar `Win + R`, digitar `shell:startup` e Enter
  4. Mover o atalho para a pasta de inicialização que abrir
  5. Reiniciar o computador para testar


## 💾 Backup - SyncBack
- [Download](https://www.2brightsparks.com/freeware/index.html)
- Perfil em: `S:\Softwares\Backup\SyncBack\Perfil\`

## ☁️ Google Drive
- [Download](https://www.google.com/drive/download/)
- Configurar sincronização de pastas


---
## 📦 Aplicativos Opcionais
- 💽 [EaseUS Partition Master](https://br.easeus.com/partition-manager/partition-master-free.html)
- 🖥️ [AOC i-Menu](https://my.aoc.com/index/explore/route/softwares)
- 🔄 VMware Workstation
  - Instalar versão de `S:\Softwares\VM Ware\Instalador\VMware workstation 2015 with key`
  - Atualizar para a versão 15.5.7
- 🖥️ [AnyDesk](https://anydesk.com/pt/downloads/windows)
  - Após instalação, desativar serviço em `services.msc`
- 💾 Backup com Imagem
  - Local: `R:\Backup`
  - Ferramentas:
    - EaseUS
    - Macrium Reflect
- 📊 Monitoramento
  - [CPU-Z](https://www.cpuid.com/)
  - [HWMonitor](https://www.cpuid.com/softwares/hwmonitor.html)
  - [GPU-Z](https://www.techpowerup.com/download/techpowerup-gpu-z/)
- ### 💾 Ferramentas de Backup
  - Local dos backups: `R:\Backup`
  - [EaseUS Todo Backup](https://www.easeus.com/backup-software/tb-free.html)
  - [Macrium Reflect Free](https://www.macrium.com/reflectfree)
- ### 📊 Monitoramento de Hardware
  - [CPU-Z](https://www.cpuid.com/)
  - [HWMonitor](https://www.cpuid.com/softwares/hwmonitor.html)
  - [GPU-Z](https://www.techpowerup.com/download/techpowerup-gpu-z/)

---
## ⚡ Inicialização Automática de Aplicativos
#### Método 1: Pasta de Inicialização (Recomendado)
1. Pressione `Win + R`, digite `shell:startup` e pressione Enter
2. Crie atalhos dos programas desejados nesta pasta
3. Os programas serão iniciados quando o Windows iniciar

#### Método 2: Gerenciador de Tarefas
1. Pressione `Ctrl + Shift + Esc` para abrir o Gerenciador de Tarefas
2. Vá para a aba "Inicializar"
3. Clique com o botão direito no programa e selecione "Ativar"

> 💡 Dica: Use o método 2 para programas que precisam de privilégios de administrador.
---
## 🖱️ Logitech

### 🛠️ Softwares de Gerenciamento
### 🖱️ Logitech Options+
   - Suporta a maioria dos teclados e mouses atuais
   - Interface moderna e intuitiva
   - [Download](https://www.logitech.com/software/options-plus.html)


### ⌨️ Teclado e Mouse(Caso precisar de algum ajuste)
- [Logitech MK540](https://support.logi.com/hc/en-za/articles/360024850313--Downloads-MK540-ADVANCED-Wireless-Keyboard-and-Mouse-Combo)
  - Guia de instalação e configuração
  - Configuração de teclas especiais
  - Gerenciamento de perfis

### 📹 Câmera
- [Logitech C922](https://support.logi.com/hc/pt-br/articles/360024699934--Downloads-C922-Pro-Stream-Webcam)
- [Logitech Capture](https://www.logitech.com/pt-br/software/capture.html)
  - Configuração de iluminação e enquadramento
  - Perfis de streaming

---
## 🔊 Áudio

### 🎛️ Equalizador
- [Equalizer APO + Peace Equalizer](https://www.softdownload.com.br/equalize-audio-computador-equalizer-apo.html)
  - Arquivos de configuração: `S:\Softwares\Audio\Equalizador`
  - [Guia de instalação](https://sourceforge.net/projects/equalizerapo/)

### 🎧 Configurações Bluetooth
- Desativar modo "Hands Free" para melhor qualidade de áudio:
  1. Painel de Controle > Hardware e Sons > Dispositivos e Impressoras
  2. Clique com o botão direito no dispositivo de áudio
  3. Selecione "Serviços"
  4. Desmarque "Áudio Hands Free"
- Referências:
  - [Fórum Microsoft - Fix for Bluetooth Headphones](https://answers.microsoft.com/en-us/windows/forum/all/fix-for-bluetooth-headphones-or-speaker-using/7023c43b-c001-42e9-9ec9-95a8f96a4b4c)
  - [Guia para melhorar qualidade de áudio Bluetooth](https://visser.io/2013/09/fix-for-poor-a2dp-quality-for-bluetooth-headphones-under-windows-8/)

### 🎙️ Dispositivos de Áudio
- Configurações de microfone em:
  - Painel de Controle > Som > Gravação
  - Configurar níveis e melhorias

### 🔉 Solução de Problemas
- Verificar drivers de áudio no Gerenciador de Dispositivos
- Reiniciar Serviço de Áudio do Windows
  - `services.msc` > Windows Audio > Reiniciar
- [Atualizar drivers de áudio](https://www.realtek.com/en/component/zoo/category/pc-audio-codecs-high-definition-audio-codecs-software)
---
## 🖨️ Impressora Epson L3250
- **Windows 11**  
  [Download](https://epson.com.br/Suporte/Impressoras/Impressoras-multifuncionais/Epson-L/Epson-L3250/s/SPT_C11CJ67301?review-filter=Windows+11)
- **Windows 10**  
  [Download](https://epson.com.br/Suporte/Impressoras/Impressoras-multifuncionais/Epson-L/Epson-L3250/s/SPT_C11CJ67301?review-filter=Windows+10+64-bit)
- Procedimentos de instalação 
  - `S:\Softwares\Impressoras\Epson\L3250`

#### Outros Downloads
- [Epson Smart Panel](https://epson.com.br/Suporte/Impressoras/Impressoras-Multifuncionais/Epson-L3250/s/SPT_C11CJ26401#drivers)
- [Todos os Drivers e Softwares](https://epson.com.br/Suporte/Impressoras/Impressoras-Multifuncionais/Epson-L3250/s/SPT_C11CJ26401)

### 🔧 Solução de Problemas
- Limpeza de bicos: Painel da impressora > Manutenção > Limpeza de bicos
- Alinhamento de cabeçote: Painel da impressora > Manutenção > Alinhamento de cabeçote
- [Guia de Solução de Problemas](https://epson.com.br/Suporte/Impressoras/Impressoras-Multifuncionais/Epson-L3250/s/SPT_C11CJ26401#faq)


---


## ⚙️ Configurações
### 🖥️ Barra de Tarefas - Múltiplos Monitores
- Configurar janelas individuais:
  1. Clique com o botão direito na barra de tarefas
  2. Selecione "Configurações da barra de tarefas"
  3. Role até "Comportamentos da barra de tarefas"
  4. Marque "Mostrar meus botões da barra de tarefas em..."
  5. Selecione "Somente na barra de tarefas onde a janela está aberta"


### ⚡ Planos de Energia
- Local dos perfis: `S:\Softwares\Planos de Energia`
- Como importar:
  1. Abra o Painel de Controle > Hardware e Sons > Opções de Energia
  2. Clique em "Mostrar planos adicionais"
  3. Selecione o plano desejado ou importe um perfil personalizado


### 🎯 Gadgets
- [Win10 Widgets](https://win10widgets.com/)
- [Rainmeter](https://www.rainmeter.net/)
- [Open Hardware Monitor](https://openhardwaremonitor.org/downloads/)
  - Instalar em: `C:\Program Files\OpenHardwareMonitor`
  - Adicionar à inicialização do Windows
  
---

## 📌 Pendências
### 💻 Notebook Pendências
- Atualizar backups do SyncBack
- Exportar configurações do MiniPC e importar no notebook
- Deletar arquivos desnecessários do notebook


---
