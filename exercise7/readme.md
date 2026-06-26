<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Designing a Wooden Tea Light Candle Holder</title>

<style>
body{
    font-family: Arial, Helvetica, sans-serif;
    max-width: 900px;
    margin: auto;
    padding: 40px;
    line-height: 1.7;
    background: #f5f5f5;
}

.container{
    background: white;
    padding: 40px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,.15);
}

h1, h2{
    color: #3d2f23;
}

img{
    display: block;
    margin: 20px auto;
    max-width: 700px;
    width: 100%;
    border: 1px solid #ccc;
    border-radius: 8px;
}

.caption{
    text-align: center;
    font-style: italic;
    color: #666;
    margin-top: -8px;
    margin-bottom: 30px;
}
</style>
</head>

<body>
<div class="container">

<h1>Digital Design &amp; Fabrication – Exercise 7</h1>
<h2>CNC Milling – Wooden Tea Light Candle Holder</h2>

<p>
<strong>Student:</strong> Fateme Mazaherian<br>
<strong>Course:</strong> Digital Design &amp; Fabrication<br>
<strong>University:</strong> Carl von Ossietzky University Oldenburg<br>
<strong>Lecturers:</strong> Prof. Dr. Susanne Boll-Westermann, Mikołaj Woźniak, Tobias Lunte
</p>

<hr>

<h2>1. Introduction</h2>

<p>
For this exercise, I designed a wooden tea light candle holder using Inkscape.
The aim was to create a vector outline that could later be imported into CAM software for CNC milling.
I wanted the final design to be decorative while remaining simple enough to manufacture with a CNC milling machine.
</p>

<hr>

<h2>2. Idea and Inspiration</h2>

<p>
The main inspiration for my design came from a decorative wooden mandala-style candle holder.
I chose this flower pattern because it resembles a lotus flower, which is my mother's favourite flower.
I wanted to create something meaningful that I could later paint and give to her as a handmade gift.
</p>

<img src="ideaPattern.png" alt="Reference idea for a wooden flower candle holder">
<p class="caption">Figure 1. Reference image used as inspiration for the flower-shaped candle holder.</p>

<hr>

<h2>3. Document Setup</h2>

<p>
I created a new document in Inkscape and changed the document units to millimetres.
Following the exercise instructions, I set the page size to <strong>100 mm × 150 mm</strong>.
Working with real dimensions was important because the design would later be manufactured using CNC milling.
</p>

<ul>
<li>Software: Inkscape</li>
<li>Units: Millimetres (mm)</li>
<li>Page Size: 100 × 150 mm</li>
<li>Design Type: Vector Outline</li>
<li>Object: Wooden Tea Light Candle Holder</li>
</ul>

<hr>

<h2>4. Creating the Main Shape</h2>

<p>
I started by drawing a simple flower outline using the Pencil Tool.
Then I created the circular opening in the centre where the tea light candle would be placed.
At this stage, the petals were not perfectly identical because everything was drawn manually.
</p>

<img src="drawing.png" alt="First draft of the flower-shaped candle holder">
<p class="caption">Figure 2. First draft of the flower outline and the central candle opening.</p>

<p>
To improve the appearance, I edited the outline using the Node Tool.
By moving and adjusting the nodes, I obtained smoother curves and a cleaner flower shape.
</p>

<hr>

<h2>5. Refining the Design</h2>

<p>
After creating one clean petal, I copied and repeated it around the centre of the design.
A single petal was separated from the original path using the Node Tool and the “Break Path at Selected Nodes” command.
The petal was then duplicated using Ctrl + D and rotated repeatedly to form the complete flower pattern.
</p>

<p>
Using this method ensured that every petal had exactly the same shape, resulting in a more symmetrical and visually balanced design.
It also reduced the amount of manual editing required.
</p>

<img src="brakingOnePetal.png" alt="Separating and copying one petal in Inkscape">
<p class="caption">Figure 3. Separating one petal from the original path before duplicating it around the centre.</p>

<p>
To verify that the design could be manufactured, I created a red circle with a diameter of <strong>6 mm</strong>.
This circle represented the minimum cutter diameter used to check whether there was enough clearance between neighbouring petals.
If the circle could fit between two petals, there would be sufficient space for the milling tool to pass through.
</p>

<p>
I also set the outline stroke width to <strong>1 mm</strong> so that the cutting path was clearly visible before exporting the SVG file.
</p>

<img src="checkingSize.png" alt="Checking the cutting clearance with a 6 mm red circle">
<p class="caption">Figure 4. The red 6 mm circle was used to check the clearance between petals.</p>

<hr>

<h2>6. Adding the Candle Hole</h2>

<p>
I created the candle opening using the Ellipse Tool.
Holding the Ctrl key allowed me to draw a perfect circle.
I then set its dimensions to <strong>39.5 mm × 39.5 mm</strong>, which matches the required tea light candle size.
</p>

<p>
The circle was positioned exactly at the centre of the flower to ensure symmetry and provide sufficient material around the candle opening.
</p>

<img src="result.png" alt="Final flower-shaped tea light candle holder design">
<p class="caption">Figure 5. Final flower-shaped tea light candle holder design.</p>

<hr>

<h2>7. What I Found Important</h2>

<p>
This exercise taught me that it is very important to consider the cutter diameter while designing.
Checking the clearance between the petals before machining helps avoid unnecessary material removal, reduces machining time, and ensures that the final product matches the original design.
</p>

<p>
Another important lesson was that repeating a well-designed component is much more effective than drawing every repeated element manually.
By editing one petal carefully and copying it around the design, I achieved a much cleaner and more professional final result.
</p>

<hr>

<h2>8. Conclusion</h2>

<p>
This exercise helped me understand the complete workflow of preparing a vector design for CNC milling using Inkscape.
I learned how to create clean vector paths, edit shapes using the Node Tool, duplicate repeated elements, verify machining clearances, and prepare the design for manufacturing.
The final result is a flower-inspired tea light candle holder that is both decorative and suitable for CNC milling.
</p>

<p style="text-align:center;">
<em>Prepared as part of the CNC Milling Exercise using Inkscape.</em>
</p>

</div>
</body>
</html>
