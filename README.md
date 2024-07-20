# MetamericLight

Contact: e.gecer@tue.nl

Abstract: Light does not only allow the visual system to perceive the outside world but also 
impact humans in non-visual ways such as in their physiology and psychology. To be able to 
understand and quantify effect of light on humans, we need sophisticated light designs that allow 
us to test with utmost precision in targeting desired photoreceptors. Experiments testing for 
effects of light on humans have the caveat of using visually distinguishable light that does not 
control for the activation of other photoreceptors than the desired one, making it hard to 
distinguish potentially different systems at interplay. In this paper we are proposing an 
algorithmic approach using the principles of Silent Substitution and formulating it as an 
optimization problem to help researchers calculate metameric light pairs efficiently. 

Method:
The optimization problem consists of maximizing the contrast for the desired photoreceptor and 
involves several boundary conditions to ensure that metamers match in terms of other qualities such as 
cone activation, illuminance, different degrees of colour coordinates, colour temperature, distance to 
the black body radiation. Once the calibration measurements for individual LEDs are collected receptor 
specific irradiances are calculated by alpha-opic toolbox and divided by the full-range of intensity 
values [6]. These increments per photoreceptor irradiances served as the parameter for our objective 
function represented by mLED in the Equation (1)
