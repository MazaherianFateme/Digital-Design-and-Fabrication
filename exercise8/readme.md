# Digital Design & Fabrication – Exercise 8  
# 3D Printed Hair Accessory

**Student:** Fateme Mazaherian  
**Course:** Digital Design & Fabrication  
**University:** Carl von Ossietzky University Oldenburg  
**Lecturers:** Prof. Dr. Susanne Boll-Westermann, Mikołaj Woźniak, Tobias Lunte  

---

## Introduction

For this exercise, I designed and created a personalized 3D printed hair accessory inspired by traditional Kanzashi-style hair sticks.

The goal of this project was to turn a simple everyday object into a functional 3D printed product. I wanted to design something that I could actually use, while also learning how to work with parametric CAD modelling, prepare a model for printing, and understand the connection between design decisions and fabrication results.

This project was also my first experience using Onshape for a complete 3D design process. Because of that, the exercise was not only about the final object, but also about understanding how sketches, dimensions, constraints, extrusion, and slicing work together.

<p align="center">
  <img src="images/inspiration.jpg" width="500" alt="Inspiration image or original wooden hair stick">
</p>

<p align="center">
  <em>Image 1: Inspiration image / original wooden hair stick</em>
</p>

---

## Motivation and Concept

I chose to design a hair accessory because it is something I actually use in my daily life. Especially during warm weather, I often prefer putting my hair up quickly, and I have always liked this type of accessory because it is simple, lightweight, easy to carry, and does not take much space.

I already owned a similar wooden hair stick and enjoyed using it, but after some time I noticed a problem with the material. Since I live in Germany, where the weather can be quite humid, wood is not always practical for everyday use.

Hair accessories are directly in contact with hair, water, and products such as oils or conditioners, so they need to be cleaned regularly. However, wood absorbs moisture and needs a long time to dry after washing. Over time, this can damage the material, change its appearance, and even cause mold.

This problem gave me the idea to create my own 3D printed version. I wanted to make something that keeps the same functionality but uses a material that is easier to wash, dries faster, and lasts longer.

Another important point for me was durability. If a model lasts longer, it does not need to be replaced as quickly. For similar objects, this can reduce the need to use and replace wooden versions repeatedly, which means less wood is wasted over time.

For the decorative part, I used a small house shape and added the word **“Hope.”** This concept had a personal meaning for me. While working on this project, I was missing my family and home, so the house became a small symbol of that feeling. The word “Hope” represents my hope of seeing them again soon.

<p align="center">
  <img src="images/concept-sketch.jpg" width="500" alt="Concept sketch or reference idea">
</p>

<p align="center">
  <em>Image 2: Concept sketch or reference idea</em>
</p>

---

## Starting the CAD Design in Onshape

This was my first experience using parametric CAD software. At the beginning, I realized that CAD modelling is very different from normal drawing. Instead of only focusing on the appearance, I had to think about dimensions, constraints, and how each feature affects the next steps.

I started my design in **Onshape** by selecting the **Top Plane** and creating my first sketch.

The first part I created was the main stick because this was the functional part of the accessory. I started with a simple rectangle for the body. Then I modified the end of the shape by adding a triangular pointed tip.

The pointed shape was important because it helps the accessory slide through the hair more easily, similar to my original wooden version.

While creating this sketch, I added **dimensions** to control the size and used **constraints** to define the relationships between the lines.

At first, some parts of my sketch were still blue, meaning they were under-defined and could move. I adjusted the constraints and dimensions until the sketch became black, which showed that it was **fully constrained / fully defined**.

After finishing the 2D sketch, I used:

**Extrude → Add**

to give the model thickness and create the first 3D shape.

**Turning the idea into a 3D model was more difficult than I expected at the beginning, because every small line, point, and relation had to be controlled properly. I could not only think about the visual shape; I also had to make sure that the model would work as a real printable object.**

<p align="center">
  <img src="images/stick-sketch.jpg" width="500" alt="First sketch of the stick with dimensions">
</p>

<p align="center">
  <em>Image 3: First sketch of the stick with dimensions</em>
</p>

