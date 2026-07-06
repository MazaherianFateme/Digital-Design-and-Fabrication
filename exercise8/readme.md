<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>3D Printed Hair Accessory</title>

  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.7;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7;
      color: #222;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 40px 22px;
      background-color: #ffffff;
    }

    h1, h2 {
      color: #1f1f1f;
      line-height: 1.3;
    }

    h1 {
      font-size: 2.1rem;
      margin-bottom: 10px;
    }

    h2 {
      margin-top: 45px;
      border-bottom: 2px solid #eeeeee;
      padding-bottom: 8px;
    }

    .subtitle {
      font-size: 1.2rem;
      color: #555;
      margin-bottom: 30px;
    }

    .info {
      background-color: #f1f1f1;
      padding: 18px 22px;
      border-radius: 10px;
      margin-bottom: 35px;
    }

    .info p {
      margin: 6px 0;
    }

    p {
      margin-bottom: 18px;
    }

    ul {
      margin-bottom: 22px;
    }

    li {
      margin-bottom: 8px;
    }

    .process-step {
      background-color: #fafafa;
      border-left: 4px solid #333;
      padding: 12px 18px;
      margin: 20px 0;
      font-weight: bold;
    }

    figure {
      text-align: center;
      margin: 28px auto;
    }

    .blog-image {
      width: 85%;
      max-width: 620px;
      height: auto;
      border-radius: 10px;
      border: 1px solid #ddd;
      box-shadow: 0 3px 12px rgba(0, 0, 0, 0.08);
    }

    figcaption {
      font-size: 0.9rem;
      color: #666;
      margin-top: 8px;
    }

    .footer {
      margin-top: 50px;
      padding-top: 20px;
      border-top: 2px solid #eeeeee;
      color: #555;
      font-size: 0.95rem;
    }

    @media (max-width: 600px) {
      .container {
        padding: 25px 16px;
      }

      h1 {
        font-size: 1.7rem;
      }

      .blog-image {
        width: 100%;
        max-width: 100%;
      }
    }
  </style>
</head>

