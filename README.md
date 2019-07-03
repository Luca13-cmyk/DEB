# DEB
Modelo para criar .deb
// cria a pasta
# mkdir pki
// entra na pasta
# cd pki
// cria o diretório DEBIAN
# mkdir DEBIAN
// cria o binário
# mkdir -p usr/bin/
// cria o application
# mkdir -p usr/share/applications/
// cria o pixmaps
# mkdir -p usr/share/pixmaps









// para construir o pacote
# dpkg-deb -b pki/ pki.1.0.deb
// para instalar
# dpkg -i pki.1.0.deb
// para remover
# apt remove teste
