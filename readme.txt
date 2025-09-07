Configrura bash para maven
una ves descargado
colocaen la carpeta descargas y renombrar la carpeta descomprimida como maven
despues de Users y antes de Downloads agregar el usuario


```
ejecutamos en la terminal
> nano ~/.bashrc

pegamos estas lineas pero con el usuario agregado
> export M2_HOME=/c/Users//Downloads/maven
> export PATH=$M2_HOME/bin:$PATH
ctrl + o
ctrl + x

ejecutamos esto para que se actualizen los cambios
> source ~/.bashrc
```


comandos maven
> mnv -v

> mvn archetype:generate "-DgroupId=ar.edu.utnfc.backend" "-DartifactId=projecto_nombre" "-DarchetypeGroupId=org.apache.maven.archetypes" "-DarchetypeArtifactId=maven-archetype-quickstart" "-DinteractiveMode=false"

> mvn compile
> mvn package
> mvn exec:java



etiquetas para lombok
@Data
@Getter
@Setter
@ToString
@AllArgsConstructor
@NoArgsConstructor
@EqualsAndHashCode

recordatorios
creaer carpeta "resources" abajo de la carpeta "main"



