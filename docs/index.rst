.. BBC Microbit Micropython documentation master file, created by
   sphinx-quickstart on Tue Oct 20 10:41:30 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

BBC micro:bit MicroPython dokumentaatio
=======================================

Tervetuloa!


BBC Micro:bit on pieni tietokone joka on suunnattu lapsille avuksi ohjelmoinnin oppimiseen. Yksi sen ymmärtämistä
ohjelmointikielistä on Python. Python on suosittu ohjelmointikieli, ja BBC Micro:bitin käyttämää Python-versiota kutsutaan MicroPythoniksi.

Tämä opas sisältää oppitunteja opettajille sekä
API-dokumentaation ohjelmoijille (katso indeksi vasemmalla). Toivomme
että nautit BBC Micro:bitin ohjelmoinnista MicroPythonin avulla.

Jos olet uusi ohjelmoija, opettaja tai epävarma mistä aloittaa, suosittelemme että aloitat oppaista.

.. image:: comic.png

Jos haluat osallistua Micro:bit yhteisöön, voit liittyä microbit@python.org postituslistalle osoitteessa
(https://mail.python.org/mailman/listinfo/microbit). 

.. note::
   
   Tätä projektia kehitetään aktiivisesti. Voit auttaa muita lisäämällä vinkkejä, oppaita, käännöksiä tai kysymyksiä & vastauksia (Q&A) tähän dokumentaatioon. Kiitos!

Seuraavat projektit liittyvät läheisesti BBC Micro:bitin ohjelmointiin MicroPythonilla:

* `Mu <https://github.com/ntoll/mu>`_ - yksinkertainen koodin muokkausohjelma joka on suunnattu lapsille, opettajille ja aloittelijoille. Mu on todennäköisesti helpoin tapa ohjelmoida BBC Micro:bit käyttäen MicroPythonia.
* `uFlash <https://uflash.readthedocs.io/en/latest/>`_ - komentorivityökalu jonka avulla voi siirtää lähdekoodia BBC Micro:bitin muistiin.


.. toctree::
    :maxdepth: 2
    :caption: Tutorials

    tutorials/introduction
    tutorials/hello
    tutorials/images
    tutorials/buttons
    tutorials/io
    tutorials/music
    tutorials/random
    tutorials/movement
    tutorials/gestures
    tutorials/direction
    tutorials/storage
    tutorials/speech
    tutorials/network
    tutorials/radio
    tutorials/next

.. toctree::
   :maxdepth: 2
   :caption: API Reference

   microbit_micropython_api.rst
   microbit.rst
   accelerometer.rst
   ble.rst
   button.rst
   compass.rst
   display.rst
   filesystem.rst
   i2c.rst
   image.rst
   music.rst
   neopixel.rst
   os.rst
   pin.rst
   radio.rst
   random.rst
   speech.rst
   spi.rst
   uart.rst

.. toctree::
   :maxdepth: 2
   :caption: Developer Guide

   devguide/installation
   devguide/flashfirmware
   devguide/repl
   devguide/devfaq
   devguide/contributing

.. toctree::
   :maxdepth: 2
   :caption: Indices and tables

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
