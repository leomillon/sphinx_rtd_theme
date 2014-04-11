======================
eZy Documentation Test
======================

----
Misc
----

This is a code block
    .. code:: java

        public class MyJavaClazz {

            private String myString;

            public MyJavaClazz() {
                // This is a comment...
            }

        }

-------
Methods
-------

returnObj nomMethode() nomChannel
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Contexte d'appel
  Bla bla bla...

Description des informations retournées et de leur utilité.
  Bla bla bla...

  Bla bla bla BIS...

Cas d'erreur à traiter de manière particulière.
  Bla bla bla..., une ``Exception`` est envoyée.

+----------------------------------------------+---------+-----------+-------------------------------------------------+
| Paramètre                                    | Type    | Optionnel | Commentaire                                     |
+==============================================+=========+===========+=================================================+
| param1                                       | String  | Non       | Commentaire du paramètre n°1.                   |
+----------------------------------------------+---------+-----------+-------------------------------------------------+
| param2                                       | Integer | Non       | Ceci est un loooooooong commentaire décrivant   |
|                                              |         |           | le cas d'utilisation du 2ème paramètres.        |
+----------------------------------------------+---------+-----------+-------------------------------------------------+
| param3                                       | Object  | Oui       | Bla bla bla...                                  |
+----------------------------------------------+---------+-----------+-------------------------------------------------+

.. WARNING::
    Ceci est un message de ``warning``

-----
Enums
-----

com.myapp.model.enums MyType
  Bla bla bla...

+------------------------------------+----------------------------------------------------------------------+
|  Valeur                            |  Description                                                         |
+====================================+======================================================================+
| MY_FIRST_TYPE                      | Description de ``MY_FIRST_TYPE``                                     |
+------------------------------------+----------------------------------------------------------------------+
| MY_OTHER_TYPE                      | Description de ``MY_OTHER_TYPE``                                     |
+------------------------------------+----------------------------------------------------------------------+