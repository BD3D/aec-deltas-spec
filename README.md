# AEC Deltas Specification

AEC Delta Mobility is an Innovate UK funded project under the [Increase productivity, performance and quality in UK construction](https://apply-for-innovation-funding.service.gov.uk/competition/203/overview#scope) grant No. 104799 as part of £12.5 million public contribution from the [Industrial Strategy Challenge Fund](https://www.gov.uk/government/news/ai-and-digital-design-to-transform-future-of-uk-construction).

## Description
The aim of this project is to engage manufacturing in the earliest possible stages of design by streamlining data workflow from consultants to factory. This is currently difficult due to proprietary file formats and commercial vendor lock-in causing significant overheads especially in design for manufacturing. Even though open standards such as IFC, COINS and BCF paved the way for collaboration, they are neither suitable for manufacturing nor scalable to large architectural and infrastructure projects. IFC, for instance, requires enormous amounts of memory to process (a single 1GB IFC file will easily consume 32GB of RAM over several hours of processing on a powerful server), not to mention inconsistent support across different applications. To address such shortcomings, this project is developing a novel open source micro-services web framework that will enable the industry to exchange individual object-level changes across various applications regardless of the underlying data format. Instead of exporting a whole file, our aim is to stream individual design changes (a.k.a. deltas) to whichever application is conformant with our newly proposed “AEC Delta Mobility” specification.
 
To achieve this we are going to:
1. Define a new common delta interchange schema that is open and shared across various systems, 
2. Specify a new REST API micro-services layer so that different AEC applications can communicate easily, and 
3. Validate the proposed specification by creating a working reference implementation that connects open source Speckle Works and 3D Repo with proprietary systems. This will cover the basis of CRUD commands, i.e. Create, Read, Update and Delete with the addition of a built-in security specification to ensure encrypted data transmission but also verification of authorship. 

This new and open ecosystem is a collaboration between the most famous and internationally renowned architectural and engineering practices with the standardisation support from [Building Smart International](https://www.buildingsmart.org) and the [UK BIM Alliance](http://www.ukbimalliance.org). The project will deliver an open specification and an open source reference implementation but also support further development of paid for services that will drive adoption, commercialisation and long-term support. Ultimately, our unique approach is expected to streamline the design processes for manufacturing, reduce delays and thus directly increase productivity on a wide variety of multidisciplinary projects. Such a solution will help engage manufacturers in the early design stages resulting in increased pre-manufactured value of build assets across the sector.

## Project Partners
* [BuroHappold Engineering](https://www.burohappold.com)
* [3D Repo](https://3drepo.com)
* [Speckle Works](https://speckle.works)
* [UCL Bartlett School of Construction and Project Management](https://www.ucl.ac.uk/bartlett/construction/)
* [Rhomberg Sersa Rail Group (UK)](https://rhomberg-sersa.com)

