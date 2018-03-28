# Unreal VR Course - Section 1 - Architecture Explorer

Section 1 of the GameDev.tv Unreal VR Course, [available on Udemy](http://gdev.tv/unrealvrgithuboffer). Understand the causes of VR sickness. Implement teleportation, play-space movement and controller movement. Navigate an architectural scene.

### 0 Course Promo ###

+ Why you should take the course.
+ We overview the journey.
+ What are the prerequisites?

### 1 Welcome And Course Orientation ###

+ How is the course structured?
+ How should I take the course?

### 2 Getting Into VR ###

+ What about mobile VR?
+ Supported hardware: Oculus Rift and HTC Vive.
+ Setting up our base project.
+ How head tracking works in Unreal.

### 3 Movement Section Overview ###

+ Overview of the syllabus for this section.
+ A sneak peak at the project we will make.
+ What you will get from this section.

### 4 Basic Controller Movement ###

+ Why we will use a character.
+ Finding the look direction.
+ Setup the characters movement.
+ The draw backs of controller movement.

### 5 Importing An ArchViz Environment ###

+ Importing a beautiful environment.
+ Why we shouldn't version these files.
+ Setup the `GameMode`.
+ Why do collisions behave strangely?

### 6 Playspace Movement and Colliders ###

+ How can we avoid the collision issue?
+ Adding a VR root component.
+ Aligning the camera to the capsule.

### 7 What Is VR Sickness? ###

+ Why do we feel VR sickness?
+ The sensory systems involved.
+ How do we fool our senses?
+ What are the limits of existing techniques.

### 8 Line Tracing A Teleport Destination ###

+ How does teleporting work?
+ Creating a destination marker.
+ Revision of Line Tracing in C++.
+ Positioning the destination with gaze.

### 9 Importing And Using Materials ###

+ Fixing the cylinder bug.
+ Importing a teleport material.
+ Showing/hiding the destination.

### 10 Fades, Timers and Teleporting ###

+ Setting up a teleport action.
+ Teleporting to the right location.
+ Fading the camera.
+ Setting a timer to fade up.

### 11 Projecting Onto The NavMesh ###

+ How can we constrain the teleport destination?
+ Setting up a NavMesh.
+ Projecting to the NavMesh.
+ A brief refactor.

### 12 PostProcessing Materials ###

+ What is a material?
+ Creating a post processing material.
+ Overview of the nodes we need.
+ Creating a tunnel vision effect.

### 13 Dynamic Material Instances ###

+ What are material parameters?
+ Setup a post processing component.
+ Dynamic vs static material instances.
+ Creating a material instance.

### 14 Adjusting Radius With A Curve ###

+ What is a curve?
+ Accessing a curve from C++.
+ Setting the radius from speed.

### 15 Creating Tunnel Vision ###

+ Where is the centre of movement?
+ Updating the blinker centre.
+ Projecting to the screen.
+ Getting the screen size.
+ Calculating the centre.

### 16 Hand Controller Components ###

+ Setup hand controller components.
+ Where are the hand controller meshes?
+ Teleporting with hand controllers.

### 17 Parabolic Teleport Pointer ###

+ Why use a parabolic path?
+ How do we trace a parabolic path?
+ Predicting a projectile in Unreal.

### 18 Using A USplineComponent ###

+ Adding to a spline component.
+ How the component works.
+ Previewing the spline in debug mode.
+ Setting the spline control points in C++.

### 19 Dynamically Constructing UObjects ##

+ Creating a new object.
+ Dynamically attaching components.
+ Why is `RegisterComponent()` important?
+ Setup meshes and materials.
+ Storing an object pool.

### 20 Deforming Meshes With Splines ###

+ What is a `USplineMeshComponent`?
+ Replacing the `UStaticMeshComponent`
+ Getting the spline tangents.
+ Tracing the spline.
+ Hiding extra meshes.

### 21 Extracting A Hand Controller Actor ###

+ Why should hand controllers be actors?
+ Spawn actors on BeginPlay.
+ Move `UMotionControllerComponent` into Actors.
+ Fix other build errors.
+ Create a Blueprint child actor.
