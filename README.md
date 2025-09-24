Bonsai: Modelagem BIM Nativa no Blender



Este documento descreve o Bonsai, um add-on gratuito e open-source para o Blender que o transforma em uma plataforma de modelagem BIM (Building Information Modeling) nativa, similar ao REVIT, e compatível com o padrão IFC (Industry Foundation Classes). O Bonsai, desenvolvido sobre o motor IfcOpenShell, permite a criação, edição, visualização e gerenciamento de modelos BIM completos diretamente dentro do Blender.



Introdução ao Bonsai



O Bonsai representa uma mudança de paradigma para profissionais de arquitetura, engenharia e construção (AEC) que já utilizam o Blender para visualização e renderização. Ao adicionar funcionalidades BIM nativas, o Bonsai elimina a necessidade de alternar entre diferentes softwares para modelagem, análise e documentação de projetos. Isso resulta em um fluxo de trabalho mais eficiente e integrado, aproveitando a flexibilidade e o poder do Blender.


<img width="780" height="612" alt="Bonsai_ Modelagem BIM Nativa no Blender - visual selection" src="https://github.com/user-attachments/assets/739759e0-e6df-447b-b899-0f4fb3d6a505" />

Funcionalidades Principais



O Bonsai oferece um conjunto abrangente de ferramentas para modelagem BIM, incluindo:







Criação e Edição de Elementos BIM: Permite criar e editar elementos BIM como paredes, lajes, portas, janelas, colunas e vigas, atribuindo-lhes propriedades IFC relevantes.



Compatibilidade IFC: Suporta a importação e exportação de arquivos IFC, garantindo a interoperabilidade com outros softwares BIM.



Visualização e Navegação BIM: Oferece ferramentas de visualização e navegação otimizadas para modelos BIM, incluindo seções, cortes e vistas 3D.



Gerenciamento de Informações BIM: Facilita o gerenciamento de informações BIM, como propriedades de elementos, classificações e relações.



Integração com IfcOpenShell: Utiliza o motor IfcOpenShell para garantir a precisão e a conformidade com o padrão IFC.



Fluxo de Trabalho Integrado: Permite combinar modelagem BIM com as capacidades de modelagem orgânica e visualização do Blender.



Vantagens do Uso do Bonsai



A utilização do Bonsai oferece diversas vantagens em relação a outras soluções BIM:







Custo: Sendo um add-on gratuito e open-source, o Bonsai elimina os custos de licenciamento associados a softwares BIM proprietários.



Flexibilidade: O Blender oferece uma flexibilidade incomparável em termos de modelagem, visualização e personalização, permitindo a criação de projetos complexos e inovadores.



Integração: O Bonsai integra-se perfeitamente com o ecossistema do Blender, permitindo o uso de outros add-ons e ferramentas para otimizar o fluxo de trabalho.



Comunidade: O Blender possui uma comunidade ativa e engajada, oferecendo suporte, tutoriais e recursos para usuários do Bonsai.



Personalização: Sendo open-source, o Bonsai pode ser personalizado e adaptado às necessidades específicas de cada projeto.



Curva de Aprendizagem: Para usuários já familiarizados com o Blender, a curva de aprendizado do Bonsai é relativamente suave, permitindo uma rápida adoção da ferramenta.



Instalação e Configuração



A instalação do Bonsai é simples e direta:







Download: Baixe o add-on Bonsai no site oficial ou no repositório GitHub.



Instalação no Blender: No Blender, vá em Edit > Preferences > Add-ons e clique em Install. Selecione o arquivo ZIP do Bonsai e clique em Install Add-on.



Ativação: Na lista de add-ons, procure por "Bonsai" e marque a caixa para ativá-lo.



Após a instalação, o Bonsai estará disponível no painel lateral do Blender, oferecendo acesso a todas as suas funcionalidades.



Fluxo de Trabalho Típico



Um fluxo de trabalho típico com o Bonsai envolve as seguintes etapas:







Criação do Projeto: Crie um novo projeto no Blender e configure as unidades e as configurações do projeto.



Modelagem BIM: Utilize as ferramentas do Bonsai para criar e editar elementos BIM, atribuindo-lhes propriedades IFC relevantes.



Importação de Arquivos IFC: Importe arquivos IFC existentes para integrar modelos de diferentes disciplinas.



Visualização e Análise: Utilize as ferramentas de visualização e análise do Bonsai para explorar o modelo BIM e identificar problemas.



Documentação: Gere documentação do projeto, como plantas, cortes e elevações, a partir do modelo BIM.



Exportação IFC: Exporte o modelo BIM para o formato IFC para compartilhar com outros softwares BIM.



Exemplos de Uso



O Bonsai pode ser utilizado em uma variedade de projetos, incluindo:







Projetos Arquitetônicos: Modelagem de edifícios residenciais, comerciais e institucionais.



Projetos de Engenharia: Modelagem de estruturas, instalações e infraestrutura.



Projetos de Construção: Planejamento e gerenciamento da construção.

<img width="1920" height="1055" alt="Pasted image 20250911115727" src="https://github.com/user-attachments/assets/84acd62b-60b5-4a12-823b-fbd496c29311" />


Reabilitação e Restauração: Modelagem de edifícios existentes para fins de reabilitação e restauração.



Considerações Finais



O Bonsai representa uma alternativa promissora aos softwares BIM proprietários, oferecendo uma solução gratuita, flexível e integrada para modelagem BIM no Blender. Com sua compatibilidade com o padrão IFC e sua integração com o ecossistema do Blender, o Bonsai permite que profissionais AEC criem projetos complexos e inovadores de forma eficiente e colaborativa. A contínua evolução do Bonsai, impulsionada pela comunidade open-source, promete adicionar ainda mais funcionalidades e melhorias no futuro, consolidando-o como uma ferramenta essencial para a modelagem BIM.


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

