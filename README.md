# isye-8803---topics-on-high-dimensional-data-analytics-exam-ii-solution
**TO GET THIS SOLUTION VISIT:** [ISyE 8803 – Topics on High Dimensional Data Analytics Exam II Solution](https://www.ankitcodinghub.com/product/isye-8803-topics-on-high-dimensional-data-analytics-exam-ii-solution/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;89707&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISyE 8803 – Topics on High Dimensional Data Analytics  Exam II Solution&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<ul>
<li>For all questions, you are required to clearly state all assumptions you make and show all necessary details of your solutions.</li>
<li>You are not allowed to discuss the exam content with your fellow students or receive aid on this exam.</li>
<li>You are expected to observe the Georgia Tech Honor Code throughout the exam.</li>
<li>Exam is due on July 26 at 11:59 pm. Late submission is NOT accepted. Please submit your solutions via Canvas.</li>
</ul>
<h1>Question 1. Regularization (33 points)</h1>
In this problem, you build a set of different models to classify different forest types based on their spectral characteristics at visible-to-near infrared wavelengths observed by ASTER satellite imagery over a forest area in Ibaraki Prefecture, Japan (36<sup>°</sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 57&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑁, 140<sup>°</sup> 38&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝐸). The training data can be found in “training.csv” and test data can be found in “testing.csv”.

Attribute Information:

4 classes: ‘s’ (‘Sugi’ forest) ; ‘h’ (‘Hinoki’ forest); ‘d’ (‘Mixed deciduous’ forest) ; ‘o’ (‘Other’ non-forest land) 27 features:

b1 – b9: ASTER image bands containing spectral information in the green, red, and near infrared wavelengths for three days (Sept. 26, 2010; March 19, 2011; May 08, 2011).

pred_minus_obs_S_b1 – pred_minus_obs_S_b9: Predicted spectral values (based on spatial interpolation) minus actual spectral values for the ‘s’ class (b1-b9).

pred_minus_obs_H_b1 – pred_minus_obs_H_b9: Predicted spectral values (based on spatial interpolation) minus actual spectral values for the ‘h’ class (b1-b9).

<ul>
<li>Run a multinomial logistic regression to classify different forest. Present the coefficients obtained. Present the confusion matrix on the test set.</li>
<li>Use ridge multinomial logistic regression to classify different forest. Explain why we use ridge regression. Present the optimal tuning parameter obtained using cross-validation, the coefficients for this parameter and the confusion matrix for the test set.</li>
<li>Use lasso multinomial logistic regression to classify different forest. Explain why we use lasso. Present the optimal tuning parameter obtained using cross-validation, the coefficients for this parameter and the confusion matrix on the test set.</li>
<li>Use adaptive lasso multinomial logistic regression to classify different forest. Explain why we use adaptive lasso regression. Present the optimal tuning parameter obtained using cross-validation, the coefficients for this parameter and the confusion matrix on the test set.</li>
<li>Which model do you select? Why?</li>
</ul>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<h1>Question 2. Matrix Factorization with Regularization (33 points)</h1>
There is a user-item matrix, 𝑀 available where nonzero elements of the matrix are ratings that a user has for an item. The objective of matrix factorization is to learn a low-rank factorization of 𝑀. It decomposes a large matrix into products of matrices, namely,&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑀 = 𝑈 × 𝑉. The picture below demonstrates the idea of low-rank factorization.

<ul>
<li>In order to learn matrix 𝑈 and 𝑉, we will minimize following loss function 𝐿. In order to overcome the problem of overfitting, we are going to use matrix factorization with regularization for this problem. We define the loss function 𝐿 as follows:</li>
</ul>
𝐿 = 4(𝑀<sub>67 </sub>− 𝑈<sub>6</sub>𝑉<sub>7</sub><sup>9</sup>)<sup>; </sup>+ 𝜆(4‖𝑈<sub>6</sub>‖<sup>; </sup>+ 4?𝑉<sub>7</sub>?<sup>;</sup>)

6,7&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 7

Use the <strong><em>Alternating Least Squares</em></strong> method to minimize the loss function to learn matrix 𝑈 and 𝑉 (Hint: fix 𝑈 or 𝑉 one at a time, derive a closed form solution for the other). Write out pseudocode for implementing the algorithm. You should clearly show the closed form solution in the updating step of your pseudocode.

<ul>
<li>Implement your proposed algorithm using the data located in the the folder ratings.data from MoviesLens Dataset. This dataset consists of ratings of 1682 movies by 943 users (on a 1-5 scale). The test.csv file is generated by removing 10 of the item ratings from train.csv for each user and assign them to test dataset. Plot both training and test errors in terms of MSE versus number of iterations. Please use rank 𝑑 =20, 𝜆 =01 and train it for 100 iterations.</li>
</ul>
(Hint: the 𝑀𝑆𝐸<sub>BCDB </sub>= ∑<sub>(6,7)∈G</sub><sub>HIJH</sub>(𝑀<sub>BCDB67 </sub>− 𝑈<sub>6</sub>𝑉<sub>7</sub><sup>9</sup>)<sup>;</sup> where 𝑈 and 𝑉 are learnt using the train.csv and 𝑆<sub>BCDB</sub> contains the locations of all nonzero ratings in the test.csv.)

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<h1>Question 3. Sparse Representation for Classification (34 points)</h1>
A signal not only might be sparse in an SVD or Fourier basis, but also it might be sparse in an overcomplete dictionary whose columns consist of the training data itself. Wright et al. demonstrated the power of sparse representation in a dictionary of test signals for robust classification of human faces, despite significant noise and occlusions. The so-called sparse representation for classification (SRC) has been widely used in image processing.

In this problem, you need to use two data sets. The first data set is the training set: 30 images are used for each of 20 different people in the Yale B database, resulting in 600 columns. Notice that the first 30 columns are the flattened images of one person, the second 30 columns are the flattened images of another person, and so on. In the test set, there are 4 columns and each column correspond to a flatten noisy and occluded image of 7<sup>th</sup> person in the training set. We want to use sparse representation to classify the images that are in test sets.

Here is what you should do for SRC in this problem:

<ul>
<li>Use the training data set to build an overcomplete library Θ. To use compressed sensing, we need Θ to be a fat matrix. To do so, you need to reshape each column of the training set to 192*168 image and then resize it to 12*10, so the flattened images are 120-component vectors. You can use a built-in function to resize the images and you should normalize each column of Θ by dividing by its norm. Notice that the method of resizing can have an effect on your result; to get better results use the ‘lanczos3’ method for resizing.</li>
<li>You should repeat the same process to the images in the test set: Reshape them to a 192*168 image and resize them to 12*10. You do not need to normalize the test set.</li>
<li>Now that you have library Θ and the test set, you can use L1 norm to find the sparse representation of each image in the test set. To do so, you should solve the following optimization for each image in the test set:</li>
</ul>
𝑀𝑖𝑛𝑖𝑚𝑖𝑧𝑒&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Q|𝑠|Q<sub>T</sub>

𝑠. 𝑡. Q|Θ𝑠 − 𝑌|Q<sub>; </sub>&lt; 𝑒

Where s is the sparse representation, Y is an image in the test set (one column of the test set). Choose the value of <strong>“e=1”</strong> for this optimization. You need to run this optimization on each test set image separately to get the corresponding <strong>s</strong>.

<ul>
<li>The final classification stage in the algorithm is achieved by computing the L2 reconstruction error using the coefficients in the vector <strong>s </strong>vector corresponding to each of the categories separately. The category that minimizes the L2 reconstruction error is chosen for the test image. To do that, consider a sparse representation of an image in test set (<strong>s),</strong> then for all images corresponding to each 20 persons in the original training set compute the following:</li>
</ul>
Error for person (j) = || [Test image(i) – (All training images of person(j)´normalized <strong>s</strong>)] ||<sub>2</sub>/ ||Test image(i)||<sub>2</sub>

All the norms in the above equation are L2 norm. The result of the above equation should be 20 numbers corresponding to the 20 persons in the training set. Normalization of <strong>s</strong> should be based on the normalizing values that you found in part 1. Then you would classify test image(i) as person (j) if it has the minimum error.

Deliverables:

<ol>
<li>Show the 4 images in the test set. You should be able to see that these images are noisy and occluded.</li>
<li>Plot the 4 vectors of <strong>s </strong>separately (corresponding to each image in the test set). Ideally the resulting vector of coefficients <strong>s</strong> should be sparse and have large coefficients primarily in the regions of the library corresponding to the correct person in training set. Comment on whether you see large coefficients on specific part or not.</li>
<li>Plot 4 bar chart correspond to 4 images in test set. In each of these bar charts, you should show the error for person (j) in training set, so it should have 20 bars in it.</li>
<li>All images in the test set are related to the 7<sup>th</sup> person in the training set. Based on the 4 bar charts in the previous section, determine whether or not this method was successful to classify test images.</li>
</ol>
&nbsp;

&nbsp;

&nbsp;

&nbsp;
