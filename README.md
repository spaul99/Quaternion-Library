# Quaternion Transformation Library

## Description
This is a simple quaternion library designed to facilitate transformation between quaternions, rotation matrices, Euler angles, and more. It provides the following conversion functionalities:

- **Axis and Angle to Quaternion:** Utilize the function `axisAngle2quatern(axis, angle)`
- **Axis and Angle to Rotation Matrix:** Employ the function `axisAngle2rotMat(axis, angle)`
- **Euler Angle to Rotation Matrix:** Utilize the function `euler2rotMat(phi, theta, psi)`
- **Quaternion to Euler Angle:** Utilize the function `quatern2euler(q)`
- **Quaternion to Rotation Matrix:** Employ the function `quatern2rotMat(q)`
- **Conjugate of a Quaternion:** Calculate the conjugate of a quaternion using the function `quaternConj(q)`
- **Quaternion Product:** Compute the quaternion product of quaternion `a` and `b` using the function `quaternProd(a, b)`
- **Rotation Matrix to Euler Angle:** Utilize the function `rotMat2euler(R)`
- **Rotation Matrix to Quaternion:** Employ the function `rotMat2quatern(R)`

## Installation
To get started run 
```sh
pip install quatlib
```
## Input & Output Data Types

For input and output, the library expects and provides the following data types:

- **Angles:** `Radian(float)`
- **Quaternion:** `Array` $$\mathbb{Q} = [qw, qx, qy, qz]$$
- **Axis:** Array `[x, y, z]`
- **Rotation Matrix:** `In (3x3) matrix/array form like:`

$$
R =
\left(\begin{array}{ccc}
R11 & R12 & R13 \\
R21 & R22 & R23 \\
R31 & R32 & R33
\end{array}\right)
$$

Feel free to utilize this library for your quaternion transformation needs.
