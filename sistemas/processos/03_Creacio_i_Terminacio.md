### Creació i Terminació de Processos

La creació i terminació de processos són aspectes crucials en la gestió eficient de l'execució de programes en un entorn informàtic. La creació d'un nou procés implica típicament la duplicació d'un procés existent, donant origen a un procés fill independent amb els seus propis recursos i espai de memòria. Aquest procés fill hereta característiques del procés pare, com el seu codi, dades i context d'execució.

#### Creació de Processos

La creació de processos es duu a terme mitjançant l'ús d'anomenades al sistema operatiu específiques. Quan un programa invoca la creació d'un nou procés, el sistema operatiu assigna recursos, com a espai de memòria, identificadors de procés (PID), i estableix una relació jeràrquica entre el procés pare i el fill.

És important destacar que la creació de processos no sols permet l'execució simultània de múltiples tasques, sinó que també facilita la *modularidad i l'eficiència en el disseny de programari. Els processos independents poden executar-se de manera autònoma, comunicar-se entre si i fer tasques específiques sense afectar la integritat del sistema.

#### Terminació de Processos

La terminació d'un procés pot ser tant voluntària com involuntària. La terminació voluntària ocorre quan el procés completa la seva tasca assignada i finalitza de manera ordenada. En contrast, la terminació involuntària pot ser el resultat d'errors, excepcions no manejades o condicions anòmales.

El sistema operatiu és responsable d'alliberar els recursos assignats a un procés acabat i notificar al procés pare sobre la seva finalització. A més, la terminació d'un procés pot desencadenar esdeveniments com l'alliberament de memòria i l'actualització de registres d'estat.

En conjunt, la creació i terminació de processos són processos dinàmics i essencials en l'administració eficient dels recursos del sistema, permetent l'execució concurrent i la gestió adequada de la càrrega de treball.

Al llarg d'aquest treball, explorarem més a fons aquests processos, analitzant les seves implicacions en l'estructura i el rendiment dels sistemes operatius moderns.

[README](README.md)
