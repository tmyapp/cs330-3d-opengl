# cs330-3d-opengl
This project was developed for CS 330: Computational Graphics and Visualization. The application renders an interactive 3D scene using OpenGL and demonstrates core graphics programming concepts including geometric modeling, texture mapping, lighting, camera navigation, and projection control.

The scene features a multi-part object constructed from primitive shapes placed on a textured surface. The project emphasizes low-polygon modeling combined with realistic lighting and shading techniques.

_____

Features
	•	Multi-primitive 3D object (cylinder, sphere, cone)
	•	Textured floor and objects (wood, brick, marble)
	•	Phong lighting model (ambient, diffuse, specular)
	•	Multiple light sources:
	•	Directional light
	•	Point light
	•	Colored accent light
	•	Specular highlights for realistic surface response
	•	Interactive camera controls
	•	Perspective and Orthographic projection toggle

_____

Controls
Key - Function
W/A/S/D - Move camera forward, left, backward, right
Q/E - Move camera up and down
Mouse - Adjust camera yaw and pitch
Scroll Wheel - Adjust movement speed
P - Switch to Perspective projection
O - Swith to Orthographic projection

_____

Technologies Used
	•	C++
	•	OpenGL
	•	GLSL (Vertex and Fragment Shaders)
	•	GLM (OpenGL Mathematics Library)

_____

Rendering Techniques Demonstrated

Geometric Modeling

The main object is built using multiple primitive shapes positioned and scaled using transformation matrices.

Texture Mapping

UV coordinates are used to properly project textures onto surfaces. The floor uses UV scaling to repeat the texture pattern.

Lighting Model

The scene implements the Phong shading model including:
	•	Ambient lighting
	•	Diffuse lighting
	•	Specular highlights

Multiple light sources are used to create depth and visual interest, including a colored point light.

Camera System

The camera supports full 3D navigation across the X, Y, and Z axes with mouse-based orientation control.

Projection Modes

The application allows dynamic switching between:
	•	Perspective projection
	•	Orthographic projection

_____

Project Structure
	•	SceneManager – Manages rendering, textures, lighting, and transformations
	•	ShaderManager – Handles shader compilation and uniform updates
	•	ShapeMeshes – Contains reusable primitive geometry
	•	shaders/ – GLSL vertex and fragment shader files
	•	textures/ – Image files used for texture mapping

_____

Purpose

This project demonstrates the ability to create an interactive 3D visualization using modern OpenGL practices, modular code design, and real-time rendering techniques.
