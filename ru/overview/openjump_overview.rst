:Author: OSGeo-Live
:Reviewer: Cameron Shorter, Jirotech
:Version: osgeo-live6.0
:License: Creative Commons Attribution 3.0 Unported (CC BY 3.0)

.. image:: /images/project_logos/logo-openjump.png
  :alt: project logo
  :align: right
  :target: http://www.openjump.org

OpenJUMP
================================================================================

Настольная ГИС
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
OpenJUMP — лёгкая в использовании и вместе с тем мощная настольная ГИС,
которая позволяет пользователям отображать, править, анализировать и
объединять различные геопространственные данные.

OpenJUMP предоставляется в двух версиях — CORE (базовая установка) и PLUS,
которая, кроме базовой, включает множество полезных дополнений.

OpenJUMP отлично подходит для редактирования векторных данных и быстрого
прототипирования ГИС-функций. 

.. image:: /images/screenshots/1024x768/openjump-screenshot.png
  :scale: 50 %
  :alt: project screenshots
  :align: right

Базовые функции и плагины
--------------------------------------------------------------------------------

* Форматы данных

    * чтение (файлы): GML, SHP, DXF*, MIF*, CSV* & TIFF, JPG, PNG, JPEG2000*, MrSID*, ECW*
    * чтение (БД): PostGIS, ArcSDE*, Oracle*, MySQL* и SpatiaLite*
    * чтение (стандарты OGC): WKT, WMS
    * запись: GML, SHP, WKT, DXF*, PostGIS* & JPG, TIFF и SVG*
    * заметьте, что форматы, отмеченные звёздочкой (*), доступны только через дополнительные плагины.

* Редактирование и объединение данных

    * оцифровка точек, линий, полигонов, мультигеометрии, коллекций геометрии и кругов, в конечном итоге смешанных в одном слое;
    * добавление, перемещение, удаление вершин;
    * вращение, масштабирование, автозавершение полигона;
    * разрезание, соединение, упрощение полигонов и линий;
    * привязка векторов, инструменты оценки качества.

* Анализ и запросы

    * пространственные и атрибутивные запросы;
    * анализ: буфер, объединение, перекрытие, центроиды, выпуклые оболочки...;
    * статистика: длина, площадь, статистика по слою, статистика по атрибутам, графики;
    * инструменты редактирования: конвертер, извлечение вершин, построение полигонов, создание планарного графа, чистка топологии (в PLUS-версии);
    * средства для работы с атрибутами: присоединение, сравнение*
    * библиотека геоалгоритмов SEXTANTE включена в PLUS-версию. 

* Настройка

    * интернационализация (cz, de, en, es, fi, fr, hu, it, ja, pt, ta, zh)
    * предоставляется API, пользовательские скрипты через BeanShell и Java Python
    * (Java) система плагинов.
   

Реализованные стандарты
--------------------------------------------------------------------------------

.. Writing Tip: List OGC or related standards supported.

* Поддерживаемые стандарты OGC: GML2, SFS, WMS and SLD; (WFS для *deegree*)

Подробная информация
--------------------------------------------------------------------------------

**Веб-сайт:** http://www.openjump.org

**Лицензия:** `GPL <http://www.gnu.org/licenses/gpl.html>`_

**Версия ПО:** 1.7.1 (CORE-версия)

**Поддерживаемые платформы:** Windows, Linux, Mac, Unix

**Поддержка сообщества:** http://www.openjump.org/support.html

**Коммерческая поддержка:** http://sourceforge.net/apps/mediawiki/jump-pilot/index.php?title=Professional_Support_Page

**Загрузки:** http://sourceforge.net/projects/jump-pilot/files/ 


Начало работы
--------------------------------------------------------------------------------
    
* :doc:`Введение <../quickstart/openjump_quickstart>`
