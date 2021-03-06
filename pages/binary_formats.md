<!--
This "lecture" or "lesson" template is adapted from the one provided here:
 http://www.buffalo.edu/ubcei/enhance/teaching/lesson-planning.html
Although the page produced from this is learner-facing, some of the
lesson plan structure
-->

# Binary Formats

## Summary

<!--
Short description of the lesson.
-->

Although binary-formatted data is best in many applications for
improved efficiency, we lose the human-readable
simplicity of text-based formats.  One solution is to adopt binary
formats with well defined interfaces for getting and setting data
from and to binary format.  Many formats are available and tend to be
domain specific.  Here, we survey two formats widely used in
technical computing applications: [HDF5]() and [VTK]().

<!--
********* STAGE 1 - DESIRED RESULTS ********************************************
-->

## Learning Outcomes

<!--
      What course goals or outcomes will this lesson address?
-->

 - Students will be able to choose the proper tool.
 - Students will be able to find, load, manipulate, and save
   data.


## Essential Questions

<!--
      What question(s) will your students be able to answer by the end of
      instruction?
-->

 - How can I shared large amounts of data that another person can easily
   use?

## Resources

<!--
      What resources can be made available to your student to support their
      active learning?
      What formats are best suited to complement your course material?
-->

[VTK Book](https://lorensen.github.io/VTKExamples/site/VTKBook/00Preface/)

[HDF5 Documentation](https://portal.hdfgroup.org/display/HDF5/HDF5) with a nice,
short [tutorial](https://portal.hdfgroup.org/display/HDF5/Introduction+to+HDF5)


<!--
********* STAGE 2 - ASSESSMENT EVIDENCE ****************************************
-->

##  Evidence of Student Learning

<!--
      How will you assess students’ prior knowledge?
      What criteria will be used to assess student performance?
      What evidence will be collected to demonstrate achievement?
      How will students reflect and self-assess their learning?
-->

  - Students will inspect an existing HDF5 file using `h5py`.
  - Students will create their own HDF5 file using `h5py`.
  - Students will create a VTK file with scalar and
    vector data for visualization in Paraview or Visit.
  - Students will reflect on their learning by completing their daily log.

<!--
********* STAGE 3 - LEARNING PLAN ****************************************
-->


## Learning Plan

<!--
List the steps in chronological order to create a timeline of what
will occur in your lesson.

Consider how each of the components below will be included in your
lesson if applicable:

   - Anticipatory Sets/Hooks
       * How will you introduce the material and capture their attention?
   - Teacher Modeling
       * What instructional content and techniques will be incorporated
         into this lesson?
   - Guided Practice
       * How will you scaffold information for your students?
       * How will collaborative learning be used?
   - Learning Activities
       * How will students actively engage with the material?
       * How will students work towards achievement of the learning outcomes?
   - Independent Practice
       * How will students show evidence of learning?
   - Reflection
       * What have you learned about your teaching and content covered in this unit?
       * What changes or adjustments could you make?
       * What were the strongest features of your unit?
       * What are your overall reflections in the course to this point?
   - Conclusion and Preview
       * What should students take away from this lesson?
       * What will happen next? Why?
-->

### Required Preparation

  - Skim [this HDF5 tutorial](https://portal.hdfgroup.org/display/HDF5/Introduction+to+HDF5)
  - Ensure `import h5py` works in your Python environment of choice; if not,
    execute `conda install -c anaconda h5py`.
  - Skim [this h5py tutorial](https://docs.h5py.org/en/stable/quick.html)
  - Skim this [overview of VTK formats](https://lorensen.github.io/VTKExamples/site/VTKFileFormats/).
    Install VTK by executing `conda install -c anaconda vtk`.


### Live Activities

  1. Download examples.
  2. Explore the example file using h5view and the h5py interface.
  3. Use h5py to create a new file.  Confirm using h5view.
  3. Use `vtk` in Python to load the example file.  Plot data to verify.
  4. Extend data and save to a new file for next time.

### Videos

- [Video](https://youtu.be/5jFc5DnY4wU)
  and [slides](https://github.com/robertsj/me701/blob/f2020/lectures/Binary_Formats.ipynb)


### Useful Tips (To Be Updated As We Learn!)


<!--  

NOTES  




-->
