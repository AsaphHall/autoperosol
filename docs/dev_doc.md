Content:
    Dev_Information:
        general informations
        BFO as Top Level Ontology
        Reuse of existing ontologies
        relations & RO
        Definitions
        ODK Workflow
        Documentation
        Nomad
    Classes/Processes:
        Spin Coating
        Maximum Power Point Tracking
        IV Measurement
        Time correlated single photon counting
        Electroluminescence Imaging
        Photoluminescence Imaging
        Slot die Coating
        Solar Cell
        Layer
        JV Analysis
        Annealing/Hotplate Annealing


# 1
TFSCO

# 2 BFO as Top-Level-Ontology

When creating a schema one should aim to implement an existing structure. For the TFSCO we choose the Basic Formal Ontology (BFO/LINK) as the Top-Level-Ontology. Within the BFO everything is classified as either a process or a continuant.

# 3 Reuse of existing Ontologies

When creating classes and properties one should aim to reuse existing classes if possible. Therefore the TFSCO reuses classes from a variety of existing Ontologies. To get an overview over the imported classes and the ontologies, from which these classes are imported from check the imports-folder.

# 4 The ODK Workflow

It is important to keep the imports up-to-date and recognize changes in imported ontologies. The Ontology Development Kit (ODK) is a tool that helps you with creating a ____ workflow. It allows to import and update classes from existing ontologies, creates a clear directory structure and enables quality control. Further information on the Ontology Development Kit, the odkrunner, and a documentation of the implemented workflows can be found at ________.

ODK
-https://incatools.github.io/ontology-development-kit/
-https://github.com/INCATools/odkrunner