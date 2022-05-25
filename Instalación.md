# Instalación

Para **instalar** chocolatey, primero necesitamos introducir el comando **Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))**.
Esto nos configurará la PowerShell para permitir la ejecución de scripts externos, ya que necesitamos este paso antes de instalar el propio chocolatey

![Ins. 1](https://github.com/lmrs-06/Chocolatey/blob/main/foto%20github/foto1.PNG)

Tras este paso, procedemos a introducir el comando **choco install vlc**, el cual descargará e instalará VLC Media Player en el sistema mostrando la información del progreso que se muestra en su consola a medida que se agrega VLC a su sistema. Luego lo encontraremos en el menú Inicio como si ejecutaramos el instalador nosotros mismos.

![Ins. 2](https://github.com/lmrs-06/Chocolatey/blob/main/foto%20github/foto2.PNG)

Finalmente para instalar los paquetes (que podemos buscar en su pagina web) solo hace falta escribir **choco install** seguido del programa que queramos
