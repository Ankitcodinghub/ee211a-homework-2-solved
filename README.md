# ee211a-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [EE211A Homework 2 Solved](https://www.ankitcodinghub.com/product/ee211a-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100068&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE211A Homework 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Motivation

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
In the previous homework, we have seen how to process images using convolutions and mine images for features such as edges using image gradients. In this homework, we will detect other types of useful features in images such as blobs and corners that can be useful for a variety of computer vision tasks. We then transition from detecting useful features in images to relating different images via 2D transformations.

The problem set consists of:

• analytical questions to solidify the concepts covered in the class; and

• coding questions to implement some of the algorithms described in class using Python.

Homework Layout

The homework consists of 5 problems in total, with subparts for each problem. There are 2 types of problems in this homework – analytical and coding. All the problems need to be answered in the Overleaf document. Make a copy of the Overleaf project, and fill in your answers for the question in the solution boxes provided.

Submission

You will need to make two submissions comprising of PDF and code: (1) CCLE: You will save this Overleaf as PDF with all the answers (and necessary work) in boxes. We would like you to use LaTeX, but will accept handwritten or tablet notes. (2) You will also submit your Jupyter notebook (.ipynb file) with all the cells executed or a Matlab script with equivalent code. The course staff will provide only limited Matlab support.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
1 Filter Design

In the class you were taught the Central Difference/Laplacian filter for detecting the edges in an im- age (by computing the gradients along the horizontal and vertical directions). In the discussion we derived those filters by approximating the first (for gradient) and second derivative (for Laplacian) of a univariate function f (x) using the Taylor series expansion of f (x + h) and f (x − h), where h is a small perturbation around x with h = 1 for the discrete case. These filters only consider the adjacent neighbours of the current pixel. In this question you will derive a high-order approxi- mation for the two filters, such that the filters will use 2 adjacent neighbours. To summarize, you will be deriving a higher order approximation to the first/second derivative of f (x). We will use

f (1)(x), f (2)(x) to denote the first and second derivative respectively. 1.1 Compute f (x + h) (1.0 points)

Write the Taylor series approximation for f (x + h) around f (x), such that the approximation error tends to 0 as h5, i.e. consider only the first 5 terms in the Taylor series approximation. Use f(1)(x) for the first derivative, f (2)(x) for the second derivative and so on.

1.2 Compute f (x − h) (1.0 points)

Similarly, write the Taylor series approximation for f (x − h) around f (x), such that the approxi-

mation error tends to 0 as h5.

1.3 Compute f(x+h)− f(x−h) (1.0 points)

Using the expressions you obtained in the previous two parts, compute the expression for f (x + h) − f (x − h). You may assume that O(h5) tends to 0, so that you can neglect the term. You will be using this result to compute a high-order approximation to f 1(x).

1.4 Unknowns at each pixel (1.0 points)

Let’s assume that you have access to f (x), which is a 1D signal (or equivalently one row in an image). This means that you can easily obtain the values for f (x), f (x ± h), f (x ± 2h) and so on (assuming appropriate zero padding for start and end values). However, for each pixel x, if

</div>
</div>
<div class="layoutArea">
<div class="column">
f(x+h) = f(x)+hf(1)(x)+ h2 f(2)(x)+ h3 f(3)(x)+ h4 f(4)(x)+O(h5) 2 6 24

</div>
</div>
<div class="layoutArea">
<div class="column">
f(x−h) = f(x)−hf(1)(x)+ h2 f(2)(x)− h3 f(3)(x)+ h4 f(4)(x)+O(h5) 2 6 24

</div>
</div>
<div class="layoutArea">
<div class="column">
f(x+h)− f(x−h) = 2hf(1)(x)+ h3 f(3)(x) 3

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
you only consider using its adjacent neighbours (±h), then the equation in the previous part has 2 unknowns. What are the two unknowns? Note: h = 1 for the discrete case, so h is not an unknown. But don’t substitute h = 1 as of now; we will substitute it later.

1.5 Compute f (1)(x) (1.0 points)

