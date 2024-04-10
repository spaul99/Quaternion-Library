This is a very basic quaternion library for transformation between quaternion, Rotation matrix, Euler angle and many more. It have the following conversion abilitys,

Axis and angle to quaternion using the function 'axisAngle2quatern(axis, angle)'

Axis and angle to Rotation matrix using the function 'axisAngle2rotMat(axis, angle)'

Euler angle to Rotation matrix using the function 'euler2rotMat(phi, theta, psi)'

Quaternion to euler angle using the function 'quatern2euler(q)'

Quaternion to Rotation matrix using the function 'quatern2rotMat(q)'

Converts a quaternion to its conjugate using the function 'quaternConj(q)'

Calculates the quaternion product of quaternion a and b using the function 'quaternProd(a, b)'

Rotation matrix to Euler angle using the function 'rotMat2euler(R)'

Rotation matrix to quaternion using the function 'rotMat2quatern(R)'


Input & Output Datatypes

Angles:	Radian(float)

Quaternion: array[qw,qx,qy,qz]

Axis: array[x,y,z]

Rotation Matrix: In (3x3) matrix/array form Like,

$$
R =
\left(\begin{array}{cc}
R11 & R12 & R13 \\
R21 & R22 & R23 \\
R31 & R32 & R33
\end{array}\right)