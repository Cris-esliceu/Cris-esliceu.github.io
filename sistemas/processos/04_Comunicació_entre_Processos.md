## Comunicació entre Processos

La capacitat dels processos per a intercanviar informació i cooperar és essencial en entorns informàtics on múltiples tasques han de realitzar-se de manera simultània i coordinada. La comunicació entre processos (IPC, per les seves sigles en anglès) es converteix en un component crític per a aconseguir aquesta col·laboració de manera efectiva. Diversos mecanismes faciliten la comunicació entre processos, permetent l'intercanvi de dades, senyals i coordinació.

### Pipes

Els pipes, o canonades, són un dels mecanismes més simples per a la comunicació entre processos. Un *pipe estableix una connexió unidireccional entre dos processos, permetent que la sortida d'un procés es converteixi en l'entrada de l'altre. Això facilita la transferència de dades de manera eficient. Els *pipes són especialment útils en situacions on un procés genera dades que han de ser consumits per un altre de manera seqüencial.

### Cues de Missatges

Les cues de missatges proporcionen un mecanisme de comunicació entre processos independents. En aquest model, els processos poden enviar missatges a una cua i altres processos poden recuperar aquests missatges de la cua. Aquest enfocament és útil quan els processos necessiten comunicar-se de manera asíncrona i compartir informació sense establir una connexió directa.

### Memòria Compartida

La memòria compartida permet que diversos processos accedeixin a la mateixa regió de memòria. Això facilita la comunicació en permetre que els processos comparteixin dades de manera eficient. No obstant això, l'ús de la memòria compartida també requereix una acurada sincronització per a evitar conflictes i garantir la integritat de les dades compartides.

### Senyals

Els senyals són esdeveniments asincrònics que un procés pot enviar a un altre per a notificar esdeveniments o sol·licitar unes certes accions. Aquest mecanisme és especialment útil per a la gestió d'esdeveniments i la coordinació entre processos.

### Sockets

Els sockets permeten la comunicació entre processos en diferents sistemes o fins i tot a través d'una xarxa. Proporcionen una interfície estàndard per a la comunicació, la qual cosa facilita la interacció entre processos en màquines separades.

L'elecció del mecanisme de comunicació entre processos depèn de la naturalesa de la tasca i els requisits específics de l'aplicació. La comprensió d'aquests mecanismes és essencial per al disseny de sistemes robustos i eficients.

[README](README.md)
