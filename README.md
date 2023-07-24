# What is a cell type? 

By Tiago Lubiana 

tiago.lubiana.alves@usp.br

A chronological collection of the core scientific articles discussing the concept of cell type, cell state, and similar concepts.

Comments on each publication reflect my own summarized view on each piece. Some might be longer, some might be shorter. I'll try to keep them to 1-2 paragraphs.
Longer analyses might be factored out in their own documents. 

I have some focus on categorizing cell types for understanding human biology in the context of the Human Cell Atlas, but considerations across species might be present nevertheless.

If you have additional articles that you think should be featured, just add an issue! 

Citations are added in Vancouver style to preserve fine-grained publication date.


# 2020s

## 2023 

- Domcke S, Shendure J. [A reference cell tree will serve science better than a reference cell atlas](https://doi.org/10.1016/j.cell.2023.02.016). Cell. 2023 Mar 16;186(6):1103-14. 

A pledge for an ontogenetic tree as the reference for classifying cell types. It brings exciting points of view, but misses essential literature such as [Jeff Doyle's "Cell types as species: Exploring a metaphor"](https://doi.org/10.3389/fpls.2022.868565) and the whole Cell Ontology endeavor. It extends the ontogenetic classification of *C. elegans* to other organisms, but requires critical technical advances before applying to humans.


## 2022 

- Doyle JJ. [Cell types as species: Exploring a metaphor.](https://doi.org/10.3389/fpls.2022.868565) Frontiers in Plant Science. 2022 Aug 22;13:868565.

An in-depth dissection of the analogy between organizing cells in types and organizing individual organisms in species. For different facets, such as "Philosophical underpinnings', Jeff Doyle explores the cell type side and the species side, finalizing with synthesis and outstanding questions. With an impressive coverage of the literature, and the clarity of the writing, the article is a must-read and, in my opinion, under-discussed in the human cell type community.  

## 2021

- Bernstein, MN.  [On cell types and cell states](https://mbernste.github.io/posts/cell_types_cell_states/)  - Blog. 2021 Mar 03

Very interesting blogpost, with a computer-science oriented mindset and graph representations. Talks about "*cell types are a subset of cell states*" in a state space, meaning that "each cell type is a subset of the *total set* of states". Bernstein is talking about a particular cell and its states alongside its life cycle. Then, in the final part, he proceeds to define the concept across different individuals, by considering their set of states as *two disconnected, and approximately isomorphic subgraphs*. Bernstein has an all-inclusive view of cell type, where any arbitrary collection of cell states could be called a "cell type", a perspective I shared on a 2021 preprint called ["Towards a pragmatic definition of cell type"](https://www.authorea.com/users/384178/articles/501068-towards-a-pragmatic-definition-of-cell-type). I've been changing my mind, however, and preferring the term "cell class" for that idea, as the *term* cell type is probably better reserved for a particular kind of class with some characteristics, such as stable properties. 

I also share the idea that we should *not* create millions of classes and instead think which classes are useful. That is important from the pragmatic standing point of computational ontologies, prized by Bernstein. His description implicitly considers that the Cell Ontology (or some other cell ontology) should represent disease states, what is currently (July 2023) not done. 

# 2010's

## 2019 
- Morris SA. [The evolving concept of cell identity in the single cell era.](https://doi.org/10.1242/dev.169748) Development. 2019 Jun 15;146(12):dev169748.

A discussion of cell identity around 3 pillars: (1) phenotype and function as a central pillar, (2) lineage as a second dimension for full characterization and (3) state as the range of flexible sub-phenotypes a given identity can acquire. In this work, cell identity and cell type are treated as synonyms. Deals with cell types/identities as 'hard-wired' but reprogrammable and cell states as 'softwired'. 

I like Samantha's consideration that  *cluster-specific gene expression is used to infer cell type, representing an initial prediction of identity that must be orthogonally validated*. This is often forgotten in large-scale transcriptomics study. 

## 2017
- Clevers H, Rafelski S, Elowitz M, Klein A, Shendure J, Trapnell C, Lein E, Lundberg E, Uhlen M, Martinez-Arias A, Sanes JR. [What is your conceptual definition of “cell type” in the context of a mature organism?.](https://doi.org/10.1016/j.cels.2017.03.006) Cell Systems. 2017 Mar 22;4(3):255-9.

An influential collection of perspectives on the nature of cell type, mostly by leading biomedical researchers, with brief statements. Discusses the perspectives on cell types x cell states, the role of function and the increasingly important role of transcriptomics as a ruler to divide cell types apart. A must read and re-read.  

## 2016 
- Arendt D, Musser JM, Baker CV, Bergman A, Cepko C, Erwin DH, Pavlicev M, Schlosser G, Widder S, Laubichler MD, Wagner GP. [The origin and evolution of cell types.](https://doi.org/10.1038/nrg.2016.127) Nature Reviews Genetics. 2016 Dec;17(12):744-57.

Detlev Arendt, an evolution researcher with a focus on the marine annelid *Platynereis dumerilii*, presents a thorough description of the notion of "cell type" in light of the evolution. The idea of a "Core Regulatory Complex (CoRC)" of transcription factors determining each cell type is very influential. Defines a cell type as ‘a set of cells in an organism that change in evolution together, partially independent of other cells, and are evolutionarily more closely related to each other than to other cells’. 
The article also includes an impressive [glossary](https://www.nature.com/articles/nrg.2016.127#Glos1), proposing definitions for many terms relevant to understanding the evolutionary definition of "cell type". Talks about cell types as fundamental evolutionary units (*Modular biological entities capable of evolving as a cohesive unit and at least partially independently of others*) similar to genes and species. 

The article discusses explicitly cell type *homology* across species via the sharing of conserved CoRCs. It also builds upon Oliver Hobert's notion of "terminal selectors", a set of transcription factors that establish and maintain postmitotic cell identity. Notably, it extends Owen's 1848 definition of homology to cell types, with a mechanistic explanation of  'same cell type regardless of form and function', with an example for muscle cells across species where *the CoRC from homologous cell types is conserved, whereas the phenotype of the cell is more flexible*. 

Arendt's article is a fantastic entry point to look at cells from an evolutionary perspective. The atlas-builders of today are usually interested in the current snapshot of cell types, in a fashion of evolution-stable account of cell types and their behaviours and humans. In many ways, atlas-builders are more interested in phenotype and function than in homology and history. Nevertheless, as the world is only one, having an evolutionary account of cell types is fundamental for efficiently organizing knowledge about cell types. 


## 2015 

- Trapnell C. [Defining cell types and states with single-cell genomics.](https://doi.org/10.1101/gr.190595.115) Genome research. 2015 Oct 1;25(10):1491-8.

An early perspective of the impact of single-cell transcriptomics on the definition of "cell type" and the discovery of new cell classes. Discusses the technical advances from bulk techniques, and how that enables a fine-grained perspective on cell function; crucially discusses how incorrect grouping of samples might lead to *qualitatively incorrect* interpretations. Cole Trapnell considers also the perspective of pseudotime analysis (e.g. inferring directional time-based state changes from a static populational snapshot), a type of analysis he invented (or at least co-invented). He then goes on to discuss the technical aspects of scRNA-seq analysis and other single-cell omics. Waddington's developmental landscape and attractor basins/wells are constant topics throughout the article.

## 2014 

- Kepecs A, Fishell G. [Interneuron cell types are fit to function.](https://doi.org/10.1038/nature12983) Nature. 2014 Jan 16;505(7483):318-26.

A somewhat niche review focusing on interneurons, but provides insights for the larger classification of cell types. Provides a summarizing standpoint stating that they*the large diversity in interneuron classes may originate from a handful of cardinal cell types* (...) *we hope (we) will help to direct future studies by consolidating interneuron diversity into cardinal classes with specific ground states.*. They go further to consider that *nature has conspired to bestow on* (interneurons) *generalized computational function that necessitated the presence of common biophysical and hodological properties*

I like the wording of *cardinal classes*, as it is precisely vague in stating that these classes are important, even in absolute, developmentally-determined nature. They bring the interesting perspective of a core parts-list of neurons, that is somewhat malleable and can be employed in different contexts. Or, as the say, *a limited set of building blocks to create enormous diversity circuits*.

An additional note is that they deal with 4 main different criteria combined to classify interneurons: morphology, connectivity pattern, markers, and "intrinsic properties" (firing patterns, I suppose). Also considers in detail the development of interneurons from *discrete proliferative regions*. Nevertheless, mentions that  *referring to an interneuron's origin as deriving from a specific embryonic structure may be an imprecise proxy for gene expression*.

I do wish they had provided an actual list of "cardinal classes" of interneurons, even if provisional. Of note, the concept of "cardinal classes" is not super hot on the scientific literature, with 8 pubmed hits (Jul 2023, [link](https://pubmed.ncbi.nlm.nih.gov/?term=%22cardinal+classes%22+%2B+neuron)). It seems to fare better in the spinal chord community, with a 2021 articles in Science and Nature Communications bearing the names [*"Conserved genetic signatures parcellate cardinal spinal neuron classes into local and projection subsets"*](https://doi.org/10.1126/science.abe0690) and [*"A harmonized atlas of mouse spinal cord cell types and their spatial organization"*](https://doi.org/10.1038/s41467-021-25125-1), neither citing this review.  A 2023 article on Neuron, [*"Cortical somatostatin interneuron subtypes form cell-type-specific circuits"*](https://doi.org/10.1016/j.neuron.2023.05.032), however, uses the concept for cortical interneurons as a whole and does cite this review. 


# 2000's

## 2006 

- Vickaryous MK, Hall BK. [Human cell type diversity, evolution, development, and classification with special reference to cells derived from the neural crest.](https://doi.org/10.1017/S1464793106007068) Biological reviews. 2006 Aug;81(3):425-55.

Vickaryous (great name, by the way) and Hall present a good overview of the cell type discussion, and provide a list of 411 in the adult *Homo sapiens*, including 145 types of names. Their catalog starts from *the cell as a component of one of the four basic tissue types (epithelial, nervous,
muscular, and connective tissue* with divisions based on explicit anatomical, functional and molecular criteria, as well as relying on previous catalogs. They discuss individually the criteria for including/excluding several cell types, and make it clear that *acceptance of this compilation requires that each cell
type listed is presumed to represent a mature, fully differentiated entity (cells are terminally differentiated) and that these cells have a stable differentiation*. These cell types are organized under 34 terminal artificial classification categories *(designated A to HH)*.
Considers cell types *mutable biological units, comparable with species and genes*.

They discuss cell-type catalogs throughout the second half of the XX century, specially Rodieck & Brening, 1983, but go as further as to discuss Schwann's seminal categorization of cells around 1839. Mentions briefly that the "analogy between cell types and organisms is not only convenient but practical". The Table 1. Pathways to cell type diversity is quite interesting, considering normal development, but also transdifferentiation and metaplasia, topics that are sometimes left aside. 

