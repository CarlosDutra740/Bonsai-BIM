# Bonsai-BIM

**Bonsai** é um _add-on_ gratuito e open-source para o [[Blender]] que transforma o software em uma plataforma nativa de modelagem [[BIM]], como o [[REVIT]](Building Information Modeling), compatível com o padrão [[IFC]] (Industry Foundation Classes) [Blender Extensions](https://extensions.blender.org/add-ons/bonsai/?utm_source=chatgpt.com)[Apprendre Blender](https://apprendre-blender.com/bonsai-pour-blender-la-puissance-du-bim-open-source/?utm_source=chatgpt.com). Desenvolvido sobre o motor [[IfcOpenShell]], permite criar, editar, visualizar e gerenciar modelos BIM completos diretamente dentro do Blender


- [[View and explore]] IFC models, including [[spaces]], [[properties]], and [[relationships]]

- The left [[Outliner panel]] shows geometric objects. The centre main [[3D Viewpor]] panel shows 3D geometry. The right [[Properties panel]] shows data and relationships.

If you have a numpad, you can use the numpad keys to quickly switch to top, front, or side view. Use 7 for top view, 1 for front view, and 3 for side view.


    
- [[Edit]] and extract attributes, properties, and metadata directly from IFC data
    
- [[Move]], [[rotate]], and [[modify]] the geometry of objects while preserving IFC semantics
    
- [[Create new objects]] using predefined library elements or custom parametric types
    
- [[Manage classification systems]], document references, and link to external libraries
    
- [[Generate 2D drawing views]] like [[plans]], [[sections]], and [[elevations with customizable annotations]]
    
- Investigate and edit structural analysis models with support for various steel profiles
    
- Model and manage complex distribution systems like [[HVAC]], [[plumbing]], and [[electrical]] ([[MEP]])
    
- [[Create construction schedules]], perform [[critical path analysis]], and [[generate sequence animations]]
    
- [[Derive quantities from model elements]] and [[create cost schedules with formulas]]
    
- [[Perform clash detection]] and [[coordinate models]], managing [[issues across disciplines]]
    
- [[Integrate non-geometric data]] like [[costing]], [[scheduling]], and [[asset management]]

- [[Properties Panel]]
It shows the loaded filename, as well as the **IFC Schema**. There are two commonly seen **IFC Schema** versions: [[IFC2X3]] and [[IFC4]]. Checking the **IFC [[Schema]]** is important because it has an impact on what BIM data may be stored. IFC4 is the newer version and it is recommended to use IFC4 models as it has significantly more BIM capabilities compared to IFC2X3.

-- [[IFC Classes]]

IfcSlab
IfcMember
IfcRailing
IfcWall


Physical objects in an IFC file must be categorised to a _class_ of object, which has implications on what properties are expected to be found on the object.If your BIM model has missing or incorrect _class_ categorisations, then your BIM model becomes difficult to use for costing, sustainability quantification, automated scheduling, filtering maintainable assets for facility management, and more.

**`IfcDamperType / IfcDamper`**

**`IfcSensorType / IfcSensor`**

- _`FIRESENSOR`_ - A device that senses or detects fire
    - _`CO2SENSOR`_ - A device that senses or detects carbon dioxide.
    - _`CONDUCTANCESENSOR`_ - A device that senses or detects electrical conductance.
    - _`CONTACTSENSOR`_ - A device that senses or detects contact, such as for detecting if a door is closed.
    - _`COSENSOR`_ - A device that senses or detects carbon monoxide.
    - _`FLOWSENSOR`_ - A device that senses or detects flow in a fluid.
    - _`FROSTSENSOR`_ - A device that senses or detects frost on a window.
    - _`GASSENSOR`_ - A device that senses or detects gas concentration (other than CO2)
    - _`HEATSENSOR`_ - A device that senses or detects heat.
    - _`HUMIDITYSENSOR`_ - A device that senses or detects humidity.
    - _`IDENTIFIERSENSOR`_ - A device that reads a tag, such as for gaining access to a door or elevator
    - _`IONCONCENTRATIONSENSOR`_ - A device that senses or detects ion concentration, such as for water hardness.
    - _`LEVELSENSOR`_ - A device that senses or detects fill level, such as for a tank.
    - _`LIGHTSENSOR`_ - A device that senses or detects light.
    - _`MOISTURESENSOR`_ - A device that senses or detects moisture.
    - _`MOVEMENTSENSOR`_ - A device that senses or detects movement.
    - _`NOTDEFINED`_ - Undefined type.
    - _`PHSENSOR`_ - A device that senses or detects acidity.
    - _`PRESSURESENSOR`_ - A device that senses or detects pressure.
    - _`RADIATIONSENSOR`_ - A device that senses or detects pressure.
    - _`RADIOACTIVITYSENSOR`_ - A device that senses or detects atomic decay.
    - _`SMOKESENSOR`_ - A device that senses or detects smoke.
    - _`SOUNDSENSOR`_ - A device that senses or detects sound.
    - _`TEMPERATURESENSOR`_ - A device that senses or detects temperature.
    - _`USERDEFINED`_ - User-defined type.
    - _`WINDSENSOR`_ - A device that senses or detects airflow speed and direction.

