# Pose-editing

## Task 1 (Segment Object in Given Scene)
<p>
  For segmenting the user-specified object from an image, I have used Grounding DINO and Segment Anything Model (SAM) <cite>[1]</cite>.
  Given a text prompt and an image, Grounding-DINO can return the most relevant bounding boxes for the given prompt. And, given a bounding box and an image, SAM can return the segmented mask inside the bounding box.
</p>
<p align="middle">
  <img title="a title" alt="Masked image of laptop" src="https://github.com/mukulmehar/Pose-editing/blob/main/generated_images_task_1/laptop_generated.png" width=400 height=400>
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img title="a title" alt="Masked image of laptop" src="https://github.com/mukulmehar/Pose-editing/blob/main/generated_images_task_1/flower_vase_generated.png" width=400 height=400>
</p>

## Task 2

### Results of Image Sculpting
<p>
  The Image Sculpting framework <cite>[2]</cite> is employed to manipulate 2D images by integrating techniques from 3D geometry and graphics. This methodology diverges significantly from conventional approaches, which are constrained within 2D domains and usually depend on textual directives, resulting in ambiguity and restricted control. Image Sculpting transforms 2D entities into 3D, facilitating direct manipulation of their three-dimensional geometry. After editing, these entities are reverted back to 2D and seamlessly integrated into the original image, yielding high-fidelity outcomes through a coarse-to-fine refinement procedure.
</p>

<p align="middle">
  <img src="https://github.com/mukulmehar/Pose-editing/assets/54510198/c7befee9-edb7-4eb2-b0ee-16438ca9d86a" width=400 height=400>
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="https://github.com/mukulmehar/Pose-editing/assets/54510198/b6457f61-df6f-47aa-bb95-1002fda86732" width=400 height=400>
</p>

https://github.com/mukulmehar/Pose-editing/assets/54510198/90b5897e-873a-42a8-b553-1ac6d722f472

 ## Citation
[1]: <a id="SAM" href="https://github.com/luca-medeiros/lang-segment-anything">lang-segment-anything</a>

[2]: <a id="Sculpt" href="https://github.com/vision-x-nyu/image-sculpting/tree/main">image-sculpting</a>
