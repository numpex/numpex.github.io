---
type: landing

sections:
- block: hero
  content:
    title: NumPEx
    image:
      filename: NumPEx.jpg
    cta:
      label: "Orap Presentations"
      url: http://orap.irisa.fr/49ieme-forum-le-pepr-numpex/
      icon_pack: fas
      icon: file-pdf
    cta_alt:
      label: "NumPEx on Github"
      url: https://github.com/numpex
    text: |-
      High Performance Numerics for the Exascale
      <div class="mb-4"></div>
    cta_note:
      label: |-
        - **CEA**: Jérôme Bobin
        - **CNRS**: Michel Daydé
        - **Inria**: Jean-Yves Berthou
        <div class="mb-3"></div>
        Find our <a href='#appel-a-demonstrateurs'>call for demonstrators</a>.
  design:
    background:
      gradient_start: '#556688'
      gradient_end: '#334477'
      text_color_light: true
- block: markdown
  content:
    text: |-
      NumPEx is a PEPR (Programme et Équipement Prioritaire de Recherche) on the Exascale, financed by the [France2030](https://www.economie.gouv.fr/france-2030#) investment program.
      
      Acces the slides of NumPEx presented at the [49th Orap Forum](http://orap.irisa.fr/49ieme-forum-le-pepr-numpex/).


      Access a general [presentation](/NumPEx_PresentationGenerale_20230117.pdf)

      NumPEx has a gloabl budget of 41.8 million euros, and is made up of 5 target projects covering the complete spectrum of the Exascale software stack.


      NumPEx has a gloabl budget of 41.8 million euros, and is made up of 5 targeted projects covering the complete spectrum of the Exascale software stack.

      The French Exascale program NumPEx aims at designing and developing the software components that will equip future exascale machines and  preparing the major scientific and industrial application domains to fully exploit the capabilities of these machines. NumPEx will therefore contribute to the Jules Verne consortium response to the next EuroHPC call for expressions of interest (AMI), with a view to hosting and operating at TGCC one of the two European exascale machines planned in Europe by 2025. The NUMPEX program contributes to the constitution of a set of tools, software, applications and also sovereign training that will allow France to remain one of the leaders in the field by developing a national Exascale ecosystem coordinated with the European strategy and to allow Europe to be in the forefront of the international competition.
      
      The NumPEx program	(2023-2028) has a budget of 40,8 M€ over 5 years. It is structured around 5 integrated projects:
          • ExaMA, Algorithms and numerical: design and development of next-generation scalable algorithms, numerical methods for high performance numerical (computing, AI, data processing) ; 
          • Exa-Soft, Computation-oriented software and libraries: design and development of software, libraries and tools dedicated to massive, accelerated and heterogeneous parallelism by coupling HPC, HPDA and AI approaches;
          • ExaDoST, Data-oriented tools and software: design and development of software solutions for data processing and analysis and the use of artificial intelligence in HPC environments;
          • ExaAToW, end-to-end complex workflows: management of large scale workflows composed of HPDA, AI, and HPC tasks that are distributed over the Exascale, HPC, and Data infrastructures.
          • ExaDIP, as a transverse activity of co-design and software productivity: co-design of strategic application demonstrators, development of representative proxy-apps and mini-apps,  design of modern agile software development methodologies and frameworks for the production of software development kits
      The production of NumPEx software will leverage several decades of publicly funded French research and European and international efforts. To cite a few, some of the software, libraries, packages on which NumPEx software stack will be built are already well recognized and deployed: Scikit Learn, Pytorch, NetCDF, PDI, SIONlib, MUMPS, PETSc, Pleiades, Croco, Manta, Uranie, OpenTurns,  Hwloc, StarPU,  PAPI, Perf, PowerAPI,  Damaris., PaDaWan, (TBC).

      **ExaMA project.** The ExaMA project aims to (i) develop scalable numerical methods, algorithms, and implementations that, taking advantage of the exascale architectures, empower modeling, solving, assimilating model and data, optimizing and quantifying uncertainty, at levels that are unreachable at present; (ii) develop and contribute to software and toolbox libraries allowing to assemble specific critical reusable components, hiding the hardware complexity and exposing only the specific methodological interface (iii} to identify and co-design Methodological and Algorithmic Patterns at exascale that can be reused efficiently in large scale applications (eg in weather and climate forecasting and other societal, industrial and scientific challenges); (iv) to enable AI algorithms to reach Exascale performance, exploiting the methods from (i) and the libraries from (ii); and (iv) to provide demonstrators through mini-apps and proxy-apps that will be openly available and benchmarked on exascale systems.

      **ExaSoft project.** The ExaSoft project aims at consolidating the European Exascale software ecosystem by providing a coherent, exascale-ready software stack enabling HPC applications to efficiently exploit heterogeneous supercomputers featuring heavily accelerated compute nodes. The project will achieve breakthrough research advances in programming languages and models, code optimization, runtime systems, performance profiling and analysis, and numerical libraries to address major scientific challenges such as scalability, performance portability, heterogeneity, resilience and energy efficiency.  Many members of ExaSoft are deeply involved in the Joint Lab for Extreme-Scale Computing initiative (https://jlesc.github.io), which will ensure strong collaborations with European, Japanese and American exascale research projects.


      **ExaDoST project.** The ExaDoST project will address scalable storage and I/O, scalable in situ processing and scalable AI-analytics for complex hybrid, distributed workflows combining simulation, data processing and AI. While such challenges are now well identified at international level, ExaDoST will specifically build operational solutions based on European software technologies with high technology readiness levels, co-designed and validated with representative European applications (aiming to support, in particular, specific scenarios from the SKA research infrastructure). To ensure European needs are consistently taken into account in the roadmaps for building the data-oriented Exascale software stack, experimentation and validation on the most advanced infrastructure that will be made available by the Exascale supercomputer proposed by the Jules Verne consortium will be highly instrumental.

      **ExaAToW project.** The solution proposed by the Jules Verne consortium will ambition to embed the Exascale supercomputer inside a growing scientific datasphere spanning from edge devices to sovereign HPC systems. The Exa-AToW project aims at providing solutions for the efficient management of large scale workflows composed of HPDA, AI, and HPC tasks that are distributed over the Exascale, HPC, and Data infrastructures. ExaAToW focuses on effective end-to-end solutions, at scale, by considering not only functional dimensions such as workflows and data logistics but also resource federation governance, cybersecurity, energy, and sustainability. ExaAToW will build strong collaborations with major EU partners (Helmholtz, FZJ) and projects (eFlows4HPC). Furthermore, at a worldwide level, a continuation of the BDEC initiative (https://exascale.org/) will be led by the NumPEx program. 

      **ExaDIP project.** The ambition of the Jules Verne consortium is to deliver a capable exascale system integrating strategic exascale Computational Science and Engineering (CSE) applications and software technology innovations to address new science discoveries and critical challenges. The ExaDIP project focuses on an iterative participatory process — referred as a co-design process —  supported by a Computational and Data Team (CDT, evaluated at 70 FTEs, 6100 k€, for the 5 year duration of the program) and that defines and takes steps toward a new exascale software ecosystem driven by strategic CSE application demonstrators — some of them already identified as flagship codes for exascale in EuroHPC CoEs such as Excellerat, ChEESE, Hidalgo, MAX -- and cross-cutting algorithmic computational and communication patterns. This process emphasizes the adoption of modern agile software development methodologies, high-quality software components and frameworks that can be integrated and delivered in the form of Software Development Kits to accelerate the production of an Exascale software stack and the composition of next-generation sustainable CSE applications, improving software productivity and performance portability at an Exascale level. The ExaDIP co-design strategy introduces an intermediate application-driven aggregation layer and an important organisational and coordinating structure that should serve well the execution phase and reduce the overall complexity of the Jules Verne project. With that objective, we plan to develop strong synergies between the Computational and Data team (CDT) of the ExaDIP project and the pool of AST (application Support Team) proposed by the Jules Verne consortium. 

  design: { columns: '1' }
- block: markdown
  title: "targeted projects"
  content:
    text: |-
      # <a id='projets-cibles'></a>Targeted projects
      ```markmap {height="15rem"}
      - NumPEx
        - **ExaMA**: Methods and Algorithms for Exascale
          - Hélène Barucq
          - Christophe Prud’homme
        - **ExaSofT**: HPC software and tools
          - Alfredo Buttari
          - Raymond Namyst
        - **ExaDoST**:  Data-oriented Software and Tools for the Exascale
          - Gabriel Antoniu
          - Julien Bigot
        - **ExaAToW**: Architectures and Tools for Large-Scale Workflows
          - François Bodin
          - Mark Asch
          - Thierry Deutsch
        - **ExaDIP** Development and integration project
          - Valérie Brenner
          - Jean-Pierre Vilotte
      ```
- block: markdown
  content:
    title: "<a id='appel-a-demonstrateurs'></a>Call for Demonstrators"
    subtitle: "Join NumPEx by submitting to the call for application demonstrators."
    
    text: |-
     One of the objectives of NumPEx is to encourage synergies between research groups and application domains.

     The strategy adopted is one of co-design of software solutions associated with algorithmic motifs of computation and communication, and their integration to accelerate the development of application demonstrators.
     
     NumPEx will coordinate and finance the co-design strategy, with the application demonstrators, by a compute and data team (CDT) at the interface between research and application groups. An application demonstrator will be the result of a conjoint effort of the NumPEx teams and the application development teams.
      
      Applications can be submitted by filling in the [“Application Demonstrator” form](/AplicationDemonstrators-AD-form.docx) and sending them to
    
      - Jean-Pierre Vilotte: vilotte@ipgp.fr 
      - Valérie Brenner: valerie.brenner@cea.fr 
      - Mark Asch: mark.asch@u-picardie.fr
      - Jérôme Bobin: jerome.bobin@cea.fr
- block: markdown
  content:
    title: "<a id='jobs'></a>Jobs"
    subtitle: "From PhDs to Research Fellows."
    
    text: |-
      We will have a large number of openings, starting from September 2023, with the possibility of earlier dates. Each targeted project will publish calls for candidates.
      - ExaMA
      - ExaSoft
      - ExaDoST
      - ExaAToW
      - ExaDIP: 

        - we are seeking at least 5 candidates for our Compute and Data Team (CDT)
        - the positions are for 2 to 5 years, with remuneration as a function of experience
        - location: Paris, Bordeaux, Grenoble
        - the profiles we seek begin from Postdoc level (directly after a PhD), and extend to candidates with 3 to 5 years experience after their PhD
        - the positions involve working on co-design projects, combining upstream research performed in NumPEx's other target projects, with application development teams (see the call for Application Demonstrators above)

        - Contacts: (Mark Asch) mark.asch@u-picardie.fr   and (Jean-Pierre Vilotte) vilotte@igp.fr
#design: { columns: '1' }
#- block: logos
#  content:
#    logo_folder: logos
#  design: { columns: '1' }
---