From the previous part, you know that for each pixel x, if we only consider x ± h, then we have 1 equation and 2 variables (underdetermined system). To mitigate this issue, we consider two adjacent neighbours for each pixel (x ± 2h) in addition to x ± h. Replace h with 2h in the previous equation and you will get another equation for that pixel. So now, for each pixel, you have 2 equations and 2 variables. One equation should have f (x ± h) and the other should have f (x ± 2h). Using these two equations, solve for f (1)(x).

</div>
</div>
<div class="layoutArea">
<div class="column">
The unknowns are f (1)(x) and f (3)(x).

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
f(x+h)− f(x−h) = 2hf(1)(x)+ h3 f(3)(x) 3

f(x+2h)− f(x−2h) = 4hf(1)(x)+8h3 f(3)(x) 3

Multiplying the first equation by −2 and adding the two equations:

−2f(x+h)+2f(x−h)+ f(x+2h)− f(x−2h) = −4hf(1)(x)+4hf(1)(x)−2h3 f(3)(x)+

</div>
</div>
<div class="layoutArea">
<div class="column">
8h3 f(3)(x) 3

</div>
<div class="column">
3

</div>
</div>
<div class="layoutArea">
<div class="column">
Solving for f (3)(x),

f(3)(x) = 1 (−f(x+h)+ f(x−h)+ 1 f(x+2h)− 1 f(x−2h))

</div>
</div>
<div class="layoutArea">
<div class="column">
h3 22 Plugging this back into the first equation:

</div>
</div>
<div class="layoutArea">
<div class="column">
f(1)(x) = 1 (8f(x+h)−8f(x−h)− f(x+2h)+ f(x−2h)) 12h

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1.6 Convolution Kernel (1.0 points)

What is the convolution kernel corresponding to the new filter for f (1)(x)? Substitute h = 1 for the discrete case. This filter is now a higher order central-difference filter which can be used to compute the gradients/edges.

</div>
</div>
<div class="layoutArea">
<div class="column">
1 􏰇1 −8 0 8 −1􏰈 12

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
1.7 Laplacian Filter (1.0 points)

We will repeat the same exercise as the previous parts; however, now we compute a higher order approximation to the Laplacian filter. Similar to 1.3, compute the expression for f (x + h) + f (x − h).

1.8 Unknowns for the Laplacian (1.0 points)

Similar to 1.4, what are the two unknowns for each pixel in the expression from the previous part?

1.9 Compute f (2)(x) (1.0 points)

Similar to 1.5, use f (x ± 2h) to solve for f (2)(x). Write the expression for f (2)(x).

</div>
</div>
<div class="layoutArea">
<div class="column">
f(x+h)+ f(x−h) = 2f(x)+h2 f(2)(x)+ h4 f(4)(x) 12

</div>
</div>
<div class="layoutArea">
<div class="column">
The unknowns are f (2)(x) and f (4)(x).

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
f(x+h)+ f(x−h) = 2f(x)+h2 f(2)(x)+ h4 f(4)(x) 12

f(x+2h)+ f(x−2h) = 2f(x)+4h2 f(2)(x)+4h4 f(4)(x) 3

Multiplying the first equation by −4 and adding them,

−4f(x+h)−4f(x−h)+ f(x+2h)+ f(x−2h) = −8f(x)− h4 f(4)(x)+2f(x)+4h4 f(4)(x)

</div>
</div>
<div class="layoutArea">
<div class="column">
Solving for f (4)(x),

f(4)(x) = 1 (−4f(x+h)−4f(x−h)+ f(x+2h)+ f(x−2h)+6f(x))

</div>
</div>
<div class="layoutArea">
<div class="column">
h4

Plugging this back into the first equation,

</div>
</div>
<div class="layoutArea">
<div class="column">
h2f(2)(x)=f(x+h)+f(x−h)−2f(x)+1(x+h)+1f(x−h)−1 f(x+2h)−1 f(x−2h)−

</div>
</div>
<div class="layoutArea">
<div class="column">
12 f ( x )

</div>
<div class="column">
3 3 12 12

