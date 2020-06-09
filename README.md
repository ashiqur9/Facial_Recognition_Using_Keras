<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Facial Recognition with keras</title>
    <link rel="stylesheet" href="<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">">
</head>
<body>
    <h1 style="text-align: center;">
        Facial Recognition with keras
    </h1>
    <hr>
</br>
<p style="font-size: 1.5rem;">
    In this project I use Numpy, OpenCV, Scit-Learn,Tensorflow and Keras to build model and dataset.
</p>
<p  class="h2  text-success">
    The main Features of this model</p>
    <ul>
        <li><p>High Accuracy. This model gain almost 95% train accuracy and 97% validation Acuracy</p></li>
        <li><p>Before feed data to model dataset is generalize by augmentation which helps to detect pattern in slightly change image</p></li>
        <li><p>This model is built by using about 300-500 images of each person which is expand later through augmentation</p></li>
        <li><p>I use being search api to download all the images in very short period</p></li>
        <li><p>This model is buit with dropout layers and Earlystopping to avoid over-fiting</p></li>
        <li><p>Before each convolution layers data is normalized by BatchNormalization</p> </li>
    </ul>

<div class="h2 text-success">Work through the project</div>
<ol>
    <li><p>Create dataset by downloadin images by <span class="text-info">Create_face_dataset.ipynb</span></p><p>
        To get 1 mont free bing search API Key <a href="#">Click here</a>
    </p></li>
    <li>
       <span> Extract the faces from downloaded images by  <span class="text-info">Face_Extractor.ipynb</span> </p>
    </li>
    <li>
      <p>  Expand dataset size and create actual dataset for further uses by  <span class="text-info"> 	Expand_Dataset_Size(Augmentation).ipynb</span></p>
    </li>
    <li>
       <p> Traing the model by dataset with  <span class="text-info">Face_Recognitionl.ipynb</span></p>
    </li>
    <li>
        <p>Finaly Test your model by <span class="text-info">test.ipynb</span></p>
    </li>
</ol>

<div class="alert alert-warning">
    This project might consume huge RAM so you can use colab with free GPU by Google.
</div>
<div class="alert alert-warning">
    You might need to manualy check faces after face Extraction for damage photo and delete them. 
</div>
</body>
</html>
