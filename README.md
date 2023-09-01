# DrakeTutorials
Trying to put together a bunch of minimal working examples for 'RobotLocomotion/drake' Model-Based Design and Verification for Robotics.

All Tutorials in this Repo will be in Python.

I am targetting new users, as it can be quite difficult to start diving in.


Starting with:

- Exhaustive Look into the functions in each Namespace, with minimal working examples in Python
       Everything from how to call AutoDiffXD version of math.sin() to setting up a LeafSystem...

#### 001 : Load via Mujoco, URDF, SDF, Build manipulator equations,
         
#### 002  : Multibody plant: setup and Python API

#### 003 : Meshcat Raw Interface
- It's quite an eyesore, but we change the environment map and add a bunch of objects to a Drake scene. This is just a quick overview of the raw Meshcat interface through Drake with a SceneGraph or plant...
  
<p align="center">
<img src="https://github.com/drewhamiltonasdf/DrakeTutorials/blob/main/imgs/meshcat.png"> 
</p>
        
#### 004 : Hybrid System (WitnessFunction) with Unusual Discrete-time Map
<p align="center">
<img src="https://github.com/drewhamiltonasdf/DrakeTutorials/blob/main/imgs/UnusualHybridSystem.png"> 
</p>

#### 005: Hybrid System (WitnessFunction) & Meshcat
- Here, we just focus on the bare minimum to set up a Hybrid Plant with LeafSystem. We visualize this in meshcat without tapping into SceneGraph. In the next tutorial we layer in SceneGraph.

#### 006: Using SceneGraph & Meshcat with Hybrid System
<p align="center">
<img src="https://github.com/drewhamiltonasdf/DrakeTutorials/blob/main/imgs/HybridSystem.png"> 
</p>