</div>
</div>
<div class="layoutArea">
<div class="column">
f(2)(x) = 1 (16f(x+h)+16f(x−h)−30f(x)− f(x+2h)− f(x−2h)) 12h2

</div>
</div>
<div class="layoutArea">
<div class="column">
33

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1.10 Convolution Kernel (1.0 points)

What is the corresponding convolution for the filter you derived in the previous part? Use h = 1 for the discrete case.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
1 􏰇−1 16 −30 16 −1􏰈 12

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
2 Blob Detection (10.0 points)

In this question, you will be using the Laplacian of Gaussian (LoG) filter to detect blobs in an

image. Let’s consider a 2D Gaussian Gσ (x, y) = 2π σ 2 e 2σ 2 . Remember that we need to

smooth the image using a Gaussian filter before computing the Laplacian to prevent noise ampli- fication. However, instead of computing the Laplacian after filtering the image with a Gaussian kernel, we can directly filter the image with the Laplacian of Gaussian filter.

2.1 Compute ∂2Gσ(x,y) (1.0 points) ∂x2

Write the expression for ∂2Gσ(x,y). ∂x2

2.2 Compute ∂2Gσ(x,y) (1.0 points) ∂y2

Write the expression for ∂2Gσ(x,y). ∂y2

2.3 Laplacian of a 2D Gaussian (1.0 points)

Using the results from the previous parts, write the expression for the Laplacian of a 2D Gaussian,

L(x, y).

2.4 Scale-Normalization (1.0 points)

In class, we studied that it is important to normalize the scale of L(x,y) before using it for blob

detection. What is the normalization factor? Provide justification.

</div>
</div>
<div class="layoutArea">
<div class="column">
x2 + y2 1−􏰁 􏰂

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
∂2Gσ(x,y) 1 −(x2+y2) x 2

∂x2 =2πσ4e 2σ2 ((σ) −1)

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
∂2Gσ(x,y) 1 −(x2+y2) y 2

∂y2 =2πσ4e 2σ2 ((σ) −1)

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
∂2Gσ(x,y) ∂2Gσ(x,y) 1 −(x2+y2) x2+y2 L(x,y) = ∂y2 + ∂x2 = 2πσ4 e 2σ2 ( σ2 −2)

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
The normalization factor is 􏰉 􏰉 L(x,y)dxdy. Letting r2 = x2 +y2, 􏰉−r2 2

</div>
</div>
<div class="layoutArea">
<div class="column">
thiscomesto: 1 e 2σ2(r −2)rdrdθ=

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰉−r2 2

</div>
<div class="column">
2πσ4

</div>
<div class="column">
σ2

</div>
</div>
<div class="layoutArea">
<div class="column">
1 e2σ2(r−2)rdr σ4 σ2

</div>
</div>
<div class="layoutArea">
<div class="column">
222 1􏰉−rr3 2􏰉−r1 1􏰉−r1 2􏰉−r1

</div>
</div>
<div class="layoutArea">
<div class="column">
=2σ4 e 2σ2(σ2)dr−σ4 e 2σ2(σ2)rdr=2σ4 e 2σ2(σ2)rdr−σ4 e 2σ2(σ2)rdr r − r2

</div>
</div>
<div class="layoutArea">
<div class="column">
= 1 (−σ2)e2σ2 (r+2σ2)− 2 σ2(−e 2σ2 ) = 1 . So we should multiply L(x,y) by σ2. σ6 σ4 σ2

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.5 LoG Filter (1.0 points)

(See the Jupyter notebook) Using the expression for L(x,y) and the scale normalization, write a

Python function which will compute the LoG Filter.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>def log_filter(size: int, sigma: float):
    mu = int((size-1)/2)
    LoG = np.zeros((size,size))
    for x in np.arange(size):
</pre>
<pre>        for y in np.arange(size):
            LoG[x,y] = - (1/(np.pi*sigma**4)) \\
            *(1 - ((x-mu)**2 + (y-mu)**2)/(2*sigma**2)) \\
            *np.exp(-((x-mu)**2+(y-mu)**2)/(2*sigma**2))
</pre>
<pre>    LoG /= np.sum(LoG)
    return LoG
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.6 σ values (1.0 points)

