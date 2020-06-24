# AMT Video Annotation Tools

This repo contains some prototype tools for video annotations.
These single-page HTML tools are designed to be used for Amazon Mechanical Turks crowd-sourcing annotation.

Some demo frames/GIFs are dumped from [Charades dataset](https://prior.allenai.org/projects/charades).

Contributers: [@ranjaykrishna](https://github.com/ranjaykrishna) and me

## Bounding boxes
Provided with a reference video clip and the interested human action, the task is to draw a bounding box around an 
object involved in the action.

See [bbox.html](bbox.html).

## Human-object relationships
Provided with a reference video clip and the interested human action, the task is to label all relationships between the
actor and the object.

See [relationship.html](relationship.html)

## Clip multi-classification
Find all occurring actions in each short video clip.

See [multiclass.html](multiclass.html)



