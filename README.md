# Intermediate_Representation
In this project, I will try to present a visual representation of the what the convnets learn during training. 

The representations learned by convnets are highly amenable to visualization, in large because they are representations of visual concepts.

# Findings:
> * First Layer acts as a collection of various edge detectors.
> > At this stage, almost all the information present in the initial image is present.
> * As we go deeper, the activations becomes more abstract and less visually interpretable.
> > Higher presentations carry increasingly less information about the visual contents of the image and increasingly more information related to the class of the image.
> * In the following layers, more and more filters are blank, which means that the pattern encoded by the filter isn't found in the input image.