<body>
  <main class="container">

    <h1>Digital Design &amp; Fabrication – Exercise 8</h1>
    <p class="subtitle">Designing and 3D Printing a Personalized Hair Accessory</p>

    <section class="info">
      <p><strong>Student:</strong> Fateme Mazaherian</p>
      <p><strong>Course:</strong> Digital Design &amp; Fabrication</p>
      <p><strong>University:</strong> Carl von Ossietzky University Oldenburg</p>
      <p><strong>Lecturers:</strong> Prof. Dr. Susanne Boll-Westermann, Mikołaj Woźniak, Tobias Lunte</p>
    </section>

    <section>
      <h2>Introduction</h2>

      <p>
        For this exercise, I designed and fabricated a personalized 3D printed hair accessory inspired by traditional Kanzashi-style hair sticks.
      </p>

      <p>
        I chose this idea because I have always liked this type of hair accessory. Hair sticks are simple, lightweight, easy to carry, and very practical, especially during warm weather when I want to tie up my hair quickly. Compared to normal hair ties, I personally find hair sticks more comfortable because they hold my hair without pulling it too much.
      </p>

      <p>
        The main motivation for this project came from a problem I had with a hair stick I already owned. My previous one was made from wood, and although I liked the design, I realized that wood was not the best material for daily use. Since I live in Germany, where the humidity can be relatively high, the wooden material started to become problematic.
      </p>

      <p>
        Hair accessories are often in contact with hair, water, and hair products such as oils or conditioners. Because of this, they need to be cleaned regularly. However, wood absorbs moisture and takes a long time to dry. Over time, this can damage the material, change its appearance, or even create the risk of mold.
      </p>

      <p>
        That is why I wanted to create a 3D printed plastic version. My goal was to design something that would be easier to clean, dry faster, and be more durable for everyday use.
      </p>

      <p>
        Before starting the CAD model, I searched for different hair stick designs to get inspiration. After looking at different examples and deciding on the general concept, I started creating my own model in Onshape.
      </p>

      <figure>
        <img class="blog-image" src="images/inspiration-reference.jpg" alt="Inspiration and reference images for the hair accessory design">
        <figcaption>Inspiration/reference image</figcaption>
      </figure>
    </section>

    <section>
      <h2>Creating the Basic Shape</h2>

      <p>
        This project was my first experience working with parametric CAD software. At the beginning, Onshape felt very different from normal drawing software. I could not just draw freely and move things around visually. Instead, I had to think more carefully about sketches, constraints, dimensions, and how each feature connects to the next one.
      </p>

      <p>
        I started the CAD design in <strong>Onshape</strong> by selecting the <strong>Top Plane</strong> and creating my first sketch.
      </p>

      <p>
        The first part I designed was the main stick of the hair accessory. I created a rectangle for the body of the stick and then modified one end by adding a triangular pointed tip.
      </p>

      <p>
        The pointed end was an intentional design choice. I wanted the accessory to slide through the hair more easily, so the tip needed to be narrow enough to pass through the hair smoothly.
      </p>

      <p>
        During the sketching process, I used <strong>dimensions</strong> to control the size of the design. I also used <strong>constraints</strong> to define the relationship between different sketch elements, such as how lines connect to each other and how the shape should stay controlled.
      </p>

      <p>
        At first, some of the sketch lines were blue. This meant that the sketch was still under-defined and some parts could still move. I added the necessary dimensions and constraints until the sketch lines became black. This showed that the sketch was <strong>fully constrained / fully defined</strong>.
      </p>

      <p>
        After completing the sketch, I used:
      </p>

      <div class="process-step">Extrude → Add</div>

      <p>
        This turned the 2D sketch into a 3D object and gave the hair stick its thickness.
      </p>

      <figure>
        <img class="blog-image" src="images/stick-sketch.jpg" alt="Stick sketch in Onshape">
        <figcaption>Stick sketch in Onshape</figcaption>
      </figure>

      <figure>
        <img class="blog-image" src="images/first-extrusion.jpg" alt="First extrusion of the hair stick">
        <figcaption>First extrusion of the main stick</figcaption>
      </figure>
    </section>

    <section>
      <h2>Adding the Decorative House Shape</h2>

      <p>
        After finishing the main stick, I started designing the decorative part of the accessory.
      </p>

      <p>
        I decided to create a small house shape because I wanted the design to have a personal meaning. While working on this project, I was missing my family and home, so the house became a symbol of that feeling. I also chose the word <strong>“Hope”</strong> because it represents my hope of seeing them again soon.
      </p>

      <p>
        For the house design, I created a new sketch on the existing surface of the model.
      </p>

      <p>I used simple geometric shapes:</p>

      <ul>
        <li>a rectangle for the main body of the house</li>
        <li>a triangle for the roof</li>
      </ul>

      <p>
        I positioned the house directly on top of the stick and made sure that the two shapes overlapped.
      </p>

      <p>
        This step was important because I did not want the house and the stick to become separate objects. By overlapping the shapes, I could create a stronger connection between them. This also allowed the stick to support the house structure better, which is important for a 3D printed object that needs to be strong enough for daily use.
      </p>

      <p>
        After finishing the house sketch, I used:
      </p>

      <div class="process-step">Extrude → Add</div>

      <p>
        again to give the house thickness and merge it with the existing model.
      </p>

      <figure>
        <img class="blog-image" src="images/house-sketch.jpg" alt="House sketch on the existing model surface">
        <figcaption>House sketch on the existing model surface</figcaption>
      </figure>

      <figure>
        <img class="blog-image" src="images/house-extrusion.jpg" alt="House shape extruded and merged with the stick">
        <figcaption>House extrusion added to the main stick</figcaption>
      </figure>
    </section>

    <section>
      <h2>Fixing Sketch Problems</h2>

      <p>
        During the process, I learned from the class tutorials and also from my own mistakes that sketches must be completely closed before they can become a correct 3D solid.
      </p>

      <p>
        Some of my earlier sketches had small gaps between points or unnecessary extra lines. These small problems caused issues when I tried to use the Extrude feature, because Onshape could not recognize the shape as a closed profile.
      </p>

      <p>
        To solve this, I went back to the sketches and corrected the open areas. I checked the connections between the lines and made sure that the sketch profiles were closed properly.
      </p>

      <p>
        I also used the:
      </p>

      <div class="process-step">Trim Tool</div>

      <p>
        to remove unnecessary lines and clean up the geometry.
      </p>

      <p>
        This made the sketches simpler, cleaner, and easier to work with. It also helped prepare them correctly for extrusion.
      </p>

      <figure>
        <img class="blog-image" src="images/sketch-problem.jpg" alt="Sketch problem showing open profiles or extra lines">
        <figcaption>Sketch problem before cleaning the geometry</figcaption>
      </figure>

      <figure>
        <img class="blog-image" src="images/trim-tool.jpg" alt="Using the Trim Tool in Onshape">
        <figcaption>Using the Trim Tool to clean the sketch</figcaption>
      </figure>
    </section>

    <section>
      <h2>Adding the Text Design</h2>

      <p>
        To make the design more personal, I added the word:
      </p>

      <div class="process-step">Hope</div>

      <p>
        to the front surface of the house.
      </p>

      <p>
        I created a new sketch on the house surface and used the <strong>Text Tool</strong> in Onshape. After adding the text, I adjusted the size and position until it fitted properly inside the house shape.
      </p>

      <p>
        At first, I noticed a problem. Onshape created multiple parts because each letter was being recognized separately. This meant that my model was not one connected printable object.
      </p>

      <p>
        To solve this, I edited the text sketch and placed the whole word inside one text box. I also adjusted the sketch constraints until the text became fully defined.
      </p>

      <p>
        When the sketch changed from blue to black, I knew that the geometry was properly controlled.
      </p>

      <p>
        After fixing this issue, the Parts list showed only:
      </p>

      <div class="process-step">Part 1</div>

      <p>
        This confirmed that the model was one connected body instead of multiple separate parts.
      </p>

      <figure>
        <img class="blog-image" src="images/text-sketch.jpg" alt="Text sketch with the word Hope on the house surface">
        <figcaption>Text sketch with the word “Hope”</figcaption>
      </figure>

      <figure>
        <img class="blog-image" src="images/part-list.jpg" alt="Parts list showing only Part 1">
        <figcaption>Parts list showing one connected body</figcaption>
      </figure>
    </section>

    <section>
      <h2>Engraving the Text</h2>

      <p>
        My goal was not to place the letters on top of the house. Instead, I wanted the text to be engraved into the surface.
      </p>

      <p>
        For this step, I used:
      </p>

      <div class="process-step">Extrude → Remove</div>

      <p>
        I selected the text regions and removed material from the house surface.
      </p>

      <p>
        During this step, I also checked the <strong>Merge Scope</strong> carefully to make sure that the Remove operation affected the correct main body and did not create additional parts.
      </p>

      <p>
        This created hollow letters inside the house while keeping the whole accessory as one single printable model.
      </p>

      <figure>
        <img class="blog-image" src="images/extrude-remove.jpg" alt="Using Extrude Remove to engrave the text">
        <figcaption>Using Extrude Remove to engrave the text</figcaption>
      </figure>

      <figure>
        <img class="blog-image" src="images/final-engraved-text.jpg" alt="Final engraved Hope text on the house surface">
        <figcaption>Final engraved text result</figcaption>
      </figure>
    </section>

    <section>
      <h2>Preparing the Model for 3D Printing</h2>

      <p>
        Before exporting the design, I checked the final model carefully.
      </p>

      <p>I made sure that:</p>

      <ul>
        <li>the stick and house were connected</li>
        <li>the engraved text worked correctly</li>
        <li>unnecessary reference sketches and imported objects were removed</li>
        <li>the complete model existed as only one part</li>
      </ul>

      <p>
        After checking the model, I exported it as a <strong>STEP file</strong> and imported it into <strong>QIDI Studio</strong>.
      </p>

      <p>
        For slicing, I used the following settings:
      </p>

      <ul>
        <li><strong>Printer:</strong> QIDI Q2</li>
        <li><strong>Material:</strong> PLA Rapido</li>
        <li><strong>Nozzle diameter:</strong> 0.4 mm</li>
        <li><strong>Layer height:</strong> 0.20 mm Standard profile</li>
      </ul>

      <p>
        I placed the model flat on the print bed to increase stability during printing.
      </p>

      <p>
        In the preview mode, I checked the printing layers and noticed that some areas required support because they were not directly touching the build plate.
      </p>

      <p>
        Therefore, I enabled:
      </p>

      <div class="process-step">Tree Supports</div>

      <p>
        with the following settings:
      </p>

      <ul>
        <li><strong>Threshold angle:</strong> 30°</li>
        <li><strong>Brim width:</strong> 5 mm</li>
      </ul>

      <p>
        The brim was added to improve bed adhesion and reduce the chance of the model moving during printing.
      </p>

      <p>
        After slicing, I checked the final preview, including the generated supports, estimated printing time, and filament usage.
      </p>

      <p>
        At this point, the model was ready for 3D printing.
      </p>

      <figure>
        <img class="blog-image" src="images/exported-model.jpg" alt="Exported model before slicing">
        <figcaption>Exported model before slicing</figcaption>
      </figure>

      <figure>
        <img class="blog-image" src="images/qidi-studio-slicer.jpg" alt="QIDI Studio slicer settings">
        <figcaption>QIDI Studio slicer settings</figcaption>
      </figure>

      <figure>
        <img class="blog-image" src="images/support-preview.jpg" alt="Tree support preview in QIDI Studio">
        <figcaption>Tree support preview</figcaption>
      </figure>

      <figure>
        <img class="blog-image" src="images/final-print-preview.jpg" alt="Final print preview with supports and brim">
        <figcaption>Final print preview with supports and brim</figcaption>
      </figure>
    </section>

    <section>
      <h2>Reflection and What I Learned</h2>

      <p>
        Overall, I enjoyed this exercise more than I expected. Turning an idea into a real printable object was challenging, but it was also very satisfying to see how a simple concept could become a physical product.
      </p>

      <p>
        During this project, I learned that 3D modelling is not only about creating a shape that looks nice. The model also needs to be technically correct, especially if it is going to be 3D printed.
      </p>

      <p>
        I learned the importance of:
      </p>

      <ul>
        <li>fully defining sketches</li>
        <li>using constraints correctly</li>
        <li>creating closed sketch profiles</li>
        <li>cleaning sketches with the Trim Tool</li>
        <li>understanding the difference between separate parts and one connected body</li>
        <li>using Extrude Add and Extrude Remove correctly</li>
        <li>checking the model before slicing</li>
      </ul>

      <p>
        One important lesson was that choosing a good reference point makes the design process easier. Starting the design around central references instead of random edges helps connect different sketches and control the relationships between parts more clearly.
      </p>

      <p>
        The final result is a personalized 3D printed hair accessory that replaces my wooden version with a stronger, washable, and more durable plastic design. It also has a personal meaning because of the house shape and the engraved word <strong>“Hope.”</strong>
      </p>

      <figure>
        <img class="blog-image" src="images/final-cad-model.jpg" alt="Final CAD model of the 3D printed hair accessory">
        <figcaption>Final CAD model</figcaption>
      </figure>

      <figure>
        <img class="blog-image" src="images/final-printed-object.jpg" alt="Final 3D printed hair accessory">
        <figcaption>Final 3D printed object</figcaption>
      </figure>

      <figure>
        <img class="blog-image" src="images/accessory-in-use.jpg" alt="3D printed hair accessory in use">
        <figcaption>Accessory in use</figcaption>
      </figure>
    </section>

    <footer class="footer">
      <p>
        Digital Design &amp; Fabrication – Exercise 8 | 3D Printed Hair Accessory
      </p>
    </footer>

  </main>
</body>
</html>
