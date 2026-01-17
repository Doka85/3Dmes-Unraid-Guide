Dieser Fehler erscheint, weil MQTT noch nicht bereit ist, aber der Datenlogger bereits versucht zu verbinden. Das ist kein Problem, weil er alle 5 Sekunden nochmals versucht zu verbinden. Diese Nachricht kann ignoriert werden, der Fehler soll aber in einer der kommenden Versionen gefixt werden

```text
MQTTnet.Exceptions.MqttCommunicationException: Error while connecting host 'Unspecified/127.0.0.1:1883'.
 ---> System.Net.Sockets.SocketException (111): Connection refused
    at System.Net.Sockets.Socket.AwaitableSocketAsyncEventArgs.ThrowException(
        SocketError error,
        CancellationToken cancellationToken)
```

