## Barnacle: An alignment framework for building a Chatbot based on Jungian concepts of the psyche.

## Introduction

Barnacle is a unique chatbot project, built on the principles of Carl Jung's theories of archetypes and the collective unconscious. This paradigm facilitates the creation and engagement of multiple chatbot personas, each reflective of different facets of the user's psyche. Over time, these personas grow, evolve, and adjust based on the interactions, leading to a more personalised and aligned chat experience.

![Default_surreal_barnacle_and_human_skull_An_alignment_framewor_0](https://github.com/EveryOneIsGross/barnacle/assets/23621140/a44fcc96-5304-4f44-b005-8b36dcb5043d)

## Current Architecture Overview

The Barnacle project is composed of several Python scripts, each serving a distinctive purpose rooted in Jungian theory. The system constructs a multi-faceted "persona" that the user interacts with, influencing its growth over time. This process allows for dynamically adapting responses that are contextually attuned to the user's communication style and preferences. This Chatbots' context window is built out of shared JSON files stored locally containing previous topics of conversation, generated lessons learned and generated  objectives, created across multiple aspects of the user's own psyche.

shadow.py
The Shadow class is defined within this file. The "Shadow" is a Jungian concept that represents the unconscious aspects of the personality, which the ego does not identify with. This class embodies those elements in the context of the user's interactions, storing these repressed aspects and learning from them. Its responses are generated based on a memory model of previous interactions, resulting in a persona that evolves with the user's input. It encourages free association.

archetypes.py
This script encompasses various archetype classes that epitomise different aspects of the user's psyche. Drawing from Jungian archetypes such as 'The Fool', 'The Magician', 'The Hermit', and 'The Emperor', each archetype has a distinct role and persona. They learn and grow from user interactions, providing a multi-dimensional conversation experience, thereby enhancing the adaptive context of the Barnacle system. These represent varied perspectives on a topic to help the user holistically evaluate their questions.

anima_animus.py
In this file, the Anima and Animus classes are defined. They embody the unconscious feminine and masculine aspects of the user's personality respectively, as per Jungian theory. The interaction with these classes provides unique insights into the user's unconscious gender aspects. Each class learns from its interactions, shaping the responses accordingly and contributing to the growing persona of the chatbot. This is a model intended to expose our gendered bias, and help use engage in new ways of expressing ourselves.

psyche.py
This central interface integrates all the individual components of the Barnacle system, through shared memories and objective generation. It creates an instance of the users Persona, integrating previous interactions with the user across all archetypes. This data is summarised and analysed, providing insights and identifying patterns that shape future interactions. The resulting persona is a cumulative representation of these dynamic elements, offering a highly personalised, aligned and evolving chat interface for the user.

## Framework and Project Goals

This is currently a work in progress, the projects' goal is a automated chain of reasoning across all scripts, each with their own tree branch conversation structure relevent to their logic. Archetypes are to be expanded to represent the whole Tarot, or will integrate my Tree of Life project Sefirot, with lefthanded and right handed path sentiment analysis.


