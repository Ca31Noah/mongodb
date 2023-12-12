mongodb://root:root123@192.168.184.143:28106/?tls=false&authMechanism=DEFAULT
mongodb://root:root123@192.168.184.143:27017/?tls=false&authMechanism=DEFAULT
mongodb://root:root123@192.168.184.143:28105/?tls=false&authMechanism=DEFAULT

use("espoch_store")
db.productos.find()

use("espoch")
db.estudiantes.find()

use("SedeO")
db.Alumnos.find()