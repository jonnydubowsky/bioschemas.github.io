## BioChemEntity specification v. 0.1 

**Type** 

Thing > BioChemEntity

**Bioschemas specification describing a physical entity.** 

# Description 
A BioChemEntity is any object that exists in the physical world and cannot be better represented with any other existing type in schema.org. In order to specify the nature of this physical entity, additionalProperty must be used to specify the nature/type of this physical entity. For instance, http://semanticscience.org/resource/SIO_010043 can be used to refer to a protein.

Bioschemas usage

A BioChemEntity is a flexible and extensible wrapper for Life Sciences entities. Representations of physical entities in Life Sciences are usually recorded in datasets; the link to a dataset should be done via properties. A particular Life Sciences entity, refer to as a profile in Bioschemas, will customize BioChemEntity by modifying the marginality, cardinality and ontologies used. For instance, a protein profile would recommend pointing to an organism a part of the minimum information, but not necessarily to a sample or disease. 
# Links 
- [Specification](http://bioschemas.org/bsc_specs/BioChemEntity/specification/)
- [Specification source](specification.html)
- [Mapping Spreadsheet](https://docs.google.com/spreadsheets/d/1e_8LUQ4GYxar0-gotOXsbAUVUQkvF6GNuBdr54hbcdc/edit?usp=drivesdk)
- [Coding Examples](https://github.com/BioSchemas/specifications/tree/master/BioChemEntity/examples)
- [GitHUb Issues](https://github.com/BioSchemas/bioschemas/labels/type%3A%20BioChemEntity)
> These files were generated using [map2model](https://github.com/BioSchemas/map2model) Python Module.