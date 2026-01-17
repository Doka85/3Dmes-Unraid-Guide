Der Ursprung des Fehlers ist noch unklar, dennoch funktioniert alles wie erwartet:

´´´
 MQTTnet.Exceptions.MqttCommunicationException: Error while connecting host 'Unspecified/127.0.0.1:1883'.
       ---> System.Net.Sockets.SocketException (111): Connection refused
         at System.Net.Sockets.Socket.AwaitableSocketAsyncEventArgs.ThrowException(SocketError error, CancellationToken cancellationToken)
´´´
