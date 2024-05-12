# metodologias-tarea-semana-6
'Use Strict';
let Clave = 3214;
let Contador = 0;
let num;

do{
    num = (Number(prompt("Ingresar Clave")));
    Contador++;
}
while (num != Clave && Contador < 5);
if( Contador == 5 && num != Clave)
    {
        alert ("Clave Incorrecta");
        alert ("Tarjeta Bloqueada");
 }else
 {
     alert ("Clave Correcta");
     alert ("Operaciones Exitosas");
};

