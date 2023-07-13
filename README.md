# Image2MarkUp

A Digital Conversion of hand-Drawn flowcharts that clearly explains the approach of a
problem solver using Deep learning. Flowcharts , UML Models ,Finite automata are key
artifacts in Software engineers contexts.
The availability of various tools over the Internet for drawing digital diagrams by joining
various notations takes considerable time,effort, friction and there may be no presence of a
laptop/ desktop .These tools do not provide means for effective communication and
collaboration that are required for creating diagrams. So, A developer has to sketch or
whiteboard or piece of paper. The paper on which the hand-drawn model was drawn may be
lined, squared or dotted. The paper adds numerous lines to drawing which may appear
similar to lines used to denote notations.It however,creates a need to transform model
diagrams into digital counterparts that are processed by analysis tools. Hand-Drawn
Flowcharts do not address the recognition of edges or textual labels.
It uses a neural network based architecture to recognize
notations, edges and textual labels of expressive flowcharts.
Image2MarkUp considerably improves upon existing works in terms of both recognition quality
and scope.It provides comprehensive transformation of hand drawn flowcharts , including
proper handling of textual labels and message flows.It reliably recognizes hand-drawn
flowcharts from scanned images and hence remove undesirable friction in workflow.
**STEPS INVLOVED-**

1- Preprocessing of Images in the Dataset <br>
	a) Resizing the dataset: pixel value taken is 600x600 <br>
	b) Adding more images to dataset using augmentation : 
            Augmentation involved rotation, flipping, change in brightness

2- Annotated images using Roboflow

3- Object detection using YOLOv8 - single stage neural network

