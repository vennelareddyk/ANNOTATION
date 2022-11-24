[annotation.docx](https://github.com/vennelareddyk/ANNOTATION/files/10086356/annotation.docx)

                                                          DEXTR DESCRIPTION

DEXTR or Deep Extreme Cut, obtains an object segmentation from its four extreme points: the left-most, right-most, top, and bottom pixels. The annotated extreme points 
are given as a guiding signal to the input of the network.

DEXTR requires a minimum of four markers to function. When your mouse pointer is over one of these edges, left click or click "A" to create these markings. 
The DEXTR-model will "look" for any object inside of those four markers after you have provided four markers.

You can keep adding points if you're unsatisfied with the choice. You should be aware, though, that occasionally, the outcomes might not be the best. It is claimed 
that adding more than 10 results in weak performance, even for complicated objects.

By left clicking, holding, and dragging markers to the correct location, you can move them. By pressing "backspace," you can delete the most recent marker you set.
Additionally, you can choose a marker that you want to remove by clicking on it first and then pressing the "backspace" key.

You can see a "Threshold" in the upper left corner once DEXTR has been activated. The user can set this threshold anywhere between 0% and 100%. It regulates how 
stringent the model ought to be while producing outcomes. The outcome will be smaller and more exact the higher the threshold. 

You can press "esc" if you're not content with your decision and want to start over. When you are finished with your selection, press "enter" or select the "convert" 
button from the tool settings menu to make it an object.

Annotations with additional information are increasingly prevalent in computer vision. They have created a feature called label attributes to accommodate that. Using 
this functionality, you can supplement any annotation while using our annotation environment. Label classes and attributes are inextricably related thus, you must
assign attributes to each class.

The polygon tool is the tool of choice for the majority of annotators. In contrast to bounding boxes, it enables you to design more intricate forms that can "fit" 
the contours of any object you choose to annotate.

The tools known as the "Brush" and "Eraser" are used to add and remove masks, respectively, or to edit masks. Shapes that are more complex than polygons and
bounding boxes are referred to as masks. When you need pixel-perfect level annotations, a mask that is placed on a certain pixel level is employed.

Sometimes, anything in front "breaks apart" the annotation in the backdrop, so you make partial masks or polygons. This, however, confuses machine learning networks,
making it less than ideal. You have two options for doing that: utilizing the brush, make the backdrop annotation a single, consistent annotation.

Alternatively, you can combine different polygons or masks into a single shape by first selecting them all and then choosing "Merge into single mask."

Bounding boxes are used today for the majority of object detection tasks. Putting a rectangle over an object to mark it out is a frequent and time-consuming 
procedure in supervised learning. We intend to speed up the procedure over what it was with the help of this technology.

An advanced method of picture segmentation called instance segmentation which uses DEXTR deals with locating instances of things and defining their bounds.
Large-scale applications can be made for self-driving cars, medical imaging, aerial crop monitoring, and other real-world scenarios. Box to Instance had 
its start when a few businesses approached us and said they wanted to convert huge datasets with bounding boxes to instances. We thought this was a 
reasonable request, so we made a special tool to assist.

In order for it to function, any bounding boxes on an image are first taken, and they are then used as anchor boxes in which an AI model searches for example shapes.
The user is then shown the shape that is most likely.

Move your mouse over the proposed instance and left click on it to accept a single prediction. BTI will provide suggestions for each bounding box if your image has
numerous bounding boxes. 

And we can save each annotation individually as well as at the end of all annotations.

Roboflow link:  https://universe.roboflow.com/dataminingmilestone3/milestone3-ta1bc


