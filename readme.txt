Proyecto Final: Extensión del modelo de virus de NetLogo

Este programa considera algunos parámetros extra en el desarrollo de una pandemia, en el esfuerzo por mitigar sus efectos, como son el distanciamiento social, el uso de cubrebocas y la vacunación. Además, incluye estornudos, residuos en el ambiente y considera las posibles muertes.

En la interfaz se observan varios sliders y monitores, así como el espacio del desarrollo de la simulación, los botones para controlarla y una gráfica de algunos parámetros.

El botón "setup", genera los agentes en el espacio de la simualción de acuerdo con las condiciones impuestas por los parámetros de los sliders.
El botón "go", avanza la simulación una unidad de tiempo (un tick).
El botón "go" en modalidad "forever", activa la simulación una cantidad indefinida de ticos, hasta que se den las condiciones de paro y se detenga.

El slider "poblacion", controla la población inicial de la simulación. 
El slider "S0", controla la cantidad inicial de agentes con estado "susceptible".
El slider "p-infeccion", modula la probabilidad de que los agentes se infecten en las condiciones establecidas como de posible contagio.
El slider "duracion", permite variar la cantidad de ticks en los que un agente tendrá el estado "infectado", antes de recuperarse o morir.
El slider "p-distanciamiento", representa la estrategia de distanciamiento social. Permite variar el porcentaje de agentes que llevan a cabo dicha estrategia.
El slider "p-sneeze", modula la probabilidad de un agente estornude y deje residuos en el ambiente, formando una nube de residuos alrededor de él temporalmente y con un cierto alcance.
El slider "p-cubrebocas", representa la estrategia de uso de cubrebocas. Permite variar el porcentaje de agentes que llevan a cabo dicha estrategia.
El slider "p-muerte", modula la probabilidad de que los agentes mueran. 
El slider "p-vacuna", representa la estrategia de vacunación. Permite variar el porcentaje de agentes que llevan a cabo dicha estrategia.

El monitor "Emax", muestra el valor del tick en el que se alcanza el número máximo de infectados, es decir, es la coordenada x del máximo de la curva de infectados.
El monitor "Poblacion inicial", muestra la cantidad de agentes en el tick 1.
El monitor "Población restante", muestra la cantidad de agentes hasta ese instante de tiempo, restando el número de muertes a la población inicial.
El monitor "Total contagios", muestra el número de agentes con el estado "infectado" hasta ese instante de tiempo, es decir, los agentes de color rojo.
El monitor "Total contagios (%)", muestra lo mismo que el anterior, pero en porcentaje.
El monitor "Max infectados", muestra el número máximo de agentes infectados en un mismo instante de tiempo, es decir, corresponde a la coordenada y del máximo de la curva de infectados.
El monitor "Max infectados (%)", muestra lo mismo que el anterior, pero en porcentaje.
El monitor "Muertes", muestra la cantidad de agentes que han muerto hasta ese instante de tiempo.
El monitor "Muertos (%)", muestra lo mismo que el anterior, pero en porcentaje.
El monitor "Susceptibles", muestra el número de agentes con el estado "susceptible" hasta ese instante de tiempo, es decir, el número de agentes de color azul.
El monitor "Contagios estornudo", muestra el número de agentes infectados mediante los residuos de un estornudo hasta ese instante de tiempo, es decir, aquellos que estuvieron determinado tiempo en contacto con la nube de residuo de un estornudo de otro agente.
El monitor "Contagios contacto", muestra el número de agentes infectados mediante el contacto con otro agente infectado por un determinado tiempo, hasta ese instante de tiempo.

La gráfica "Población", muestra las 3 curvas de interés: Susceptibles (agentes de color azul en el tiempo), Infectados (agentes de color rojo en el tiempo) y Recuperados (agentes de color verde en el tiempo).



