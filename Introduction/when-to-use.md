---
layout: default
title: When to Use
parent: Introduction
nav_order: 2
description: "When to Use"
permalink: introduction/when-to-use
---

# When to Use

You can try EZUI to develop a wide range of applications, such as: mind map, news website, blog. In general, the circumstances when EUZI can be used are characterized by the following constraints.

## Usage Areas

We postulate that EZUIs are more suitable for information that is conceptual in nature (e.g., file exploration on a computer, text documents, charts) than for use cases where the representable information has relation to physical objects/landmarks (e.g., maps, photos). Information that is conceptual can be transformed with EZUI such that it does not lose its meaning. When information has a relation to physical objects/landmarks, the aspect ratio change of the objects on the screen would either render objects inaccurately represented (skewed) or cropped.

## Field Of Tasks that EZUI can help

EZUI-based user interfaces are conceptually task agnostic. However, they may be particularly appropriate for tasks where knowledge workers need to explore and comprehend new conceptual information. EZUI may be less useful for repetitive tasks. It perhaps would even be detrimental to the user experience for repetitive tasks, since the animated transitions take time. The focus of a user who is doing repetitive tasks may be on speed rather than on comprehending or learning information.

## Relation to Responsive Design

Responsive Design is a widely applied design solution that is used in order to tailor content for different screens. Responsive design patterns and declarations can be used in parallel with an EZUI since the transformed objects do not influence (with the dual scale factors) the encapsulated content. For instance, when an object is selected and the user interface is shown in Zoom Level 2, the size of the originally applied fonts of an encapsulated textual content stay the same as they were before the magnification happened. As the real-estate for the encapsulated textual content change (due to the elastic magnification), the content can re-flow. Similarly, if an object is elastically magnified that has an image within the object, we postulate the ideal approach is to use the image with its original aspect ratio, and allow the selected object to cut off parts of the encapsulated image. Thus, the inner content is not affected by the elastic magnification, meaning that responsive design patterns can still be used for instance to change font size or limit the maximum width of text block, or in case of images, cropping those can be done.

## Preferred Devices

Conceptually, the EZUI is device agnostic. A device that has a display that can represent information in a two-dimensional pictorial form is the target for an EZUI. EZUI may be particularly beneficial for devices that have small screens (e.g., smartwatches), because there is often more representable information than can fit on a small screen. As the viewport size grows past a typical desktop/laptop screen, the usefulness increases again, because even though a whiteboard-sized screen is much larger (hence lots of information can fit), the user’s viewing distance also tends to increase (so the apparent size of the whiteboard-sized screen is smaller).

Some inspirations are included in the [Demo](https://github.com/linecept/ezui/demo) section.
