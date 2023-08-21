# What is a cell type? 

By Tiago Lubiana 
tiago.lubiana.alves@usp.br

A chronological collection of the core scientific articles discussing the concept of cell type, cell state, and similar concepts.

Comments on each publication reflect my own summarized view on each piece. Some might be longer, some might be shorter. I'll try to keep them to 1-3 paragraphs.
Longer analyses might be factored out in their own documents. 

I have some focus on categorizing cell types for understanding human biology in the context of the Human Cell Atlas, but considerations across species might be present nevertheless.

If you have additional articles that you think should be featured, just add an issue! 

Citations are added in Vancouver style to preserve fine-grained publication dates.

# 2020s

## 2023 
### Fleck JS, Camp JG, Treutlein B. [What is a cell type? A next step for cell atlases should be to chart perturbations in human model systems.](https://doi.org/10.1126/science.adf6162.) Science. 2023 Aug 17;381(6659):733-734. DOI: 

This Perspective on Science disappointed me a bit, as it speaks very little about cell-type definitions. Feeding largely on the single-cell RNA-seq communities, the article skims the cell type x cell state framework and largely ignores all prior literature on what a cell type is. It is not a bad article, though, it discusses in technical detail the importance of experimental perturbations when charting cell atlases, as well as the need for multimodality phenotyping. It is just not about what a cell type is, and the title seems, unfortunately, a bit like a clickbait.


### Domcke S, Shendure J. [A reference cell tree will serve science better than a reference cell atlas](https://doi.org/10.1016/j.cell.2023.02.016). Cell. 2023 Mar 16;186(6):1103-14. 

