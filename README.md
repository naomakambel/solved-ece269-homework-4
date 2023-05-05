Download Link: https://assignmentchef.com/product/solved-ece269-homework-4
<br>
<ol>

 <li><strong>Problem </strong>1<strong>: Moore–Penrose pseudoinverse. </strong>A pseudoinverse of <strong>A </strong>∈ <strong>R</strong><em><sup>m</sup></em><sup>×<em>n </em></sup>is defined as a matrix <em>A</em><sup>+ </sup>∈ <strong>R</strong><em><sup>n</sup></em><sup>×<em>m </em></sup>that satisfies</li>

</ol>

<em>AA</em><sup>+</sup><em>A </em>= <em>A</em>,            <em>A</em><sup>+</sup><em>AA</em><sup>+ </sup>= <em>A</em><sup>+</sup>

and <em>AA</em><sup>+ </sup>and <em>A</em><sup>+</sup><em>A </em>are symmetric.

<ul>

 <li>Show that <em>A</em><sup>+ </sup>is unique.</li>

 <li>Show that (<em>A<sup>T</sup>A</em>)<sup>−</sup><sup>1</sup><em>A<sup>T </sup></em>is the pseudoinverse and a left inverse of a full-rank tall matrix <em>A</em></li>

 <li>Show that <em>A<sup>T</sup></em>(<em>AA<sup>T</sup></em>)<sup>−</sup><sup>1 </sup>is the pseudoinverse and a right inverse of a full-rank fat matrix <em>A</em>.</li>

 <li>Show that <em>A</em><sup>−1 </sup>is the pseudoinverse of a full-rank square matrix <em>A</em>.</li>

 <li>Show that <em>A </em>is the pseudoinverse of itself for a projection matrix <em>A</em>.</li>

 <li>Show that (<em>A<sup>T</sup></em>)<sup>+ </sup>= (<em>A</em><sup>+</sup>)<em><sup>T</sup></em>.</li>

 <li>Show that (<em>AA<sup>T</sup></em>)<sup>+ </sup>= (<em>A</em><sup>+</sup>)<em><sup>T</sup>A</em><sup>+ </sup>and (<em>A<sup>T</sup>A</em>)<sup>+ </sup>= <em>A</em><sup>+</sup>(<em>A</em><sup>+</sup>)<em><sup>T</sup></em>.</li>

 <li>Show that R(<em>A</em><sup>+</sup>) = R(<em>A<sup>T</sup></em>) and N(<em>A</em><sup>+</sup>) = N(<em>A<sup>T</sup></em>).</li>

 <li>Show that <em>P </em>= <em>AA</em><sup>+ </sup>and <em>Q </em>= <em>A</em><sup>+</sup><em>A </em>are projection matrices.</li>

</ul>

*For more information on Academic Integrity Policies at UCSD, please visit http://academicintegrity.ucsd.

edu/excel-integrity/define-cheating/index.html

<ul>

 <li>Show that <em>y </em>= <em>Px </em>and <em>z </em>= <em>Qx </em>are the projections of <em>x </em>onto R(<em>A</em>) and R(<em>A<sup>T</sup></em>), respectively, where <em>P </em>and <em>Q </em>are defined as previously.</li>

 <li>Show that <em>x</em><sup>∗ </sup>= <em>A</em><sup>+</sup><em>b </em>is a least-squares solution to the linear equation <em>Ax </em>= <em>b</em>, i.e., ∥<em>Ax</em><sup>∗ </sup>− <em>b</em>∥ ≤ ∥<em>Ax </em>− <em>b</em>∥ for every other <em>x</em>.</li>

 <li>Show that <em>x</em><sup>∗ </sup>= <em>A</em><sup>+</sup><em>b </em>is the least-norm solution to the linear equation <em>Ax </em>= <em>b</em>, i.e., ∥<em>x</em><sup>∗</sup>∥ ≤ ∥<em>x</em>∥ for every other solution <em>x</em>, provided that a solution exists.</li>

