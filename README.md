# plantillaELAN
Una plantilla básica ELAN / A basic ELAN template
</br>
</br>
Aquí se encuentra una plantilla básica ejemplar para empezar a usar ELAN, una aplicación para anotar grabaciones. Esta plantilla (.etf) esta diseñada para facilitar la creación de transcripciones, traducciones, y notas en forma de un archivo de anotación ELAN (.eaf), y es apta para exportar transcripciones y traducciones de ELAN al formato .flextext para importar en FLEx (Fieldworks Language Explorer).
</br>
</br>
Esta plantilla básica cuenta con cuatro líneas: una línea idependiente para metadatos sobre la grabación y las anotaciones, una línea madre para transcripciones, una línea dependiente para traducciones, y una línea dependiente para otras notas. Se puede agregar, cambiar, o borrar líneas de la plantilla como sea necesaria para su proyecto. 
</br>
</br>
Para usarla para exportar transcripciones y traducciones a FLEx, hay que cambiar el código de lengua en los nombres de las líneas para los metadatos y transcripciones. En esta plantilla ejemplar el código tiene forma de "xxx", por ejemplo: "A_Transcripcion_txt_xxx". Para que la exportación funcione correctamente, es necesario que el código sea igual al código de lengua utilizado en FLEx. Este código suele ser el código ISO 639-3 para la lengua, y se encuenta en FLEx bajo Tools --> Configure --> Set up writing systems. En la ventana que abre, seleccione la lengua en la lista y haga clic en Modify. En la ventana que abre, busca el código al fondo del lado derecho donde dice "Internal code". 
</br>
</br>
Referencias:
</br>
ELAN (Version 6.3) [Computer software]. (2022). Nijmegen: Max Planck Institute for Psycholinguistics, The Language Archive. Retrieved from https://archive.mpi.nl/tla/elan
</br>
FLEx (Fieldworks Language Explorer) [Computer software]. (2022). Summer Institute of Linguistics. Retrieved from https://software.sil.org/fieldworks/
