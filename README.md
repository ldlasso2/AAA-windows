# The AAA ABox Abduction Solver for Windows

Corrected version of JAVA project for windows.| [Original website and code version](http://dai.fmph.uniba.sk/~pukancova/aaa/) | [Paper](https://link.springer.com/article/10.1007/s13218-020-00685-4) | [ReadMe](http://dai.fmph.uniba.sk/~pukancova/aaa/version-0.12-beta/readme.txt)



## Download Jar file
[JAR file](https://drive.google.com/file/d/19i8iuk3Ckb_Nkh07eNkBX0Gk3VUXUBMo/view?usp=sharing)




```bash
java -jar AAAwin.jar -i family.owl -n -d 2 -out out.txt -obs "http://www.semanticweb.org/julia/ontologies/2017/8/family#Marge: http://www.semanticweb.org/julia/ontologies/2017/8/family#Mother"

```

To execute the previous line, it's necessary to download [family.owl](https://drive.google.com/file/d/1Qx8lzgtexX397yl5x9fgTl5XHNDVh_lB/view?usp=sharing)

## Download Java source code

The actual AAA implementation is located in:

- examples/src/main/java/MHS
- examples/src/main/java/abductiveReasoning
- examples/src/main/java/tableauReasoning

In adductiveReasoning is the AAA.java file.

[JAVA code](https://drive.google.com/file/d/130gC0mRZYTypIX-JHI4NrY_2X8Wm__ii/view?usp=sharing)
