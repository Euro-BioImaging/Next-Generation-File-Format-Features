# Next-Generation-File-Format-Features

This GitHub repository dedicated to the discussion around new specifications for feature definition,  extraction and storage within the context of the OME NGFF (Next Generation File Format) standard. This collaborative work is the the combined efforts of @romainGuiet, @fdsteffen, @DillanSaunders, @Tpoquillon, @retogerber, @ebouilhol, @nrepina  who participated in the Zurich Next Generation Image Analysis Workflow Hackathon 2023.



Key objectives:

* Standardization: Establish standardized guidelines for defining and storing features, ensuring interoperability across various image analysis tools and platforms.

* Flexibility: Create a framework that accommodates diverse feature types and differents bioimaging context, empowering users to extract and store a wide range of biological and image-based data.

* Efficiency: Optimize feature storage to minimize data redundancy and enhance computational efficiency.

* Community Engagement: Encourage collaboration and feedback from the wider scientific and bioimaging community to refine and improve these specifications continually.

Related works:

* Table n-data storage format for OME-NGFF  https://github.com/ome/ngff/pull/64 





## Multi-Object Feature Relationship Managment

*Biological images frequently encompass various object types and sizes, 
(such as organoids, cell mitochondria, and p-bodies). The process of 
quantifying these objects and deriving relevant features from them also 
encompasses the extraction of descriptors that characterize their 
interactions. This gives rise to challenges in managing the features of 
multiple objects, elucidating, quantifying, and storing their 
interrelationships.*