<p align="center">
  <img src="images/extruded-stick.jpg" width="500" alt="Extruded stick model">
</p>

<p align="center">
  <em>Image 4: Extruded stick model</em>
</p>

---

## Designing the Decorative House Part

After completing the main stick, I started working on the decorative part of the accessory.

To create the house shape, I made another sketch using simple geometric shapes:

- a rectangle for the main body
- a triangle for the roof

I positioned the house directly on the stick and made sure that the shapes overlapped.

This was an important step because I learned that objects can look connected visually but still be separate bodies in CAD. I wanted the decorative part to be supported by the stick and become one solid printable object.

After completing the sketch, I used:

**Extrude → Add**

to add the house geometry to the existing model instead of creating a separate part.

<p align="center">
  <img src="images/house-sketch.jpg" width="500" alt="House sketch positioned on the stick">
</p>

<p align="center">
  <em>Image 5: House sketch positioned on the stick</em>
</p>

<p align="center">
  <img src="images/house-extrude.jpg" width="500" alt="House after Extrude Add">
</p>

<p align="center">
  <em>Image 6: House after Extrude Add</em>
</p>

---

## Fixing Sketch Problems and Cleaning the Model

During the design process, I learned that creating a clean sketch is very important for 3D printing.

Some of my earlier sketches had small problems, such as unnecessary lines or points that were not completely connected. Because of these small gaps, Onshape could not always recognize the sketch as a closed profile for extrusion.

To fix this, I went back and edited the sketches.

I used the:

**Trim Tool**

to remove extra lines and unnecessary geometry. After cleaning the sketch, the profiles became easier to control and worked correctly with the Extrude feature.

**I found the tutorials very useful because they explained why clean sketches, closed profiles, and fully defined geometry are important before using features like Extrude. The tutorials helped me understand the logic behind the tools instead of only copying the steps.**

This step helped me understand why the tutorials focused so much on creating clean and fully constrained sketches. Even a very small open area in a sketch can create problems later, especially when the model is prepared for 3D printing.

**One of the main challenges was finding and fixing small sketch problems that were not always visible at first. Sometimes the model looked correct, but because a profile was not completely closed or a line was unnecessary, the extrusion did not work as expected.**

<p align="center">
  <img src="images/trim-tool.jpg" width="500" alt="Sketch correction and Trim Tool process">
</p>

<p align="center">
  <em>Image 7: Sketch correction / Trim Tool process</em>
</p>

---

## Adding the “Hope” Text

After finishing the main shape, I added the word:

**“Hope”**

to the front of the house.

I created a new sketch directly on the surface of the house and used the **Text Tool** in Onshape.

I adjusted the size and position of the text until it fit inside the house.

This step was more challenging than I expected. At first, after adding the text, I noticed that Onshape recognized some letters as separate parts. This meant that my final model was not one complete printable object.

To solve this problem, I edited the text sketch and worked on the constraints until the text became fully defined. The sketch changed from blue to black, showing that the position and geometry were controlled.

After correcting this, I checked the Parts list again and the complete model appeared as:

**Part 1**

This confirmed that the design was one connected object.

<p align="center">
  <img src="images/hope-text-sketch.jpg" width="500" alt="Adding Hope text sketch">
</p>

<p align="center">
  <em>Image 8: Adding Hope text sketch</em>
</p>

<p align="center">
  <img src="images/part-one.jpg" width="500" alt="Fully defined text and Part 1 result">
</p>

<p align="center">
  <em>Image 9: Fully defined text and Part 1 result</em>
</p>

---

## Engraving the Text into the House

I did not want the word to simply sit on top of the model. I wanted it to become part of the design by cutting it into the surface.

For this step, I used:

**Extrude → Remove**

I selected the text regions and removed material from the house.

I also checked the **Merge Scope** to make sure the Remove operation affected the main body and did not create new separate parts.

After this step, the word **“Hope”** was engraved into the house while the whole hair accessory remained a single printable object.

<p align="center">
  <img src="images/extrude-remove.jpg" width="500" alt="Extrude Remove settings">
</p>

<p align="center">
  <em>Image 10: Extrude Remove settings</em>