(See the Jupyter notebook) What are the 5 sigma values which give the maximum response? To

visualize the response, you can use the colormap in the Jupyter notebook.

2.7 Visualize LoG Filter (1.0 points)

(See the Jupyter notebook) In this sub-part you will visualize the LoG filter. Copy the saved image from the Jupyter notebook here.

</div>
</div>
<div class="layoutArea">
<div class="column">
3,7,11,15,23

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Sigma1 1.0 Sigma2 1.0 Sigma3 1.0 0.0 0 0

2.5 5

0.8 5 0.8 0.8

5.0 10 10

7.5 0.6 0.6 15 0.6 10.0 15 20

12.5 0.4 0.4 25 0.4

20

15.0 30

0.2 25 0.2 0.2 17.5 35

20.0 30 40

0 5 10 15 20 0.0 0 5 10 15 20 25 30 0.0 0 10 20 30 40 0.0

</div>
<div class="column">
0

10

20

30

40

50

</div>
<div class="column">
Sigma4 1.0 0.8 0.6 0.4 0.2 0 10 20 30 40 50 0.0

</div>
<div class="column">
0 10 20 30 40 50 60 70 80

</div>
<div class="column">
Sigma5 1.0 0.8 0.6 0.4 0.2 0 20 40 60 80 0.0

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.8 Visualize the blob detection results (3.0 points)

(See the Jupyter notebook) In this sub-part you will visualize the blob detection results. Copy the

saved image from the Jupyter notebook here.

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
1.0 1.0

</div>
<div class="column">
1.0

0.8

0.6

0.4

0.2

0.0 1.0

0.8

0.6

0.4

0.2

0.0

</div>
</div>
<div class="layoutArea">
<div class="column">
Original Image 000

</div>
<div class="column">
Sigma2

0 50 100 150 200 250

Sigma5

0 50 100 150 200 250

</div>
</div>
<div class="layoutArea">
<div class="column">
50

100

150

200

250

0 50 100 150 200 250

</div>
<div class="column">
0.8 0.8

50 50

0.6 100 0.6 100

150 150 0.4 0.4

200 200 0.2 0.2

250 250 0 50 100 150 200 250

0.0 0.0 1.0 1.0 Sigma4

</div>
</div>
<div class="layoutArea">
<div class="column">
Sigma1

</div>
</div>
<div class="layoutArea">
<div class="column">
50

100

150

200

250

</div>
<div class="column">
50

</div>
<div class="column">
50

</div>
</div>
<div class="layoutArea">
<div class="column">
Sigma3 000

</div>
</div>
<div class="layoutArea">
<div class="column">
0 50 100 150 200 250

</div>
<div class="column">
0 50 100 150 200 250

</div>
</div>
<div class="layoutArea">
<div class="column">
0.8

0.6 100

150

200

250

</div>
<div class="column">
0.8

</div>
</div>
<div class="layoutArea">
<div class="column">
0.4

0.2

0.0

</div>
<div class="column">
0.4

0.2

0.0

</div>
<div class="column">
150

200

250

</div>
</div>
<div class="layoutArea">
<div class="column">
0.6 100

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
3 Corner Detection (10.0 points)

In this question, you will be implementing the Harris corner detector. As discussed in class, corners

generally serve as useful features.

3.1 Computing Image Gradients Using Sobel Filter (1.0 points)

(See the Jupyter notebook). In this sub-part, you will write a function that computes image gradi-

ents using the Sobel filter. Make sure that your code is within the bounding box.

3.2 Visualizing the Image Gradients (1.0 points)

(See the Jupyter notebook). In this sub-part, you will visualize the image gradients. Copy the

saved image from the Jupyter notebook here.

3.3 Computing the Covariance Matrix (1.0 points)

(See the Jupyter notebook). In this sub-part, you will write a function that computes the covariance

matrix of the image gradients. Make sure that your code is within the bounding box.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>def compute_image_gradient(image: np.array):
    dx = conv2D(img, sobel_x)
    dy = conv2D(img, sobel_y)
    return dx, dy
