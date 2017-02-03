---
title: Generalizing Context for Effective Grounding of Ambiguous Language
author: 'Wil Thomason, wbthomason@cs.cornell.edu'
bibliography: generalized_context.bib
link-citations: true
links-as-notes: true
subparagraph: true
numbersections: true
colorlinks: true
toc: false
...

# Problem Definition

Context is critical to understanding human communication. It is used by humans to encode knowledge
assumed to be shared, disambiguate between otherwise equivalent options, and simply convey things
more efficiently than might otherwise be possible. Thus, in order for robotic teams to be able to
coexist with humans and collaborate on complex tasks, we must have a general means of understanding
contextual information and including it in the language grounding process.

As detailed in the [related work](#related-work), the problem of context inclusion has previously
been studied with limited success. Most approaches are only capable of incorporating very limited
forms of context (i.e. basic knowledge about the environment configuration), require retraining of
the model for changes in context, and/or insufficiently capture the temporally varying nature of
context.

We think that we can succeed in this area where others have failed due to two factors: First,
insights into the nature of context specifically in terms of its use for grounding. Second, the
advent of deep learning approaches (specifically such things as sequence prediction and attention
mechanisms) may prove useful for selecting salient context.

# Related Work

# Approach

## Distribution-Modifying Functions

## Selecting Context

# Evaluation
