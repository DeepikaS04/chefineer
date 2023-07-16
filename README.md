
<h1> CHEFINEER </h1>
<p>This is a project that is something close to my area of interest. <br> I am a student right now and in an year or less I will be a working individual.
We already know that after leaving the comfort of our homes, how much we focus on our diet. We usually prefer ordering food from some food delivery
app or go out and dine. </p>
<p>This project will help you cook something at home even if you have 10-15 minutes in your hand according to your food choices. <br>
Doesn't it sound both interesting and healthy.</p>
<p>As the input you will have to <ul><li>
 Choose a cuisine 
</li>
<li>Give total time you have to give to cooking</li>
<li>Type of Diet</li>
</ul></p>
<p><b><i>
 Voila!!! The output will be a dish or a list of dishes that you can prepare according to your given choices!
</i></b></p>

<p>We have used Transformers to train the data set. We have trained the model using GPT2 module. <br>
<h4>Transformers <br></h4>
Transformers are a type of neural network architecture. Transformers were developed to solve the problem of sequence transduction, or neural machine translation. That means any task that transforms an input sequence to an output sequence. This includes speech recognition, text-to-speech transformation, etc. Here since we have a dataset having a lot of textual data, it becomes difficult to train it using the traditional neural network algorithms. Hence we came across tranformers and found them useful for training our dataset.<br>
Keeping in mind the trending topics in the field of machine learning, we have also used Google's Bard to get our output. We achieved this by using a python module 'bardapi'. We fetch cookies of the current session of Bard using requests and then give it a prompt as input.
</p>
<h3>Output</h3>
<img src="Screen Shot 2023-07-16 at 10.13.17 PM.png" alt = "output">
<a href = "https://colab.research.google.com/drive/1bv5ZC32k3rgwP14SzxtKM0Ua_z1Sv0K5?usp=sharing"> Google Colab Notebook Link </a>