</pre>
</div>
</div>
</div>
<div class="section">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Gradient-X Gradient-Y Gradient-Sum 000

25 25 25 50 50 50 75 75 75

100 100 100 125 125 125 150 150 150 175 175 175

0 50 100 150 200 250 300 0 50 100 150 200 250 300 0 50 100 150 200 250 300

</div>
</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>def grad_covariance(image: np.array, size: int):
    grad_x, grad_y = compute_image_gradient(image)
    Ixx = grad_x**2
    Ixy = grad_x*grad_y
</pre>
<pre>    Iyy = grad_y**2
    return Ixx, Ixy, Iyy
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
3.4 Harris Corner Response (1.0 points)

(See the Jupyter notebook). In this sub-part, you will write a function that computes the Harris

response function. Make sure that your code is within the bounding box.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>def harris_response(image: np.array, k: float, size: int):
</pre>
<pre>    Ixx, Ixy, Iyy = grad_covariance(image, size)
</pre>
<pre>    Sxx = conv2D(Ixx, average_filter(size))
    Syy = conv2D(Iyy, average_filter(size))
    Sxy = conv2D(Ixy, average_filter(size))
</pre>
<pre>    R_img = Sxx*Syy-Sxy**2 - k*(Sxx + Syy)**2
    return R_img
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3.5 Visualizing the Harris Corner Detector (1.0 points)

(See the Jupyter notebook). In this sub-part, you will visualize the Harris corner detections. Copy

the saved image from the Jupyter notebook here.

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>  0
 25
 50
 75
100
125
150
175
200
</pre>
</div>
<div class="column">
0 50 100 150 200 250 300

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3.6 Thresholding the Harris Response (1.0 points)

To remove duplicate detections, you will write a function that applies non-maximum suppression to the Harris corner detections. To make writing this function easier, you will implement it in various parts.

(See the Jupyter notebook). In this sub-part, you will implement the first step of non-maximum suppression: thresholding the Harris response to obtain candidate corner detections. Make sure that your code is within the bounding box.

<pre>  def threshold_harris_response(harris_response: np.array, threshold: float):
      candidate_detections = np.argwhere(harris_response &gt; threshold)
      return candidate_detections
</pre>
3.7 Sorting Candidate Detections (1.0 points)

(See the Jupyter notebook). In this sub-part, you will sort the candidate detections by maximum

Harris response value. Make sure that your code is within the bounding box.

</div>
</div>
<div class="layoutArea">
<div class="column">
12

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
<pre>  def sort_detections(candidate_detections: np.array, harris_response: np.array):
      x = candidate_detections[:,0]
      y = candidate_detections[:,1]
      h_v = H[x,y]
</pre>
<pre>      h_argsort = np.flip(np.argsort(h_v))
      return candidate_detections[h_argsort]
</pre>
3.8 Suppressing Non-max Detections (1.0 points)

(See the Jupyter notebook). In this sub-part, you will implement the final step of non-maximum suppression: removing corner detections that are not local maxima. Make sure that your code is within the bounding box.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>def local_max(sorted_detections: np.array, distance: float):
    N = np.shape(sorted_detections)[0]
    Max_x = []
    Max_y = []
</pre>
<pre>    for i in np.arange(N):
        p1 = sorted_detections[i]
        Lx = np.array(())
        Ly = np.array(())
        for p2 in sorted_detections:
</pre>
<pre>            if l2_distance(p1, p2) &lt;= distance:
                Lx = np.append(Lx,p2[0])
                Ly = np.append(Ly,p2[1])
</pre>
<pre>        am = np.argmax(H[Lx.astype(int),Ly.astype(int)])
        local_max = np.array([Lx[am],Ly[am]]).astype(int)
        Max_x.append(local_max[0])
        Max_y.append(local_max[1])
</pre>
<pre>    m = np.shape(Max_x)[0]
    Max = np.zeros((m,2))
    Max[:,0] = Max_x
    Max[:,1] = Max_y
    return Max
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3.9 Non-Maximum Suppression: Putting it all together (1.0 points)

(See the Jupyter notebook). In this sub-part, you will write a function that performs non-maximum

