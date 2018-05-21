# rsk
Notas sobre la plataforma RSK
##
Requisitos, pasos y notas sobre la instalación de un nodo RSKj.

1.  Instalar Java 8
2.  Descargar el fichero <a href="https://github.com/rsksmart/rskj/releases/download/BAMBOO-0.4.2/rskj-core-0.4.2-BAMBOO-all.jar">rskj-core-0.4.2-BAMBOO-all.jar</a>
3.  Generar los claves e identificadores del nodo asi:<br> 
    roote@nlp:/home/rsksmart# java -cp rsk—core-O.4.2-BAMBO—all.jar co.rsk.GenNodeKeyId<br>
    {
        “privateXey": "3aSsBSbOa3XXXXXXXXXXXX69lfaddS2ecccqc94ocfl9fc964a7fodc9d2b2daelS3eaqccfb59",
        "publicKey": "0406e4abl25i44c9602XXXXXXXXXXXXXXXXXXc4badOlB39bildedB9ccS9f466b3baeSlf3ZOd9edfeef7SS3fa6Zef4Bbb4f44e4O6dlSci"
        "publicKeyCompressed": "O3O6e4ablZ5i44cXXXXXXXXXXXXOe64SfbclbadOlB3SbildedB9cC59f466b3baa",
        "address": "4652c1266d5a22cc7c49c73.6ac2f66d526709lc",
        "nodeId": "06e4ab12544c9602eZcdbfOe648fbe4badOl839bl lded89ccS9fl66b3beaßlf3ZOd9edfS8f78S3ta6Zef4Sbb4f44e4O6dlSc600SS",
    }
    root@nlp:/home/rsksmart# vi mainnet.conf

