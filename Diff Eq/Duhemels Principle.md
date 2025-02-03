### Example
#### Step 1
$\frac{dy}{dt}=\frac{1}{t^2}y+t^2$
$(\frac{dy}{dt}-\frac{1}{t^2}y)=t^2$
$(\frac{d}{dt}-\frac{1}{t^2})y=t^2$
Solve: $\frac{dy}{dt}=\frac{1}{t^2}y$
$ln|y|=-\frac{1}{t}+C$
$y=Ce^{-\frac{1}{t}}$

#### Step 2:
$y_s(s)=s^2ds$
$y_s(t)$ solves IVP
$\frac{dy}{dt}=\frac{1}{t^2}y$
$y_s(s)=s^2ds$
$s^2ds=y_s(s)=Ce^{-\frac{1}{s}}$
$y_s(t)=e^{\frac{1}{s}}e^{-\frac{1}{t}}s^2ds$
$C=e^{\frac{1}{s}}s^2ds$
$y(t)=\int_{t_0}^te^{\frac{1}{s}-\frac{1}{t}}s^2ds$

#### Step 3:
$y(t)=Ce^{-\frac{1}{t}}+\int_{t_0}^te^{\frac{1}{s}-\frac{1}{t}}s^2ds$