</p>

<p align="center">
  <img src="images/final-engraved-hope.jpg" width="500" alt="Final engraved Hope design">
</p>

<p align="center">
  <em>Image 11: Final engraved Hope design</em>
</p>

---

## Preparing the Model for 3D Printing

Before exporting the model, I checked the final design carefully.

I made sure that:

- the stick and house were connected correctly
- the engraved text was created properly
- unnecessary sketches and imported references were removed
- the final model consisted of only one part

This check was important because a model that is not one connected body can create problems during slicing and printing. If the design is prepared correctly before printing, there is a higher chance of getting a successful result on the first print. This also helps reduce failed prints, wasted filament, and unnecessary material waste.

After checking everything, I exported the model as a:

**STEP file**

and imported it into **QIDI Studio** for slicing.

For printing preparation, I used:

- **Printer:** QIDI Q2
- **Filament:** PLA Rapido
- **Nozzle diameter:** 0.4 mm
- **Layer height:** 0.20 mm Standard profile

I placed the model flat on the print bed because this orientation provided better stability.

After slicing, I checked the preview and noticed that some parts around the house shape required support because of overhanging areas.

To solve this, I enabled:

**Tree Supports**

with:

- **Threshold angle:** 30°
- **Brim width:** 5 mm

The support helped the overhanging areas print correctly, and the brim improved adhesion to the print bed.

Finally, I checked the layer preview, estimated printing time, support structures, and filament usage before saving the final 3MF project file.

<p align="center">
  <img src="images/qidi-studio.jpg" width="500" alt="Model imported into QIDI Studio">
</p>

<p align="center">
  <em>Image 12: Model imported into QIDI Studio</em>
</p>

<p align="center">
  <img src="images/support-preview.jpg" width="500" alt="Support and slicing preview">
</p>

<p align="center">
  <em>Image 13: Support and slicing preview</em>
</p>

---

## What I Found Important

One of the most important things I learned during this exercise was that 3D printing does not start at the printer. A successful print starts much earlier, during the design process.

If the sketch is not fully defined, if the profiles are not closed, or if the model is made of separate bodies by mistake, the final print can fail or the slicing process can become more complicated.

I also found it important to check the printing setup carefully. The orientation of the model, the supports, the brim, and the layer preview all affect the final result. Correctly preparing the printing part is important because it increases the chance of getting a good result from the first print. This means less wasted time, less wasted filament, and fewer unnecessary failed prints.

Another important point was material choice. By replacing a wooden accessory with a more washable and durable 3D printed version, the object can last longer and become easier to maintain. For similar models, a longer-lasting design can reduce repeated replacements and therefore reduce material waste.

<p align="center">
  <img src="images/final-slicing-preview.jpg" width="500" alt="Final slicing preview or print preparation screenshot">
</p>

<p align="center">
  <em>Image 14: Final slicing preview or print preparation screenshot</em>
</p>

---

## Conclusion

Overall, this exercise was a much bigger learning process than I expected. Turning an idea into a printable object was not only about creating a nice-looking model; it also had to work technically.

**At first, I thought the difficult part would mainly be designing the shape, but I realized that the technical preparation was just as important. The model had to be clean, connected, and correctly prepared so that it could be printed successfully.**

During this project, I learned how important it is to:

- fully define sketches
- use dimensions and constraints correctly
- create closed sketch profiles
- clean sketches using Trim
- understand the difference between separate parts and one solid body
- use Extrude Add and Extrude Remove correctly
- check the model before sending it to the printer

One important thing I learned is that choosing good reference points from the beginning makes the modelling process easier. Designing around a central reference helps align different sketches and makes connections between parts easier to control.

In the end, I created a personalized hair accessory based on something I already use, while improving the material problem of my old wooden version.

<p align="center">
  <img src="images/final-printed-product.jpg" width="500" alt="Final printed product">
</p>

<p align="center">
  <em>Image 15: Final printed product</em>
</p>

<p align="center">
  <img src="images/final-object-in-use.jpg" width="500" alt="Final object in use">
</p>

<p align="center">
  <em>Image 16: Final object in use</em>
</p>
