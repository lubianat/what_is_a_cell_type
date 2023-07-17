# What is a cell type? 

By Tiago Lubiana 

tiago.lubiana.alves@usp.br

A chronological collection of the core scientific articles discussing the concept of cell type, cell state, and similar concepts.

Comments on each publication reflect my own summarized view on each piece. Some might be longer, some might be shorter. I'll try to keep them to 1-2 paragraphs.
Longer analyses might be factored out in their own documents. 

I have some focus on categorizing cell types for understanding human biology in the context of the Human Cell Atlas, but considerations across species might be present nevertheless.

If you have additional articles that you think should be featured, just add an issue! 

Citations are added in Vancouver style to preserve publication date.



# 2020s

## 2023 

- Domcke S, Shendure J. [A reference cell tree will serve science better than a reference cell atlas](https://doi.org/10.1016/j.cell.2023.02.016). Cell. 2023 Mar 16;186(6):1103-14. 

A pledge for an ontogenetic tree as the reference for classifying cell types. It brings exciting points of view, but misses essential literature such as [Jeff Doyle's "Cell types as species: Exploring a metaphor"](https://doi.org/10.3389/fpls.2022.868565) and the whole Cell Ontology endeavor. It extends the ontogenetic classification of *C. elegans* to other organisms, but requires critical technical advances before applying to humans.


## 2022 

- Doyle JJ. [Cell types as species: Exploring a metaphor.](https://doi.org/10.3389/fpls.2022.868565) Frontiers in Plant Science. 2022 Aug 22;13:868565.

An in-depth dissection of the analogy between organizing cells in types and organizing individual organisms in species. For different facets, such as "Philosophical underpinnings', Jeff Doyle explores the cell type side and the species side, finalizing with synthesis and outstanding questions. With an impressive coverage of the literature, and the clarity of the writing, the article is a must-read, and under-discussed in the human cell type community.  

## 2021

- Bernstein, MN.  [On cell types and cell states](https://mbernste.github.io/posts/cell_types_cell_states/)  - Blog. 2021 Mar 03

Very interesting blogpost, with a computer-science oriented mindset and graph representations. Claims that , *the concept of cell type is human-made*, *in nature there are only cell states* and *cell types are a subset of cell states*, which may create a logical inconsistency. 

That inconsistency stems out of the fact that "state" in the common literature is used for two things:
 * the certain configuration of each cell (well described by Bernstein) 
 * an abstract grouping (set) of similar cells given certain properties that might not be stable 

The discrete state space is a man-made space of these abstract groupings that reflect the many certain configurations out there. 
These states are as human-made as the cell types. 

The certain configurations, however, are nature-made, and might have patterns that enable decent groupings. 

By "*cell types are a subset of cell states*", what probably was intended was that "each cell type is a subset of the *total set* of states". Bernstein is talking about a particular cell and its states alongside its life cycle. That assumes a certain individual as a reference tree, and cell types would be defined for the reference and inferred for the whole species, a decent thought experiment. In this case, there exists a set of cell states for an individual, and any particular conjunction of such cell states could be called a cell type _for that individual_.  
Then, in the final part, he proceeds to define the concept accross different individuals, by considering their set of states as *two disconnected, and approximately isomorphic subgraphs*.

Bernstein has an all-inclusive view of cell type, where any arbitrary collection of cell states could be called a "cell type", a perspective I shared on a 2021 preprint called ["Towards a pragmatic definition of cell type"](https://www.authorea.com/users/384178/articles/501068-towards-a-pragmatic-definition-of-cell-type). I've been changing my mind, however, and preferring the term "cell class" for that idea, as the *term* cell type is probably better reserved for a particular kind of class with some characteristics, such as stable properties. 

I also share the idea that we should probably not go ahead and just create millions of classes with names and identifiers; we should carefully think which classes we need to represent our knowledge about the world. 

I very much appreciate the use of knowledge graphs and ontologies for organizing information, alongside Bernstein. 
His description is consistent, and implicitly considers that the Cell Ontology (or some other cell ontology) should represent disease states, what is currently (July 2023) not done. 