suppression on the Harris corner response. Make sure that your code is within the bounding box.

</div>
</div>
<div class="layoutArea">
<div class="column">
13

</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>def non_max_suppression(harris_response: np.array, \\
distance: float, threshold: float):
</pre>
<pre>    candidate_detections = \\
    threshold_harris_response(harris_response, threshold)
    sorted_detections = \\
    sort_detections(candidate_detections, harris_response)
    corners = local_max(sorted_detections, distance)
    return corners
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3.10 Visualizing Harris Corner Detections + Non-maximum Suppression (1.0 points)

(See the Jupyter notebook). In this sub-part, you will visualize the Harris corner detections after non-maximum suppression has been applied. Copy the saved image from the Jupyter notebook here. Duplicate corner detections should now be removed.

</div>
</div>
<div class="section">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>  0
 25
 50
 75
100
125
150
175
200
</pre>
</div>
<div class="column">
0 50 100 150 200 250 300

</div>
</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
14

</div>
</div>
</div>
<div class="page" title="Page 15">
<div class="layoutArea">
<div class="column">
4 2D Transformation (10.0 points)

In this question, you will be identifying different 2D transformations. You will be given a set of feature points x and the corresponding transformed points x′. Given these two set of points, you have to identify the 2D transformation. For the first 5 sub-parts, there is only one transformation (translation, scaling, rotation, shearing). For the next parts, there may be more than one transfor- mation. While justifying your answer for each part you should also write the 3 × 3 transformation matrix M.

4.1 Example 1 (1.0 points)

x = {(1,1),(2,1),(2,2),(1,2)} and x′ = {(2,2),(3,2),(3,3),(2,3)}. Identify the transformation

and justify:

4.2 Example 2 (1.0 points)

x = {(1,1),(2,1),(2,2),(1,2)} and x′ = {(0,√2),(√2− √1 ,√2+ √1 ),(0,2√2),(√1 −√2,√2+

√1 )}. Identify the transformation and justify: 2

4.3 Example 3 (1.0 points)

x = {(1, 1), (2, 1), (2, 2), (1, 2)} and x′ = {(−1, 1), (−1, 2), (−2, 2), (−2, 1)}. Identify the transfor- mation and justify:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
1 0 1 The transformation (computed in Python; see the Jupyter notebook) is given by: 0 1 1,

</div>
</div>
<div class="layoutArea">
<div class="column">
which is a translation by 1 unit in the x direction and 1 unit in the y direction.

</div>
</div>
<div class="layoutArea">
<div class="column">
001

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
222

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
The transformation (computed in Python; see the Jupyter notebook) is given by: 0.71 −0.71 0

0.71 0.71 0, which is a rotation by π4 .

001

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
0 −1 0 The transformation (computed in Python; see the Jupyter notebook) is given by: 1 0 0,

</div>
</div>
<div class="layoutArea">
<div class="column">
which is a rotation by π2 .

</div>
</div>
<div class="layoutArea">
<div class="column">
001

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
15

</div>
</div>
</div>
<div class="page" title="Page 16">
<div class="layoutArea">
<div class="column">
4.4 Example 4 (1.0 points)

x = {(1, 1), (2, 1), (2, 2), (1, 2)} and x′ = {(3, 5), (6, 5), (6, 10), (3, 10)}. Identify the transformation

and justify:

4.5 Example 5 (1.0 points)

x = {(1, 1), (2, 1), (2, 2), (1, 2)} and x′ = {(4, 6), (5, 11), (8, 12), (7, 7)}. Identify the transformation

and justify:

4.6 Example 6 (1.0 points)

x = {(1, 1), (2, 1), (2, 2), (1, 2)} and x′ = {(0, 2), (0, 3), (−1, 3), (−1, 2)}. Identify the two transfor-

mations and their order and justify:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
3 0 0 The transformation (computed in Python; see the Jupyter notebook) is given by: 0 5 0,

</div>
</div>
<div class="layoutArea">
<div class="column">
which is a scaling by 3 in the x direction and 5 in the y direction.

