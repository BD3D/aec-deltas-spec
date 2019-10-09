![AEC_DELTA](https://user-images.githubusercontent.com/3008807/56821254-b6c66c00-6845-11e9-908d-b2f4c6bc68ec.jpg)

# AEC Deltas Specification

AEC Delta Mobility is an Innovate UK funded project under the [Increase productivity, performance and quality in UK construction](https://apply-for-innovation-funding.service.gov.uk/competition/203/overview#scope) grant No. 104799 as part of £12.5 million public contribution from the [Industrial Strategy Challenge Fund](https://www.gov.uk/government/news/ai-and-digital-design-to-transform-future-of-uk-construction).

[![Dr Al Fisher explains the AEC Deltas project](https://user-images.githubusercontent.com/3008807/62527154-87ef6700-b832-11e9-814f-9c951e797957.png)](https://www.youtube.com/watch?v=ogfyzbeEZvc "Dr Al Fisher explains the AEC Deltas project")
British Information Modelling June 2019 Al Fisher - BuroHappold

## Description
The aim of this project is to engage manufacturing in the earliest possible stages of design by streamlining data workflow from consultants to factory. This is currently difficult due to proprietary file formats and commercial vendor lock-in causing significant overheads especially in design for manufacturing. Even though open standards such as IFC, COINS and BCF paved the way for collaboration, they are neither suitable for manufacturing nor scalable to large architectural and infrastructure projects. IFC, for instance, requires enormous amounts of memory to process (a single 1GB IFC file will easily consume 32GB of RAM over several hours of processing on a powerful server), not to mention inconsistent support across different applications. To address such shortcomings, this project is developing a novel open source micro-services web framework that will enable the industry to exchange individual object-level changes across various applications regardless of the underlying data format. Instead of exporting a whole file, our aim is to stream individual design changes (a.k.a. deltas) to whichever application is conformant with our newly proposed “AEC Delta Mobility” specification.
 
 ![aec-deltas](https://user-images.githubusercontent.com/3008807/53182999-77379580-35f2-11e9-93e5-98086647c0bf.png)
 
To achieve this we are going to:
1. Define a new common delta interchange schema that is open and shared across various systems, 
2. Specify a new REST API micro-services layer so that different AEC applications can communicate easily, and 
3. Validate the proposed specification by creating a working reference implementation that connects open source Speckle Works and 3D Repo with proprietary systems. This will cover the basis of CRUD commands, i.e. Create, Read, Update and Delete with the addition of a built-in security specification to ensure encrypted data transmission but also verification of authorship. 

This new and open ecosystem is a collaboration between the most famous and internationally renowned architectural and engineering practices with the standardisation support from [Building Smart International](https://www.buildingsmart.org) and the [UK BIM Alliance](http://www.ukbimalliance.org). The project will deliver an open specification and an open source reference implementation but also support further development of paid for services that will drive adoption, commercialisation and long-term support. Ultimately, our unique approach is expected to streamline the design processes for manufacturing, reduce delays and thus directly increase productivity on a wide variety of multidisciplinary projects. Such a solution will help engage manufacturers in the early design stages resulting in increased pre-manufactured value of build assets across the sector.

## Project Partners
* [BuroHappold Engineering](https://www.burohappold.com) - [BHoM](https://bhom.xyz)
* [3D Repo](https://3drepo.com)
* [Speckle Works](https://speckle.works)
* [UCL Bartlett School of Construction and Project Management](https://www.ucl.ac.uk/bartlett/construction/)
* [Rhomberg Sersa Rail Group (UK)](https://rhomberg-sersa.com)

## Events

* 20 March 2019 - [7th British Information Modelling](https://3drepo.com/british-information-modelling-march-2019/) at TOG King's Cross, London, UK
* 30 April 2019 - [The Future of Design Collaboration](https://3drepo.com/event-the-future-of-design-collaboration/) at BuroHappold, London, UK
* 24 June 2019 - IFC Revision Meetup at HOK, London, UK
* 25 June 2019 - [8th British Information Modelling](https://www.eventbrite.co.uk/e/3d-repo-british-information-modelling-june-2019-tickets-60297667948) at Bryden Wood, London, UK
* 26-28 July 2019 - [Web3D 2019](http://web3d2019.web3d.org/) at Hotel Indigo, Los Angeles, US
* 8 October 2019 - 9th British Information Modelling at Crypt on the Green, London, UK
* 16-17 October 2019 - [Digital Construction Week](https://www.digitalconstructionweek.com/) at Excel, London, UK

## Project Pages
* [Software Requirements](https://github.com/aecdeltas/aec-deltas-spec/wiki/Software-Requirements)
* [Delta Specification](https://github.com/aecdeltas/aec-deltas-spec/wiki/Delta-Specification)
* [Comparison between Speckle Diff API Endpoint & AEC∆ Spec](https://github.com/aecdeltas/aec-deltas-spec/wiki/Comparison-between-Speckle-Diff-API-Endpoint-&-AEC%E2%88%86-Spec)

# License
This project is Copyright of respective project partners, and is released under the open source MIT license. All contributors are required to sign either the Individual or the Entity Contributor License Agreement (CLA).

# Contributing
We very much encourage contributions to the AEC Deltas project. 

We are currently in the User Requirements gathering stage. Please contribute any requirements, suggestions, etc. into the Wiki section here: https://github.com/aecdeltas/aec-deltas-spec/wiki 

For code contributions, fork the desired repository and commit your modifications there. Once happy with the changes, you can generate a pull request and our team will integrate it upstream after a review.

Your pull requests should:
1. Follow the style of the existing code
2. One commit should just do one thing, and one thing only
3. Rebase your branch against upstream's master so that we don't pull redundant commits
4. Sign our Individual CLA or if you are representing a legal entity, sign the Entity CLA

## Contact
If you need any help or want to contribute please contact: deltas.internal@3drepo.org We look forward to hearing from you.