</ul>

<ol start="2">

 <li><strong>Problem </strong>2<strong>: Eigenvalues. </strong>Suppose that <em>A </em>∈ <strong>C</strong><em><sup>n</sup></em><sup>×<em>n </em></sup>has <em>λ</em><sub>1</sub>, <em>λ</em><sub>2</sub>, . . . , <em>λ<sub>n </sub></em>as its eigenvalues repeated according to their algebraic multiplicities.

  <ul>

   <li>Show that det(<em>A</em>) = <em>λ</em><sub>1 </sub> <em>λ</em><sub>2 </sub>···<em>λ<sub>n</sub></em>.</li>

   <li>Show that Trace(<em>A</em>) = <em>λ</em><sub>1 </sub>+<em>λ</em><sub>2 </sub>+ ··· +<em>λ<sub>n</sub></em>.</li>

   <li>Show that the eigenvalues of <em>A<sup>k </sup></em>are <em>λ</em><sub>1</sub><em><sup>k</sup></em>, <em>λ</em><sub>2</sub><em><sup>k</sup></em>, . . . , <em>λ<sup>k</sup><sub>n </sub></em>for <em>k </em>= 1, 2, . . . .</li>

   <li>Show that <em>A </em>is invertible if and only if it does not have a zero eigenvalue.</li>

   <li>Suppose that <em>A </em>is invertible. Show that the eigenvalues of <em>A</em><sup>−1 </sup>are , . . . , <em><sub>λ</sub></em><sup>−</sup><em><sub>n</sub></em><sup>1</sup>.</li>

  </ul></li>

 <li><strong>Problem </strong>3<strong>: Nilpotent Matrices. </strong>A matrix <em>A </em>∈ <strong>C</strong><em><sup>n</sup></em><sup>×<em>n </em></sup>is said to be nilpotent if <em>A<sup>k </sup></em>= 0 for some integer <em>k</em>.

  <ul>

   <li>Show that all eigenvalues of a nilpotent matrix must be 0.</li>

   <li>Show that the smallest <em>k </em>for which <em>A<sup>k </sup></em>= 0, satisfies <em>k </em>≤ <em>n</em>. (<em>Hint: Use Cayley Hamilton</em>)</li>

   <li>Suppose that the smallest <em>k </em>for which <em>A<sup>k </sup></em>= 0, is <em>k </em>= <em>n</em>. Further suppose that <em>A<sup>n</sup></em><sup>−1</sup><em>x </em≯= Then show that {<em>x</em>, <em>Ax</em>, <em>A</em><sup>2</sup><em>x</em>, ··· , <em>A<sup>n</sup></em><sup>−1</sup><em>x</em>} form a basis of <strong>C</strong><em><sup>n</sup></em>.</li>

  </ul></li>

 <li><strong>Problem </strong>4<strong>: Spectral Norm.</strong>

  <ul>

   <li>Show that ∥<em>A<sup>H</sup>A</em>∥ = ∥<em>A</em>∥<sup>2</sup>.</li>

   <li>Show that the spectral norm is <em>unitarily invariant</em>, namely, ∥<em>UAV</em>∥ = ∥<em>A</em>∥ for any unitary matrices <em>U </em>and <em>V</em>.</li>

   <li>Show that</li>

  </ul></li>

</ol>

.

<ol start="5">

 <li><strong>Problem </strong>5<strong>: Properties of PSD matrices. </strong>Let <em>A </em>= <em>A<sup>T </sup></em>∈ <strong>R</strong><em><sup>n</sup></em><sup>×<em>n </em></sup>and <em>B </em>= <em>B<sup>T </sup></em>∈ <strong>R</strong><em><sup>n</sup></em><sup>×<em>n</em></sup>. Prove the following statements.

  <ul>

   <li>If <em>A </em>⪰ 0 and <em>B </em>⪰ 0, then Trace(<em>AB</em>) ≥</li>

   <li>If <em>A </em>⪰ 0, then <em>A </em>+ <em>B </em>⪰ <em>B</em>.</li>

   <li>If <em>A </em>⪰ <em>B</em>, then −<em>B </em>⪰ −<em>A</em>.</li>

   <li>If <em>A </em>⪰ <em>I</em>, then <em>I </em>⪰ <em>A</em><sup>−1</sup>.</li>

   <li>If <em>A </em>⪰ <em>B </em>≻ 0, then <em>B</em><sup>−1 </sup>⪰ <em>A</em><sup>−1 </sup>≻</li>

  </ul></li>

