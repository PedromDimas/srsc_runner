# srsc_runner

## setup

Por os 2 ficheiros na pasta ```bash init-materials ```

## RUN

pa correr compilas tudo

```bash
com o terminal na pasta init-materials

$ cd hjStreamServer && javac *.java && cd ../hjUPPproxy && javac *.java

```

depois abre o vlc, vai a Media>Open Network Stream

```http
udp://@224.7.7.7:7777
```

finalmente abrir 2 terminais na pasta init-materials

no 1o correr
```bash
./runProxy.sh
```
no 2o correr
```bash
./runServer.sh
```

## ERROS

se o runProxy ou o runServer n funcionar devido a permissoes, faz

```bash
chmod 777 runProxy.sh && chmod 777 runServer.sh
```
