# Fake-News-Detection-Using-CBIR
A lot of fake news detection systems rely on natural language processing. This system is somewhat different.
It relies on the fact that a lot of fake news stems from previously used images.


For example: Images from Syria are used to show that this is how security forces in kashmir are treating kashmiris,
Old images of riots are labelled as recent ones to spark communal tension.


What is content based image retrieval ?

Content-based image retrieval (CBIR), also known as query by image content (QBIC) and content-based visual information retrieval (CBVIR) is the application of computer vision techniques to the image retrieval problem, that is, the problem of searching for digital images in large databases. 

"Content-based" means that the search analyzes the contents of the image rather than the metadata such as keywords, tags, or descriptions associated with the image. The term "content" in this context might refer to colors, shapes, textures, or any other information that can be derived from the image itself. CBIR is desirable because searches that rely purely on metadata are dependent on annotation quality and completeness. Having humans manually annotate images by entering keywords or metadata in a large database can be time consuming and may not capture the keywords desired to describe the image. The evaluation of the effectiveness of keyword image search is subjective and has not been well-defined. In the same regard, CBIR systems have similar challenges in defining success.

This system uses content based image retrieval to find already existing images on the internet and cross check if that particular image belongs to some earlier point of time.




This gives us a fake news percentage : A higher percentage means that a similar image exists on the internet with different keywords used.
