# proxy
Listado de Ips y dominios para filtrar

## Archivo lista.txt

*Este archivo se actualiza automaticamente una vez por día obteniendo el listado oficial de spamhause combinado con emergingthreats, abuse.ch y cinsscore.com/* 

## radiosysitios.txt

*No es automatico! Es una seleccion de Radios y Sitios (como diarios etc) que alguna vez piden que se bloquen en proxys y bueno... no es de milico sino un pedido de cliente por exceso de joda tal vez?*

Si necesitas el listado sin los simbolos usa el comando  `sed 's/^||//; s/\^$//' radiosysitios.txt > limpio.txt`. 
