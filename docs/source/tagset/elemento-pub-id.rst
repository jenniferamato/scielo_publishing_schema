.. _elemento-pub-id:

<pub-id>
========


Atributos obrigatórios:

  1. ``@pub-id-type``

+----------------------------------+--------------------+
| Aparece em                       | Ocorre             |
+==================================+====================+
| :ref:`elemento-element-citation` | Zero ou mais vezes |
+----------------------------------+--------------------+


Especifica o identificador de uma publicação em uma referência bibliográfica. O atributo ``@pub-id-type`` é mandatório e explicita o tipo do identificador, autoridade ou organização responsável pela atribuição deste. Os valores possíveis são:

+--------------+---------------------------------------------------+
| Valor        | Descrição                                         |
+==============+===================================================+
| pmid         | :term:`PubMed` ID                                 |
+--------------+---------------------------------------------------+
| pmcid        | :term:`PMC` ID                                    |
+--------------+---------------------------------------------------+
| doi          | Número DOI registrado no CrossRef                 |
+--------------+---------------------------------------------------+
| pii          | Identificador do publicador                       |
+--------------+---------------------------------------------------+
|art-access-id | Identificador de dados de pesquisa em repositórios|
+--------------+---------------------------------------------------+
| other        | qualquer outro identificador                      |
+--------------+---------------------------------------------------+

Exemplo:

.. code-block:: xml

    ...
    <element-citation>
        <pub-id pub-id-type="pmid">15867408</pub-id>
    </element-citation>
    ...


.. {"reviewed_on": "20160628", "by": "gandhalf_thewhite@hotmail.com"}
