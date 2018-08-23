# Visión por computador  2018-1

_Regístrate [aquí](https://goo.gl/forms/VJRlUKah7DlMBLlf2)_. 
                                            
La máquina virtual puede descargarse [aquí](https://drive.google.com/file/d/1KxCUZlXDgyvJzfs6s7EfegMVS1HL_bXq/view?usp=sharing)


## Máquina Virtual

Usaremos esta máquina virtual que tiene instalado un entorno Python Anaconda con Jupyter Notebooks disponibles en  [localhost:8008/tree](http://localhost:8008/tree) una vez que la máquina arranca.

**Observa la configuración de la máquina**

- Si tu máquina física tiene al menos 4GB de memoria configura la máquina virtual **con 2GB de memoria**
- Aunque casi no necesitarás un terminal, el interfaz de Jupyter Notebooks tiene un terminal para acceder a través del navegador. En cualquier caso, la máquina virtual tiene un servidor SSH en el puerto 2222 con user/user como usuario y pwd. Si tu máquina física es mac o linux usa `ssh -p 2222 user@localhost` para conectarte. Si es windows, usa [putty](https://www.putty.org/)
- Si compartes una carpeta entre la física y virtual asegúrate que **el nombre cone el que se comparte** sea `share` (aunque el nombre de la carpeta en la máquina física puede ser distinto)

**Para montar la carpeta compartida** ejecuta lo siguiente en un terminal y la carpeta aparecerá en /home/user/share:

    sudo mount share


## Calificación
40% Talleres (Problemsets)<br/>
30% Parciales (Quizes) <br/>
30 % + [10% ,20 %, 30 %] Proyecto funcional IA <br/>
+10% Online courses (MOOC)

## Talleres (Problemsets)

Los talleres pretender ser una herramienta practica para afianzar los conocimientos desarrollados durante las clases. En general se presentan como un conjunto de ejercicios que serán desarrollados **individualmente** por los estudiantes. Cada taller esta escrito como un notebook para la validación automática. Se pueden hacer tantos intentos como se quieran y unicamente la última respuesta será tomada en cuenta. Cada uno de los talleres ser desarrollará en casa, dentro de las fechas establecidas en el cronograma. 


## Parciales (Quizes)

Son evaluaciones **individuales** basadas en notebooks sobre los temas tratados en las clases. Los estudiantes deben solucionarlo en el salón de clase, en un tiempo determinado. Los apuntes y notebooks del curso se pueden utilizar. 


## Proyecto funcional IA

- **Funcionamiento del proyecto**. El proyecto se debe realizar como un notebook.  

- **Prototipo [+10% - +20%]**:  En este item se considera como esta estructurado el proyecto. Los porcentajes extras tienen en cuenta importancia o relevancia de 
del proyecto y también la solución a problemas  reales.

- **Presentación (video y diapositivas) [+ 10%]**:  Se debe enviar un video corto (max 5 minutos) y un documento de máximo 5 páginas en donde se exponga: 

1- La motivación para el desarrollo del proyecto
2- El tema principal de inteligencia artificial abordado
3- funcionamiento y simulación del proyecto


- **Preguntas**: Se realizarán preguntas cortas a los estudiantes unicamente relacionadas con el proyecto. 
 
Todos los items tienen el mismo porcentaje de evaluación. 


## Online Courses (MOOC) [Extra]

El avance vertiginoso de la tecnología nos obliga a adquirir destresas en el aprendizaje autónomo. Sobre todo en lo relacionado con tecnologias de la información, existen numerosos recursos virtuales que nos permiten estar actualizados con nuevos temas, estrategias y desarrollos. Teniendo en cuenta esta motivación, como parte complementaria del curo se tendrá en cuenta un porcentaje extra para los estudiantes que deseen realizar un MOOC online. El MOOC habrá de tratar un topico relacionado con la tecnología y ha de cubrir aproximadamente 15 horas de esfuerzo, que se evaluarán según la definición y dinámica de cada caso. Puedes hacerlo en cualquier plataforma existente, como por ejemplo: [Coursera](www.coursera.org), [EDX](www.edx.org), [Udacity](www.udacity.org),  [MiriadaX](https://miriadax.net/), etc.

Tendras que hacer un informe de tu seguimiento del MOOC. La entrega ha de constar de:

- Un archivo PDF llamado MOOC_descripcion.pdf donde se describa el MOOC (primera entrega)
- Un archivo PDF llamado MOOC_completado.pdf donde se incluya la evidencia de la realizacin del MOOC
- Un directorio llamado MOOC_materiales donde se incluyan los materiales pertinentes (scripts, datos, etc.) que apoyen la evidencia mostrada en el archivo PDF.

**TODA ENTREGA QUE NO CUMPLA CON ESTAS CONVENCIONES SERÁ CONSIDERADA COMO NO REALIZADA**

La calificación del curso vendrá dada por los siguientes criterios con el mismo peso cada uno:

- COMPLEJIDAD DEL MOOC
- CALIDAD DEL REPORTE 
- CLARIDAD DEL REPORTE

## Calendario y plazos

                       SESSION 1            SESSION 2           STUDENT DEADLINES

     W32 Aug07-Aug08    --------            0. Intro
     W33 Aug14-Aug15    1.PYTHON            2.PANDAS
     W34 Aug21-Aug22    3.STATS             3.STATS-PSETS         
     W35 Aug28-Aug29    4.BAYES             4.BAYES-PSETS         
     W35 Sep04-Sep05    QUIZPREP            QUIZ                Feb 25 PSETS 1, 2     
     W37 Sep11-Sep12    5.ML INTRO          6.ML METHODS        Sep 14 Registro primera calificación
     W38 Sep18-Sep19    7.NAIVE             7.NAIVE-PSETS     
     W39 Sep25-Sep26    8.IMGINTRO          9.IMGCLASS          Sep 30 PSETS 3
     W40 Oct02-Oct03    10.IMGCLASS         10.IMGCL- PSETS  
     W41 Oct09-Oct10    PSETS               PSETS               Semana de trabajo independiente            
     W42 Oct16-Oct17    QUIZPREP            QUIZ                Oct 21 PSETS 4, 5
     W43 Oct23-Oct24    PROJECT             PROJECT    
     W44 Oct30-Oct31    11.KMEANS		    11.KMEANS           semana FIMEC U18
     W45 Nov06-Nov07    12.PLAN             12.PLAN-SETS	
     W46 Nov13-Nov14    13.GA               13.GA-PSETS        
     W47 Nov20-Nov21    14.SA               14.SA-PSET	        Dic02 PSETS 6 7 8 
     W48 Nov27-Nov28    QUIZPREP            QUIZ		
     W49 Dic04-Dic05    15.Deep L           15.Deep L
     W50 Dic11-Dic12    PROJECT             PROJECT             Entrega y sustentación de proyectos

     


    Sep14 -        -> Registro primera calificación
    Sep16 -        -> Último día cancelación materias
    Oct08 - Oct12  -> Semana estudiantil de trabajo independiente
    Nov30 -        -> Finalización clase
    Dic03-Dic12    -> Evaluaciones finales
    Dic14 -        -> Registro calificaciones finales



**CUALQUIER ENTREGA FUERA DE PLAZO SERÁ PENALIZADA CON UN 50%**
**LOS PROBLEMSETS ESTAN SUJETOS A CAMBIOS QUE SERÁN DEBIDAMENTE INFORMADOS%**
    
[Calendario academico](https://www.uis.edu.co/webUIS/es/academia/calendariosAcademicos/2018/acuerdoAcad094_2018.pdf)


