# Minecraft-Dakota-Games-Server


# Archivos
whitelist.json - Si se activa la whitelist solo los usuarios en esta lista pueden entrar
server.properties - Propiedades de configuracion del servidor (vanilla)
banned-ips - Lista de ips baneadas (recomendado para servers piratas)
banned-players - Lista de jugadores baneados
ops - Lista de usuarios administradores


# Comandos admin
/stop - Apagar servidor
/op {usuario} - Da el rango mas alto de server a un usuario
/deop {usuario} - Saca el rango mas alto de server a un usuario
/lp creategroup {nombre} - Crear un grupo
/lp group {grupo} permission set {comando} true - Agrega un comando a un grupo (ej: minecraft.command.ban)
/lp group {grupo} permission unset {comando} - Quita un comando a un grupo
/lp user {user} parent add {grupo} - Agrega un usuario a un grupo
/lp group {grupo1} parent add {grupo2} - Hace que grupo1 herede de grupo2
/lp user {grupo1} parent remove {grupo2} - Queta grupo 1 como heredado de grupo2


# Comandos jugadores
/register {contraseña} - Registra la cuenta (solamente la primera vez que entras)
/login {contraseña} - Entras a la cuenta (cada vez que entras al server)
/spawn - TP al spawn
/sethome {nombre} - Guarda la ubicacion sobre la que estas parada como "casa"
/home {nombre} - TP a la ubicacion previamente guardada
/warps - Muestra la lista de ubicaciones
/warp {nombre} - TP a una ubicacion especifica
/dc list - Muestra las tumbas (con coordenadas)
/dc giveBack {user} - Obtiene los items de la tumba
/shop o /tienda - Abre la tienda para comprar
/sell o /vender - Abre la tienda para vender
/ping - Muestra tu ping
/ping list - Muestra el ping de todos


# Comandos pagos
/back - Vuelve a la ubicacion anterior
/fly - Activa volar en survival
/heal - Te curas toda la vida
/repair - Repara el objeto que tengas en la mano

