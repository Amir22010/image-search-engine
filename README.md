# Content Based Image Search Engine

Inspired by [!Adrian Blog]('https://www.pyimagesearch.com/2014/02/03/building-an-image-search-engine-defining-your-image-descriptor-step-1-of-4/')

I am trying to built a visual search engine, by using your own image you can search other simillar images with just a single click.

There are four steps to built an image search engine
- Defining your descriptor
- Indexing your dataset
- Defining your similarity metric
- Searching

An image descriptor defines the algorithm that we are utilizing to describe our image. Features, on the other hand, are the output of an image descriptor. When you put an image into an image descriptor, you will get features out the other end. features (or feature vectors) are just a list of numbers used to abstractly represent and quantify images.

[Image]('https://www.pyimagesearch.com/wp-content/uploads/2014/11/describing_images.jpg')