A pledge for an ontogenetic tree as the reference for classifying cell types. It brings exciting points of view but misses essential literature such as [Jeff Doyle's "Cell types as species: Exploring a metaphor"](https://doi.org/10.3389/fpls.2022.868565) and the whole Cell Ontology endeavor. It extends the ontogenetic classification of *C. elegans* to other organisms, but requires critical technical advances before applying to humans.


## 2022 

### Doyle JJ. [Cell types as species: Exploring a metaphor.](https://doi.org/10.3389/fpls.2022.868565) Frontiers in Plant Science. 2022 Aug 22;13:868565.

An in-depth dissection of the analogy between organizing cells in types and organizing individual organisms in species. For different facets, such as "Philosophical underpinnings', Jeff Doyle explores the cell type side and the species side, finalizing with synthesis and outstanding questions. With an impressive coverage of the literature and the clarity of the writing, the article is a must-read and, in my opinion, under-discussed in the human cell type community.  

### Zeng H. [What is a cell type and how to define it?.](https://doi.org/10.1016/j.cell.2022.06.031) Cell. 2022 Jul 21;185(15):2739-55.

This review by Hongkui Zeng got a lot of attention, but it is not exactly about what a cell type is. It is mostly concerned with how to set boundaries for *each cell type* and how one goes about defining each of these classes. These two ideas are mixed in a relatively confusing way throughout the text. I wrote a small blog post about it back then called '[The vast gap between defining “cell type” and defining a cell type](https://pointstodots.wordpress.com/2022/07/25/the-vast-gap-between-defining-cell-type-and-defining-a-cell-type/)'. Also, in figure 2, Zeng forces a single-hierarchy tree to organize cell types, a common attempt, but there is no core, natural reason why cells should form a single hierarchical classification. 
The review is nevertheless quite good a read, it focuses on the mammalian brain and discusses the role of transcriptomics, morphology, and connectivity for crafting definitions for each cell type and covers much of the literature. It also mentions the cell types versus cell states, defining cell state as "a transient or dynamically responsive property of a cell to a context" and that each cell type may have many states.  It does miss discussing the Cell Ontology endeavor, unfortunately. 

## 2021

### Almeida N, Chung MW, Drudi EM, Engquist EN, Hamrud E, Isaacson A, Tsang VS, Watt FM, Spagnoli FM. [Employing core regulatory circuits to define cell identity.](https://doi.org/10.15252/embj.2020106785) The EMBO Journal. 2021 May 17;40(10):e106785.

Nathalia Almeida (a fellow Brazilian) and colleagues provide a nice summary of the transcription-factor centered perspective of cell identity. Drawing on Hobert's Terminal Selectors, the text focuses on core regulatory circuitry (CRCs), comprised of "core TFs and their interconnected auto-regulatory loops", exemplified with the Pbx1 gene, a terminal selector for some dopaminergic neurons and CRC genes in the pancreas. Naturally, Almeida discusses Arendt's Core Regulatory Complexes, which introduces an element of physical cooperativity of TFs. The article discusses the processes by which CRCs can be uncovered through scRNA-seq and epigenomics techniques, as well as the technical limitations. Notably, presents the focus on core transcription factors as as way to improve cell type assignment as "a given cell is expected to show a unique set of TFs regardless of its state, which would help to distinguish between cell types and cell states". 

### Bernstein, MN.  [On cell types and cell states](https://mbernste.github.io/posts/cell_types_cell_states/)  - Blog. 2021 Mar 03

Very interesting blogpost, with a computer-science oriented mindset and graph representations. Talks about "*cell types are a subset of cell states*" in a state space, meaning that "each cell type is a subset of the *total set* of states". Bernstein is talking about a particular cell and its states alongside its life cycle. Then, in the final part, he proceeds to define the concept across different individuals, by considering their set of states as *two disconnected, and approximately isomorphic subgraphs*. Bernstein has an all-inclusive view of cell type, where any arbitrary collection of cell states could be called a "cell type", a perspective I shared on a 2021 preprint called ["Towards a pragmatic definition of cell type"](https://www.authorea.com/users/384178/articles/501068-towards-a-pragmatic-definition-of-cell-type). I've been changing my mind, however, and preferring the term "cell class" for that idea, as the *term* cell type is probably better reserved for a particular kind of class with some characteristics, such as stable properties. 

I also think that we should *not* create millions of classes and instead think about which classes are useful. That is important from the pragmatic standing point of computational ontologies, prized by Bernstein. His description implicitly considers that the Cell Ontology (or some other cell ontology) should represent disease states, which is currently not done (July 2023). 

## 2020 

### Miller JA, Gouwens NW, Tasic B, Collman F, van Velthoven CT, Bakken TE, Hawrylycz MJ, Zeng H, Lein ES, Bernard A. [Common cell type nomenclature for the mammalian brain.](https://doi.org/10.7554/eLife.59928) Elife. 2020 Dec 29;9:e59928.

 
Jeremy Miller and colleagues at the Allen Institute discuss some of the practical  challenges in organizing cell types in single-cell transcriptomics. States the need for *(1) standard nomenclature and (2) centralized and standardized infrastructure associated with cell type classification.*  It presents the *common cell type nomenclature (CCN), for matching and tracking cell types across studies.*.Two definitions are of special note: *Cell set:	Any tagged group of cells in a taxonomy.* and *Provisional cell type: (...) a specific example of a cell set that is of high importance*.  
They contextualize the CCN with OBO Foundry ontologies and knowledge graphs and claims for a *cell type standards governing body* similar to the HUGO Gene Nomenclature Committee (HGNC). Such a body would be responsible for *controlled vocabulary for assigning cell type nomenclature* and defining *a process for submission to ensure that critical data and metadata can be stored in a robust database"*. As a note, the Cell Ontology and the cellxgene database *de facto* play some of those roles today, but maybe a scientific standards body could help on tying up all the bits together. 


### Fishell G, Kepecs A. Interneuron types as attractors and controllers. [Annual review of neuroscience.](https://doi.org/10.1146/annurev-neuro-070918-050421) 2020 Jul 8;43:1-30.

In this continuation to 2014's "[Interneuron cell types are fit to function.](https://doi.org/10.1038/nature12983)", Fishell and Kepecs this time base their propositions on "attractor states" arguing that *subtype identity is generated using a configurational (rather than combinatorial) code of transcription factors* and analyzing evidence that *combinations of TFs can initialize but not realize cell fates*. They trace back the attractor concept to Waddington's work and argue that there is a translation of *Waddington's concepts of chreods (canalized paths of development) to trajectories and homeorhesis (the tendency to return to a path) to attractor states.* 

They discuss Hobert 2016's concept of terminal selectors but somehow miss Detlev Arendt's Core Regulatory Complexes (see  "[The origin and evolution of cell types](https://doi.org/10.1038/nrg.2016.127)"). They advance on the idea of *cardinal interneuron types*, now in the context of single-cell transcriptomics.  They also discuss the role of interneurons in modulating circuits and the varieties that *specialize in targeting distinct pyramidal cell domains or compartments*.

The section 3, they divide the generation of diversity in 3 categories, worth copying in full: *(a) Cardinal specification (nature) occurs when interneurons become postmitotic and define their intrinsic properties; (b) definitive specification (nurture) relies on cues imposed during migration and at the settling position and determines local afferent and efferent connectivity; and (c) state specification (circumstance) transpires when some interneuron subtypes change their gene expression in the context-specific brain activity.* This theoretical model goes beyond just the type-state duality and introduces a third dimension in the mix. The cardinal type, natural and intrinsic, alongside subtyping guided by orchestrated factors and complemented by local, transitive changes in expression in particular contexts.  

They don't fix an absolute number of cardinal classes but talk about *the four largest cardinal classes*, PV, SST, VIP, and Lamp5 expressing interneurons, and other minor cardinal classes, still under discussion. 

They start to contextualize the diversity of interneuron types during evolution, but the session is relatively short. An interesting statement is that *interneuron diversity is clearly very old. Turtles diverged from mammals approximately 320 million years ago, and yet these cell types have been maintained in surprisingly conserved form*.  

# 2010's

## 2019 
### Morris SA. [The evolving concept of cell identity in the single cell era.](https://doi.org/10.1242/dev.169748) Development. 2019 Jun 15;146(12):dev169748.

A discussion of cell identity around 3 pillars: (1) phenotype and function as a central pillar, (2) lineage as a second dimension for full characterization and (3) state as the range of flexible sub-phenotypes a given identity can acquire. In this work, cell identity and cell type are treated as synonyms. Deals with cell types/identities as 'hard-wired' but reprogrammable and cell states as 'softwired'. 

I like Samantha's consideration that  *cluster-specific gene expression is used to infer cell type, representing an initial prediction of identity that must be orthogonally validated*. This is often forgotten in large-scale transcriptomics study. 

### Bates AS, Janssens J, Jefferis GS, Aerts S. [Neuronal cell types in the fly: single-cell anatomy meets single-cell genomics.](https://doi.org/10.1016/j.conb.2018.12.012) Current opinion in neurobiology. 2019 Jun 1;56:125-34.

Even though Bates and colleagues focus on the fly brain, many concepts are relevant for the more general task of deciding on what a cell type is. They talk about the consistency of scRNA-seq clusters, how genetic lines connect RNA profiles to morphology and how the body of techniques make "a full Drosophila neuronal parts list imminent". The article explicitly states that types are *"the reproducible product of definable genomic regulatory programs active during development"*. It uses the reproductive isolation criteria, a "a thought experiment that calibrates definitions based on
other measures,", to state a similar hypothesis for neuroscience: *"Neurons of a type can be consistently identified across individuals but not consistently subdivided within individuals."*. I personally think it is an interesting toy model, but it does miss the state vs type discussion and leaves too much room for too granular cell types.  Anyways, the article also discusses two purpose of cell type classification: to simplify reasoning and facilitate scientific communication. This extends a bit the list of purposes put forth by Zeng and Sanes 2017. 




### Xia B, Yanai I. [A periodic table of cell types.](https://doi.org/10.1242/dev.169854) Development. 2019 Jun 15;146(12):dev169854.

Taking advantage of 2019 as UNESCO's International Year of the Periodic Table, the authors explore the analogies between the periodic table of elements and the classification of cell types. They propose "cell types and cell fate transitions in a species can be organized in an analogous manner in a ‘periodic table of cell types`". They divide the table in columns falling into a "stem-cell phase", a "differentiation phase" and a "differentiated phase". They  focus on species-specific classifications and suggest starting with a periodic table of *C. elegans* before pursuing the *Homo sapiens* table. In my opinion, even though they take stretch the metaphor a bit too thin (as there is no actual _periodicity_, just parallelisms), they do provide interesting perspectives, such as the framing of species-specific catalogs and the different developmental categories.  

## 2017

### Zeng H, Sanes JR. [Neuronal cell-type classification: challenges, opportunities and the path forward.](https://doi.org/10.1038/nrn.2017.85) Nature Reviews Neuroscience. 2017 Sep;18(9):530-46.

Hongkui Zeng and Joshua Sanes produced a fine, extensive review of the body of knowledge related to the classification of neurons in particular and cells in general. It states clearly 3 principles for cell type classification: the incorporation of multiple quantitative criteria, the use of discontinuous variation for definitions, and the need for a hierarchical system of representation. As a side note, Cell Ontology does all of that but has been missed by the authors. The review also nicely describes the *purposes* behind cell type classification, including reproducibility of experiments, targeted experimental genetic modifications (e.g. in mice), the discovery of new types, the study of disease, and the generation of the "parts list" of the human body. The article plays with the analogies with species classification and mentions explicitly how phenetic systematics might be the most useful species-oriented framework for organizing cell types.


This 
### Clevers H, Rafelski S, Elowitz M, Klein A, Shendure J, Trapnell C, Lein E, Lundberg E, Uhlen M, Martinez-Arias A, Sanes JR. [What is your conceptual definition of “cell type” in the context of a mature organism?.](https://doi.org/10.1016/j.cels.2017.03.006) Cell Systems. 2017 Mar 22;4(3):255-9.

An influential collection of perspectives on the nature of cell type, mostly by leading biomedical researchers, with brief statements. Discusses the perspectives on cell types x cell states, the role of function and the increasingly important role of transcriptomics as a ruler to divide cell types apart. A must read and re-read.  



## 2016 
### Arendt D, Musser JM, Baker CV, Bergman A, Cepko C, Erwin DH, Pavlicev M, Schlosser G, Widder S, Laubichler MD, Wagner GP. [The origin and evolution of cell types.](https://doi.org/10.1038/nrg.2016.127) Nature Reviews Genetics. 2016 Dec;17(12):744-57.

Detlev Arendt, an evolution researcher with a focus on the marine annelid *Platynereis dumerilii*, presents a thorough description of the notion of "cell type" in light of the evolution. The idea of a "Core Regulatory Complex (CoRC)" of transcription factors determining each cell type is very influential. Defines a cell type as ‘a set of cells in an organism that change in evolution together, partially independent of other cells, and are evolutionarily more closely related to each other than to other cells’. 
The article also includes an impressive [glossary](https://www.nature.com/articles/nrg.2016.127#Glos1), proposing definitions for many terms relevant to understanding the evolutionary definition of "cell type". Talks about cell types as fundamental evolutionary units (*Modular biological entities capable of evolving as a cohesive unit and at least partially independently of others*) similar to genes and species. 

The article discusses explicitly cell type *homology* across species via the sharing of conserved CoRCs. It also builds upon Oliver Hobert's notion of "terminal selectors", a set of transcription factors that establish and maintain postmitotic cell identity. Notably, it extends Owen's 1848 definition of homology to cell types, with a mechanistic explanation of  'same cell type regardless of form and function', with an example for muscle cells across species where *the CoRC from homologous cell types is conserved, whereas the phenotype of the cell is more flexible*. 

Arendt's article is a fantastic entry point to look at cells from an evolutionary perspective. The atlas-builders of today are usually interested in the current snapshot of cell types, in a fashion of evolution-stable account of cell types and their behaviours and humans. In many ways, atlas-builders are more interested in phenotype and function than in homology and history. Nevertheless, as the world is only one, having an evolutionary account of cell types is fundamental for efficiently organizing knowledge about cell types. 

### Hobert O. [Terminal selectors of neuronal identity.](https://doi.org/10.1016/bs.ctdb.2015.12.007) Current topics in developmental biology. 2016 Jan 1;116:455-75.

In this book chapter, Oliver Hobert explores the identities of neurons in *C. elegans*, an eutelic organism (fixed number of cells). Hobert looks at identity from a * “bottomup” angle* (...)  *development from the standpoint of the end product of neuronal development, asking how the terminal features of specific neuron types in a mature nervous system are genetically programmed.*. He discusses in depth his concept of "terminal selector", raised in 2008 and 2011, applied to transcription factors *that the behavioral phenotypes of these mutants match the phenotypic consequences of laser ablating these neuron types and they broadly affect many—if not all—known molecular markers*. These laser-ablation experiments are immensely informative, but somewhat restricted to simple organisms with very well-defined cell types. Hobert notes that the concept is an extension of an extension of the selector gene concept, by Garcia-Bellido (1975), *genes that define the identity of specific domains of a developing organism*. 

Hobert discusses in depth the molecular evidence in *C. elegans* for terminal selectors, highlighting the coregulation of terminal effector genes by some transcription factors, their influence on particular molecular circuits, and the combinatorial way these terminal selectors are expressed and repressed, giving rise to diversity. 
## 2015 

### Trapnell C. [Defining cell types and states with single-cell genomics.](https://doi.org/10.1101/gr.190595.115) Genome research. 2015 Oct 1;25(10):1491-8.

An early perspective of the impact of single-cell transcriptomics on the definition of "cell type" and the discovery of new cell classes. Discusses the technical advances from bulk techniques, and how that enables a fine-grained perspective on cell function; crucially discusses how incorrect grouping of samples might lead to *qualitatively incorrect* interpretations. Cole Trapnell considers also the perspective of pseudotime analysis (e.g. inferring directional time-based state changes from a static populational snapshot), a type of analysis he invented (or at least co-invented). He then goes on to discuss the technical aspects of scRNA-seq analysis and other single-cell omics. Waddington's developmental landscape and attractor basins/wells are constant topics throughout the article.

## 2014 

### Kepecs A, Fishell G. [Interneuron cell types are fit to function.](https://doi.org/10.1038/nature12983) Nature. 2014 Jan 16;505(7483):318-26.

A somewhat niche review focusing on interneurons, but provides insights into the larger classification of cell types. Provides a summarizing standpoint stating that they*the large diversity in interneuron classes may originate from a handful of cardinal cell types* (...) *with specific ground states.*.  I like the wording of *cardinal classes*, as it is precisely vague in stating that these classes are important, even in absolute, developmentally-determined nature. They bring the interesting perspective of a core parts-list of neurons, that is somewhat malleable and can be employed in different contexts. Or, as they say, *a limited set of building blocks to create enormous diversity circuits*. They introduce 4 main different criteria combined to classify interneurons: morphology, connectivity pattern, markers, and "intrinsic properties" (firing patterns, I suppose). They also consider in detail the development of interneurons from *discrete proliferative regions*

## 2013

### Oestreich KJ, Weinmann AS. [Master regulators or lineage-specifying? Changing views on CD4+ T cell transcription factors.](https://doi.org/10.1038/nri3321) Nature reviews Immunology. 2012 Nov;12(11):799-804.

Though somewhat niche for immune cells, Oestreich and Weinmann bring up general insights on the role of single, master transcription factors in the development and maintenance of cell identities. They challenge the "simplified paradigm of the master regulator (...) the premise that each developmental cell type is defined by a critical transcription factor (...) both required and sufficient for programming an individual cell fate. " By doing so, they also make explicit the master regulator paradigm and revalidate that in some circumstances, such as maintenance of CD4+ T cells by ZBTB7B, the system holds nicely. The core point of the article, however, is to defend a "new model, termed 'lineage-specifying' (... where) the co-expression of the lineage-specifying transcription factors can tip the scales to variable levels, causing intermediate phenotypes (X′ and Y′) in addition to the phenotypes that were previously viewed as end-point lineages (X and Y)"


# 2000's

## 2006 

### Vickaryous MK, Hall BK. [Human cell type diversity, evolution, development, and classification with special reference to cells derived from the neural crest.](https://doi.org/10.1017/S1464793106007068) Biological reviews. 2006 Aug;81(3):425-55.

Vickaryous  and Hall present a good overview of the cell type discussion up to 2006, and provide a list of 411 in the adult *Homo sapiens*, including 145 types of names. Their catalog starts from *the cell as a component of one of the four basic tissue types (epithelial, nervous,
muscular, and connective tissue* with divisions based on explicit anatomical, functional and molecular criteria, as well as relying on previous catalogs. They discuss individually the criteria for including/excluding several cell types, and make it clear that *acceptance of this compilation requires that each cell
type listed is presumed to represent a mature, fully differentiated entity (cells are terminally differentiated) and that these cells have a stable differentiation*. These cell types are organized under 34 terminal artificial classification categories *(designated A to HH)*.
Considers cell types *mutable biological units, comparable with species and genes*.

They discuss cell-type catalogs throughout the second half of the XX century, specially Rodieck & Brening, 1983, but go as further as to discuss Schwann's seminal categorization of cells around 1839. Mentions briefly that the "analogy between cell types and organisms is not only convenient but practical". The Table 1. Pathways to cell type diversity is quite interesting, considering normal development, but also transdifferentiation and metaplasia, topics that are sometimes left aside. 

