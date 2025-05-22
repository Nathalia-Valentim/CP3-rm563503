# Script de minfo.sh
Exibição de informações baseado em um argumento (hostname, uptime, disk, all)

# Argumentos
- hostname (mostra o nome da máquina)
- uptime (o tempo que o sistema está funcionando/ligado)
- disk (participação '\')
- all (mostra as informações acima - hostname, uptime, disk, all)

# Exemplos (git bash/ubuntu)
./minfo.sh hostname
./minfo.sh uptime -p
./minfo.sh df -h /
./minfo.sh all