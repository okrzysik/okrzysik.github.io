---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit cayman-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
tagline:
---


<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
}
.left {
  width: 62%;
}

.right {
  width: 38%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="row">
  <div class="column left">
    <b>Oliver Krzysik</b> <br>
    <br>

    Hi,<br><br> 
    
    I'm a Postdoctoral Fellow in the Department of Applied Mathematics at the University of Waterloo, working with Prof. Hans De Sterck, and Dr. Robert Falgout (LLNL).<br>

    I obtained my PhD in 2021 from Monash University in the area of parallel-in-time methods for hyperbolic PDEs. I have broad interests in the area of scientific computing including parallel-in-time methods, multigrid methods, numerical analysis, time integration methods, and PDE discretizations.<br>

    For a full list of publications, see my [Google Scholar](https://scholar.google.com.au/citations?user=6wiIrKMAAAAJ&hl=en).<br>

    <!-- the below is commented out for the moment. 
    For more information, see:<br>
    - <a href="{{ '/cv.html' | absolute_url }}">CV</a><br>
    - <a href="{{ '/publications.html' | absolute_url }}">List of publications</a><br><br>
    -->

    Contact: okrzysik (at) uwaterloo (dot) ca
        <br>

      </div>
      <div class="column right">
        <p><img src='../../HeadShot.jpg' border="0" width="300" style="padding:0px; display: block; line-height: 0px; font-size: 0px; border:0px;" align="top">

        <br>



    </p>
      </div>
    </div>

    </body>
