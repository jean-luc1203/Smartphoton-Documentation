1. ## **Changement des paramètres de l’onduleur depuis Topic MQTT**
Il est possible de changer la valeur de certains paramètres depuis l’extérieur de Home Assistant.

Par exemple une autre domotique.

Pour ce faire voici un exemple simple :

On souhaite changer la valeur du paramètre 01 en SOL (celui-ci peut prendre les valeurs UTI, SOL, SBU)

Il suffit pour se faire de publier sur le broker MQTT de Home Assistant sur le topic :

**smartphoton/voltronic\_1-Modification/Param01** la valeur **SOL**

![](Aspose.Words.13ac10c6-e99a-46f5-a3a9-8e98528886aa.001.png)

Et l’onduleur va changer sa valeur en **SOL**. C’est simple et efficace.

![](Aspose.Words.13ac10c6-e99a-46f5-a3a9-8e98528886aa.002.png)

