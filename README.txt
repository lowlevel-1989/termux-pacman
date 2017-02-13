# Bajar termux-pacman
curl -L -O https://github.com/formatcom/termux-pacman/raw/master/termux-pacman.tar.gz

# Descomprimir en el home de termux
tar xvf termux-pacman.tar.gz

# Activar el comando arch
source termux-pacman/active

# Verificar funcionamiento
arch

# Utilizar pacman
arch pacman -S go

# Ejecutar binarios instalados con pacman
arch go version


### NOTA ###
Solo se ha probado instalando
- mariadb-clients
- go

si encuentran algun paquete que de error dejarlo en issues


