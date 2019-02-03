# geotracking
Geotracking
Proyecto 1 topicos especiales en telemática

    Aplicación que permita desde un teléfono inteligente registrar los puntos sobre las rutas que desee seguir un usuario(tracking-gps), para poder visualizar la ruta que siguio y poderla compartir con otros usuarios.

Construido con:
    NodeJs 
    MongoDB 
    Express 
    Javascript

Modelo de datos
    
        User:
        {
            name: String,
            email: String,
            password: String,
            date: Date
        }

        Note:
        {
            title: String,
            description: String,
            date: Date,
            user; String
        }

Despliegue

aavenda1.dia.eafit.edu.co

http://ec2-18-223-151-14.us-east-2.compute.amazonaws.com/notes

Desarrollado por:
    Andres Felipe Avendaño Restrepo 
    aavenda1@eafit.edu.co
