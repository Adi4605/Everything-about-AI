Measures the similarity between two non-zero vectors by calculating the cosine of the angle between them.

Used in text analysis, document comparison, search queries, and recommendation systems.

- Similarity measure calculates the distance between data objects based on their feature dimensions in a dataset.
- A smaller distance indicates a higher similarity, while a larger distance indicates a lower similarity.

The formula to find the cosine similarity between two vectors is -
SC​(x, y) = x . y / ||x|| ×× ||y||

where,
- **x . y** = product (dot) of the vectors 'x' and 'y'.
- ****||x||**** and ****||y||**** = length (magnitude) of the two vectors 'x' and 'y'.
- ****||x||**** ×× ****||y||**** = regular product of the two vectors 'x' and 'y'.

![[Pasted image 20260101140334.png]]
- The cosine similarity between two vectors is measured in 'θ'.
- If θ = 0°, the 'x' and 'y' vectors overlap, thus proving they are similar.
- If θ = 90°, the 'x' and 'y' vectors are dissimilar.