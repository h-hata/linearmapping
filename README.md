# liner mapping
This is a HTML with some script for learning liner mapping.

# usage
Two canvases apear on your browser when this HTML file is loaded.
You can plot dots, lines, rectangles on the left canvas, then 
images mapped by the marix are drawn on the right canvas.
When one of the elements of the matrix is change, images on 
both side canvas are cleared.

When the Eignen Value check box is checked, the eigen values and eigen
vectors are shown if exsist. The coodinates change from cartesian to oblique.
The unit vectors of the oblique coodinates are eigenvectors of the matrix.
When the oblique coodinates is showned, the cordinate values what you can see
below each canvas are on the oblique coodinates.

Some problems can be exercised with this HTML sheet.  
Q1) Check how the mapping changes in each of the two matrices with positive and negative determinants.  
Q2) Check the image of the matrix whose determinant is 0.  
Q3) Check the image of the diagonal martix.  
Q4) Check the eigen vectors of a symmetric (Hermite) matrix are orthogonal.  
Q5) Check there is no eigen vector of a kind of orthogonal(Unitary) matrix; rotation martix.  
Q6) Check there exist eigen values of a permutation matrix desspite the orthogonal.  
Q7) Check A=P D P^-1 where P is eigen vector matrix. Put a dot anywhere you like.   
Let X=(x1,y1) be coodinates of this dot. Then check eigen vector check box and, retuen and keep mouse pointer over the dot on the left canvas.  You can see the position of the dot will not change but the coodinates value of the dot changes. Let Y=(p,q) be the cordinate values on the left canvas after the change. This is because $ P^-1 $ acts on the orthogonal cordinate values. That is $ Y=P^1*X $. Compare this Y and the coodinates value below thr right canvas, let the tuple be Y'. The relation between Y and Y' is the diagonal matrix transformation confirmed in Q3. That is, each coordinate component is multipled by the eigenvalue.
This means $ Y'=D*P^1*X $ where $ D $ is eigen value diagonal matrix. Finally uncheck eigen vector check box.
Then Y' is converted to the orthogonal coordinate value. The unchecking means that P is acted on Y'.
Therefore we have confirmed $ AX=P*D*P^-1*X $.  

MIT license applies to this javascript.  
All right reserved by Hiroaki Hata.

