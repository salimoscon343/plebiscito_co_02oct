# Documento de acuerdo de paz inicial entre el Gobierno de Colombia y la FARC -- proyecto digital de participación

## (Documento sobre el cual se basó el plebiscito del 02 de octubre de 2016, ganado por el #NO a 51%)

Documento original en formato [Markdown](http://daringfireball.net/projects/markdown/) del acuerdo de paz votado en Colombia el 02 de Octubre (http://www.acuerdodepaz.gov.co/plebiscito)

#### Agradecimientos

* Convertir pdf en texto :  
(https://etyn.com/tools/document-converter)


* Separar un texto largo en varios archivos pequeños :  
(http://stackoverflow.com/questions/4952021/splitting-a-large-txt-file-into-200-smaller-txt    -files-on-a-regex-using-shell-scr)

    ```awk
    awk '/^LAcuerdo Final+/{g++} {print $0 > g+1".txt"}' acuerdo_paz.txt
    \#
    \# Atención :
    \# CtrlV + CtrlL para escribir el caracter "^L"
    ```