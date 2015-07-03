### OpenCV Fork
OpenCV 3 had some removals in the java API and in the C++ version itself, so I did some hacks to add them again.

This fork has these changes:
- added loadModel and saveModel to be used in java binding works with SVM only
- added trainAutoFlat as a wapper to trainAuto that can be used in java bindings
- merged feature2dx from opencv_contrib into feature2d again
- re-enable all FeatureDetectors and DescriptorExtractors for use in java bindings

This fork will not be maintained, it was just to get the wanted functionalities back.

------------------------------------------------------------------------------------------

### OpenCV: Open Source Computer Vision Library

[![Gittip](http://img.shields.io/gittip/OpenCV.png)](https://www.gittip.com/OpenCV/)

#### Resources

* Homepage: <http://opencv.org>
* Docs: <http://docs.opencv.org>
* Q&A forum: <http://answers.opencv.org>
* Issue tracking: <http://code.opencv.org>

#### Contributing

Please read before starting work on a pull request: <http://code.opencv.org/projects/opencv/wiki/How_to_contribute>

Summary of guidelines:

* One pull request per issue;
* Choose the right base branch;
* Include tests and documentation;
* Clean up "oops" commits before submitting;
* Follow the coding style guide.
