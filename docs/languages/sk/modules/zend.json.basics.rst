.. EN-Revision: none
.. _zend.json.basics:

Základné použtie
================

Používanie *Zend_Json* vyžaduje použitie týchto dvoch metód: *Zend_Json::encode()* a *Zend_Json::decode()*.

.. code-block:: php
   :linenos:

   <?php
   // Získanie hodnoty:
   $phpNative = Zend_Json::decode($encodedValue);

   // Zakódovanie pre ďalšie použitie na klientovi:
   $json = Zend_Json::encode($phpNative);
   ?>

