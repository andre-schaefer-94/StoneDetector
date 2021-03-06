# StoneDetector - Finding Structural Clones and Subclones in Java Source Code

If you just want to try StoneDetector, you can also visit the tool website: [stonedetector.fmi.uni-jena.de](https://stonedetector.fmi.uni-jena.de).

### Run StoneDetector
* Adjust the configuration file under config

* Compile StoneDetector ( Java 11 )
```
./gradlew jar
```

* Run StoneDetector
```
java -Xms4G -Xmx4G  -jar build/libs/StoneDetector.jar -x --directory="path/to/Java/Folder" --error-file=errors.txt 
```

### StoneDetector with BigCloneEval
 Use BCE_runner as tool runner script for BigCloneEval.

### I want to know more
That's great. Our [ICSME'21](https://www.computer.org/csdl/proceedings-article/icsme/2021/288200a070/1yNh4Mp9yE0) paper is a good introduction to the technology behind StoneDetector. Don't hesitate to contact us if you have any questions.

Unfortunately, the code has not been cleaned yet, though we are aiming to do so in the near future.
