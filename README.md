<p align="center">
  <img src="https://raw.githubusercontent.com/tiagorlampert/CHAOS/master/content/logo.png">
</p>

<h1 align="center">CHAOS Generador de Payload</h1>
<p align="center">
  <a href="https://golang.org/">
    <img src="https://img.shields.io/badge/Golang-1.10-blue.svg">
  </a>
  <a href="https://github.com/tiagorlampert/CHAOS/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-BSD%203-lightgrey.svg">
  </a>
  <a href="https://github.com/tiagorlampert/CHAOS/blob/master/CHAOS.go">
    <img src="https://img.shields.io/badge/Release-2.5.0-red.svg">
  </a>
    <a href="https://opensource.org">
    <img src="https://img.shields.io/badge/Open%20Source-%E2%9D%A4-brightgreen.svg">
  </a>
</p>


## ACLARACION

ESTE SOFTWARE SE PROPORCIONA "TAL CUAL" SIN GARANTÍA DE NINGÚN TIPO. PUEDE USAR ESTE SOFTWARE BAJO SU PROPIO RIESGO. EL USO ES RESPONSABILIDAD COMPLETA DEL USUARIO FINAL. LOS DESARROLLADORES NO ASUMEN NINGUNA RESPONSABILIDAD Y NO SON RESPONSABLES DE NINGÚN MAL USO O DAÑO CAUSADO POR ESTE PROGRAMA.

## HERRAMIENTAS
- [x] Reverse Shell
- [x] Descarga de archivos
- [x] Subida de archivos
- [x] Capturas de pantalla
- [x] Keylogger
- [x] Persistencias
- [x] Aperturad de URL remoto
- [x] Obtener el nombre del sistema operativo
- [x] Run Fork Bomb

## COMO USAR

[![Kali)](https://www.google.com/s2/favicons?domain=https://www.kali.org/)](https://www.kali.org) **Kali Linux - ROLLING EDITION**
```bash
# Install dependencies (You need Golang and UPX package installed)
$ apt install golang xterm git upx-ucl -y

# Clone this repository
$ git clone https://github.com/tiagorlampert/CHAOS.git

# Get and install external imports (requirement to screenshot)
$ go get github.com/kbinani/screenshot && go get github.com/lxn/win
$ go install github.com/kbinani/screenshot && go install github.com/lxn/win

# Maybe you will see the message "package github.com/lxn/win: build constraints exclude all Go files".
# It's occurs because the libraries are to windows systems, but it necessary to build the payload.

# Go into the repository
$ cd CHAOS

# Run
$ go run CHAOS.go
```

## Screenshot (outdated)
<p align="center">
<img src="https://github.com/tiagorlampert/CHAOS/blob/master/content/screenshot.gif">
</p>

## Video
<p align="center">
<a href="https://www.youtube.com/watch?v=9P-3qSA_ZjQ">
  <img src="https://img.youtube.com/vi/9P-3qSA_ZjQ/maxresdefault.jpg" width="700"/>
</a></p>

                falocab
I look at you and I hack your face, bitch !!

