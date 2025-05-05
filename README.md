# deep-learning-project-1---classification-weight-sharing-auxiliary-losses-solved
**TO GET THIS SOLUTION VISIT:** [Deep-Learning Project 1 – Classification, weight sharing, auxiliary losses Solved](https://www.ankitcodinghub.com/product/deep-learning-project-1-classification-weight-sharing-auxiliary-losses-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95191&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Deep-Learning&nbsp;Project 1 – Classification, weight sharing, auxiliary losses Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;Project 1 – Classification, weight sharing, auxiliary losses

The objective of this project is to test different architectures to compare two digits visible in a two-channel image. It aims at showing in particular the impact of weight sharing, and of the use of an auxiliary loss to help the training of the main objective.

It should be implemented with PyTorch only code, in particular without using other external libraries such as scikit-learn or numpy.

2.1 Data

The goal of this project is to implement a deep network such that, given as input a series of 2×14×14 tensor, corresponding to pairs of 14 × 14 grayscale images, it predicts for each pair if the first digit is lesser or equal to the second.

</div>
</div>
<div class="layoutArea">
<div class="column">
1 of 3

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The training and test set should be 1,000 pairs each, and the size of the images allows to run experiments rapidly, even in the VM with a single core and no GPU.

You can generate the data sets to use with the function generate ̇pair ̇sets(N) defined in the file dlc ̇practical ̇prologue.py. This function returns six tensors:

</div>
</div>
<div class="layoutArea">
<div class="column">
Name Tensor dimension Type train ̇input N × 2 × 14 × 14 float32 train ̇target N int64 train ̇classes N × 2 int64 test ̇input N × 2 × 14 × 14 float32 test ̇target N int64 test ̇classes N × 2 int64

2.2 Objective

</div>
<div class="column">
Content

Images

Class to predict ∈ {0, 1}

Classes of the two digits ∈ {0,…,9} Images

Class to predict ∈ {0, 1}

Classes of the two digits ∈ {0,…,9}

</div>
</div>
<div class="layoutArea">
<div class="column">
The goal of the project is to compare different architectures, and assess the performance improvement that can be achieved through weight sharing, or using auxiliary losses. For the latter, the training can in particular take advantage of the availability of the classes of the two digits in each pair, beside the Boolean value truly of interest.

All the experiments should be done with 1, 000 pairs for training and test. A convnet with ∼ 70, 000 parameters can be trained with 25 epochs in the VM in less than 2s and should achieve ∼ 15% error rate.

Performance estimates provided in your report should be estimated through 10+ rounds for each architecture, where both data and weight initialization are randomized, and you should provide estimates of standard deviations.

3 Project 2 – Mini deep-learning framework

The objective of this project is to design a mini “deep learning framework” using only pytorch’s tensor operations and the standard math library, hence in particular without using autograd or the neural-network modules.

3.1 Objective

Your framework should import only torch.empty, and use no pre-existing neural-network python toolbox. Your code should work with autograd globally off, which can be achieved with

torch.set ̇grad ̇enabled(False)

Your framework must provide the necessary tools to:

• build networks combining fully connected layers, Tanh, and ReLU, • run the forward and backward passes,

• optimize parameters with SGD for MSE.

You must implement a test executable named test.py that imports your framework and

• Generates a training and a test set of 1,000 points sampled uniformly in [0,1]2, each with a

label 0 if outside the disk centered at (0.5, 0.5) of radius 1/ 2π, and 1 inside, 2 of 3

</div>
</div>
<div class="layoutArea">
<div class="column">
√

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
• builds a network with two input units, two output units, three hidden layers of 25 units, • trains it with MSE, logging the loss,

• computes and prints the final train and the test errors.

3.2 Suggested structure

You are free to come with any new ideas you want, and grading will reward originality. The suggested simple structure is to define a class

class Module(object):

def forward(self, *input): raise NotImplementedError

def backward(self, *gradwrtoutput): raise NotImplementedError

def param(self): return []

and to implement several modules and losses that inherit from it.

Each such module may have tensor parameters, in which case it should also have for each a similarly sized tensor gradient to accumulate the gradient during the back-pass, and

<ul>
<li>forward should get for input, and returns, a tensor or a tuple of tensors.</li>
<li>backward should get as input a tensor or a tuple of tensors containing the gradient of the loss with respect to the module’s output, accumulate the gradient w.r.t. the parameters, and return a tensor or a tuple of tensors containing the gradient of the loss w.r.t. the module’s input.</li>
<li>param should return a list of pairs, each composed of a parameter tensor, and a gradient tensor of same size. This list should be empty for parameterless modules (e.g. ReLU).
Some modules may requires additional methods, and some modules may keep track of information from the forward pass to be used in the backward.

You should implement at least the modules Linear (fully connected layer), ReLU, Tanh, Sequential to combine several modules in basic sequential structure, and LossMSE to compute the MSE loss.
</li>
</ul>
</div>
</div>
</div>
