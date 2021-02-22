# forticlient-mxlinux

1. Español
2. English

## Español

Me costó bastante trabajo encontrar una aplicación que me permita conectarme desde [MXLinux](https://mxlinux.org/ "MXLinux") 19.3_x64 a una VPN de Fortinet.

El cliente VPN publicado en el sitio oficial de [descargas de Forticlient](https://www.forticlient.com/downloads "descargas de Forticlient"), que al 22/02/2021 es el paquete FortiClientFullVPNInstaller_6.4.3.0959_amd64.deb, se instala pero al ejecutarlo solo muestra una ventana en blanco.

Recomiendo dos opciones, ambas provistas por [Rene Hadler](https://hadler.me/ "Rene Hadler"):
- [OpenFortiGui](https://hadler.me/linux/openfortigui/ "OpenFortiGui")
- [Paquetes .deb para FortClient SSLVPN](#paquetes-deb-para-forticlient-sslvpn)

### Paquetes .deb para FortiClient SSLVPN

OpenFortiGui es un software más moderno y recomendado. No obstante, quizá por la configuración particular de la red VPN, no pude llegar a establecer la conexión.

Estos paquetes .deb de FortClient SSLVPN funcionaron correctamente, **a pesar de corresponder a varias versiones anteriores, y actualizados por última vez en 2017**. Deberías usarlo bajo tu propio riesgo.

**El sitio oficial es [https://hadler.me/linux/forticlient-sslvpn-deb-packages/](https://hadler.me/linux/forticlient-sslvpn-deb-packages/  "https://hadler.me/linux/forticlient-sslvpn-deb-packages/") y recomiendo que los descargues desde ahí.**

Yo los guardé en este repositorio, con motivos de archivo personal.

## English

It took me some effort to find a way to connect from a [MXLinux](https://mxlinux.org/ "MXLinux") 19.3_x64 machine to a FortiClient VPN.

The VPN client published in the official [official Forticlient downloads](https://www.forticlient.com/downloads "official Forticlient downloads") page, which on 22/02/2021 is the package , can be installed, but when I execute it I only get a blank window.

I recommend two options, both provided by [Rene Hadler](https://hadler.me/ "Rene Hadler") (@theinvisible):
- [OpenFortiGui](https://hadler.me/linux/openfortigui/ "OpenFortiGui")
- [FortClient SSLVPN .deb packages](#forticlient-sslvpn-deb-packages)

### FortiClient SSLVPN .deb packages
OpenFortiGui is a more modern software, and I recommend it. However, maybe due to a custom config in the server I was trying to reach, the connection dropped.

These .deb packages worked fine for me, **dispite being really outdated: they were last updated in 2017**. You should use at your own risk.

The official site is [https://hadler.me/linux/forticlient-sslvpn-deb-packages/ ](https://hadler.me/linux/forticlient-sslvpn-deb-packages/ http:// "https://hadler.me/linux/forticlient-sslvpn-deb-packages/ "), and I recommend you to download them from there.

I keep them in this repo, for personal archiving porpuse.