</div>
</div>
<div class="layoutArea">
<div class="column">
001

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
1 3 0 The transformation (computed in Python; see the Jupyter notebook) is given by: 5 1 0,

001 which is a shear matrix with a shear of 3 in the x direction and 5 in the y direction.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
0 −1 1 The transformation (computed in Python; see the Jupyter notebook) is given by: 1 0 1,

001 which is a rotation by π2 followed by a translation by 1 unit in the x direction and 1 unit in the

y direction.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
4.7 Example 7 (1.0 points)

x = {(1, 1), (2, 1), (2, 2), (1, 2)} and x′ = {(−2, 2), (−2, 3), (−3, 3), (−3, 2)}. Identify the two trans- formations and their order and justify:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
0 −1 −1 The transformation (computed in Python; see the Jupyter notebook) is given by: 1 0 1 ,

001 which is a rotation by π2 followed by a translation by -1 unit in the x direction and 1 unit in the

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
16

</div>
</div>
</div>
<div class="page" title="Page 17">
<div class="layoutArea">
<div class="column">
y direction.

</div>
</div>
<div class="layoutArea">
<div class="column">
4.8 Example 8 (1.0 points)

x = {(1, 1), (2, 1), (2, 2), (1, 2)} and x′ = {(4, 6), (7, 6), (7, 11), (4, 11)}. Identify the two transfor-

mations and their order and justify:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
3 0 1 The transformation (computed in Python; see the Jupyter notebook) is given by: 0 5 1,

001 which is a scaling by 3 units in the x direction and 5 units in the y direction followed by a

translation by 1 unit in the x direction and 1 unit in the y direction.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
4.9 Example 9 (1.0 points)

x = {(1,1),(2,1),(2,2),(1,2)} and x′ = {(−5,3),(−5,6),(−10,6),(−10,3)}. Identify the two

transformations and their order and justify:

4.10 Example 10 (1.0 points)

x = {(1,1),(2,1),(2,2),(1,2)} and x′ = {(−6,4),(−11,5),(−12,8),(−7,7)}. Identify the two transformations and their order and justify:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
0 −5 0 The transformation (computed in Python; see the Jupyter notebook) is given by: 3 0 0,

001 which is a scaling by 3 in the x direction and 5 in the y direction followed by a rotation by π2 .

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
−5 −1 0 The transformation (computed in Python; see the Jupyter notebook) is given by:  1 3 0

001

1 3 00 −1 0

=5 1 01 0 0,whichisarotationby π2 followedbyashearby3inthexdirection

001001 and 5 in the y direction.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
17

</div>
</div>
</div>
<div class="page" title="Page 18">
<div class="layoutArea">
<div class="column">
5 Interview Question (5.0 points)

Object detection is a technique which allows computers to identify and localize objects in im- ages/videos. Let us consider that we have an object detection system that finds cars in a given image. The object detection system will propose some candidates for the object. You can see multiple candidates for the car in Figure 1 (left), and the final bounding box for the car in Figure 1 (right). Each bounding box has a score which measures the likelihood of finding a car. Given the set of bounding boxes with their locations and their scores, propose a method for generating just one bounding box per object. Use one of the algorithms that has been covered in the class or even this homework.

Hint: One metric for measuring whether different bounding boxes are in the same local “neighbor- hood” is intersection over union (IoU), which is defined as follows:

IoU(box1, box2) = Area of intersection of box1 and box2 . Area of union of box1 and box2

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: (Left) The object detection system identifies many candidates for the location of the car. For each candidate, there is a score which measures how likely it is to find a car in that bounding box. You can see that there are multiple red boxes, where each box will have a score between 0-1. (Right) The final bounding box for the car.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
We can use the non-maximum suppression technique. We simply sort the bounding boxes in order of highest scores and then remove the bounding boxes that have a high degree of overlap, as measured by the IoU, iterating until we have the desired number of boxes or have reached

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
18

</div>
</div>
</div>
<div class="page" title="Page 19">
<div class="layoutArea">
<div class="column">
some minimum threshold on IoU values.

</div>
</div>
<div class="layoutArea">
<div class="column">
19

</div>
</div>
</div>