</ol>

<strong>Programming Assignment:</strong>

<strong>Face Recognition Using Eigenfaces and Principal Component Analysis</strong>

Please read the following paper which shows how to use Principal Component Analysis (PCA) for Face Recognition (uploaded on Canvas).

<ol start="1991">

 <li>A Turk and A. P. Pentland, “Face Recognition Using Eigenfaces”, Proceedings of IEEE CVPR 1991.</li>

</ol>

The paper puts forward a simple yet effective idea of using eigenfaces (obtained via PCA) to perform unsupervised face recognition. Read and understand the basic principle, and then conduct the following numerical experiments to implement and test the eigenface-based face recognition algorithm.

<strong>Data: </strong>The dataset (“<strong>eigenface-dataset.zip</strong>” uploaded on Canvas) consist of faces of 171 people and each person has two frontal images (one with a neutral expression, labeled with suffix letter “<strong>a</strong>” and the other with a smiling facial expression, labeled with suffix letter “<strong>b</strong>“), there are 342 full frontal face images manually registered and cropped.

<strong>Implementation and Experiments:</strong>

<ol>

 <li>Compute the principal components (PCs) using 100 individuals’, randomly selected neutral expression training images. Display the ten most representative eigenfaces. Plot the singular values of the data matrix and justify your choice of number of principal components. Repeat this procedure using the same 100 individuals’ smiling expression training images.</li>

 <li>Reconstruct one of 100 individuals’ neutral expression image using different number of PCs you computed from Part 1. As you vary the number of PCs, display your reconstructed images and plot the mean squared error (MSE) of reconstruction versus the number of principal components to show the accuracy of reconstruction. Comment on your result.</li>

</ol>

(<strong>Note</strong>: To calculate MSE and compare the results, you will need to make sure your reconstructed image is on the same numerical scale as the ground truth image across different PCs.)

<ol start="3">

 <li>Reconstruct one of 100 individuals’ smiling expression image using different number of PCs. Again, display your reconstructed images and plot the MSE of reconstruction versus the number of principal components and comment on your result.</li>

 <li>Now consider the remaining 71 individuals. Reconstruct one of the other 71 individuals’ neutral expression image (this image is not in the training set of 100 images used in Part 1-3) using different number of PCs. Again, display your reconstructed images and plot the MSE of reconstruction versus the number of principal components and comment on your result. Repeat this procedure using corresponding individual’s smailing expression image.</li>

 <li><strong>Facial Expression Classification</strong>: Now we want to perform facial expression classification on these images. Since the given dataset only contains two types of facial expressions, we label the smiling image as 0 and neutral image as 1. We are going to use the PCs trained from Part 1 as our eigenfaces.</li>

</ol>

a). Generate your testing set: Start by randomly selecting 60 individuals that are not in the training set.

b). Then new face images are first projected into “smiling face space” and “neutral face space” using the PCs you obtained from Part 1.

c). Follow the reconstruction steps you performed earlier, reconstruct the images and calculate the MSE with its groundtruth. Since we have two classes here, you will obtain two reconstructed images per test image that were projected onto smiling face space and neutral face space.

d). Compare the two MSEs. The face space with a smller MSE will be declared as the class of the test image.

e). Repeat b)-d) for all 60 images. Report your classification accuracy rate for two classes separately.

f). Pick one mistakenly labeled image from each class and display them in your report. Why do you think your eigenface algorithm fails to label this image? Any suggestions to improve this?