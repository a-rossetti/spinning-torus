# ASCII Spinning Torus

This project renders an animated ASCII representation of a spinning torus using C++. The torus rotates around both the Y and Z axes, creating a dynamic visual effect.

## Features

- **3D Rotation**: The torus rotates around both the Y and Z axes.
- **Perspective Projection**: Correct perspective projection ensures objects further away appear smaller.
- **Dynamic Lighting**: Surface normals provide depth and shading.

## Customization

Adjustable parameters:
- **Screen Dimensions**: `width`, `height`
- **Torus Radii**: `R1`, `R2`
- **Spacing**: `theta_spacing`, `phi_spacing`
- **Perspective**: `K1`, `K2`

## Visualization
<video width="600" controls autoplay>
  <source src="https://raw.githubusercontent.com/a-rossetti/spinning-torus/master/torus.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## License

This project is licensed under the MIT License.
