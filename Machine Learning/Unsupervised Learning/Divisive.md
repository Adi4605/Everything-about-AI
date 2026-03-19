A "Top-down" hierarchical clustering method.

It starts by placing all data points into one large cluster and then recursively splits that cluster into smaller ones based on differences or distances between the points.

Working:
1. **Start with all data points**: 
	Begin with one big group ABCDEFGH.
2. **First split***: 
	Divide it into two groups ABC and DEFGH.
3. **Split again**: 
	The group ABC is divided into A and BC while the group DEFGH is split into DEFG and H.
4. **Keep dividing**: 
	We continue dividing these new groups. BC is split into B and C, DEFG is divided into DE and so on. At this stage most of the data points are now in their individual groups.
5. **Finish**: 
	Stop when all points are separated.
![[Pasted image 20260101110430.png]]
