+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Drone++"

# Project summary to display on homepage.
summary = "A custom Human Machine Interface that controls a drone. "

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "kinect.jpeg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["drones", "robotics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "kinect.jpeg"
caption = "Microsoft Kinect"

+++

My work with drones started in high school with the Parrot A.R. Drone and the Kinect SDK in C#. From then, I have written and rewritten extensions on the project in Java, Python, Node.js and MATLAB. And I have also interfaced the drone with different types of hardware including the LEAP motion.

C# + KINECT

In high school, to complete my schools honors program requirement, we were required to complete a design project of our own with the guidance of a member of faculty. The only real requirement to the project is that it shows our interest in the subject. So I built a system that controls a quad-coptor through inputs from the Microsoft Kinect Sensor.

<!-- ![Drone In Action](/img/Drone-In-Action.png) -->
<!-- https://www.youtube.com/watch?v=&feature=youtu.be -->
{{< youtube 1bWKtaloclM >}}
MATLAB + KINECT

I rewrote the drone controller and kinect interface using MATLAB. I chose to change platforms because I was looking for more robust control over the hardware and to easily apply higher level processing (image processing, basic AI)

The ARDrone controller can be found on my github page
<!-- {{< gist hege0110 fcc61ae7d793c4eba30218560ab17aba >}} -->
<!-- <script src="https://gist.github.com/hege0110/fcc61ae7d793c4eba30218560ab17aba.js"></script> -->
[MATLAB Drone](https://github.com/hege0110/matlab-drone)
