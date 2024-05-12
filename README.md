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

 ## Citation
[1]: <a id="SAM" href="https://github.com/luca-medeiros/lang-segment-anything">lang-segment-anything</a>
