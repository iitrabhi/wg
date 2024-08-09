## Comprehensive Guidelines for Mathematical Typesetting in Scientific Writing

### **Font Usage and Symbol Distinctions**
The following points outline how different types of mathematical entities should be formatted to ensure clarity and distinction in scientific documents:

1. **Variables in Italic Font**
   - Variables such as $t$, $T$, $m$, etc., are written in italic. This style distinguishes them as mathematical entities that represent quantities which can vary or hold specific values in equations.
   - **Example**: In the acceleration formula $a = \frac{dv}{dt}$, both $v$ (velocity) and $t$ (time) are in italics.

2. **Bold Symbols for Different Entities**
   - Symbols in bold, such as $\mathbf{m}$, often represent matrices or vectors, which are distinct from scalar variables.
   - **Example**: In vector notation $\mathbf{m} = \begin{bmatrix} m_1 \\ m_2 \\ m_3 \end{bmatrix}$, $\mathbf{m}$ represents a vector.

3. **Real Numbers and Constants in Regular Font**
   - Real numbers and constants are written in regular, non-italic font to differentiate them from variables.
   - **Example**: The number $\pi$ is often shown in regular font: $\text{Circumference} = 2\pi r$.

4. **Units in Regular Font**
   - Units such as meters (m), seconds (s), etc., are written in regular font to clearly separate them from variable names.
   - **Example**: In the force formula $F = ma$, "kg" for kilograms is in regular font.

5. **Functions in Regular Font**
   - Mathematical functions like sin, cos, log, etc., are written in regular font.
   - **Example**: In the sine function $y = \sin(x)$.

6. **Matrices in Bold Font**
   - Matrices are always in bold and never italicized or slanted.
   - **Example**: For a matrix $\mathbf{A} = \begin{bmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{bmatrix}$.

### **Case Sensitivity in Units**
It is crucial not to capitalize units improperly as it changes their meaning:

- Incorrect capitalization like "Kg" instead of "kg" would imply Kelvin multiplied by grams, which is incorrect. Proper use of case in units ensures the correct interpretation of scientific data.

| **Unit** | **Correct Usage** | **Incorrect Usage** | **Implication of Incorrect Usage** |
|----------|-------------------|---------------------|------------------------------------|
| Kilogram | kg                | Kg                  | Kg could be misinterpreted as Kelvin multiplied by gram. |
| Meter    | m                 | M                   | M is a prefix for mega (\(10^6\)), not meter. |
| Second   | s                 | S                   | S denotes Siemens, a unit of electrical conductance. |
| Ampere   | A                 | a (if used incorrectly) | "a" isn't used, but small case could confuse as it isn't standard. |
| Watt     | W                 | w                   | Lowercase "w" is not standard and can lead to confusion. |
| Newton   | N                 | n                   | Lowercase "n" could be mistaken for nano when used as a prefix. |
| Joule    | J                 | j                   | Lowercase "j" is not recognized as the standard unit for energy. |
| Volt     | V                 | v                   | Lowercase "v" could lead to confusion as it isn't the standard symbol. |
| Gram     | g                 | G                   | G often represents the gravitational constant in physics. |


### **Examples of Guidelines in Use**
These examples illustrate how the guidelines are applied in scientific formulas and equations:

1. **Variable and Unit Distinction**
   - **Example**: $m = (250.0 \frac{a}{m}) \, \text{kg}$ shows $m$ as a mass variable in italic, $a$ as a length variable in italic, and $m$ in the fraction as meters in regular font.

2. **Gradient and Divergence Operations**
   - **Gradient of a Vector Field $\mathbf{u}$**:
     $$
     \nabla \mathbf{u} = \begin{bmatrix} 
     \frac{\partial u_1}{\partial x_1} & \cdots & \frac{\partial u_1}{\partial x_d} \\
     \vdots & \ddots & \vdots \\
     \frac{\partial u_d}{\partial x_1} & \cdots & \frac{\partial u_d}{\partial x_d}
     \end{bmatrix}
     $$
     This tensor contains all partial derivatives of a vector field $\mathbf{u}$, showing the vector's change across different dimensions.
   - **Divergence of a Second-Rank Tensor $\boldsymbol{\sigma}$**:
     $$
     \nabla \cdot \boldsymbol{\sigma} = (\nabla \cdot \sigma_1, \ldots, \nabla \cdot \sigma_d)^T
     $$
     This operation computes the divergence of each row in the tensor $\boldsymbol{\sigma}$, providing a vector field of divergences.



