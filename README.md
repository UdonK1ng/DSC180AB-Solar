
# Background
  Perovskite cells are hailed as the next generation of solar cells that can potentially be more effective than traditional and widely used silicon cells.  One drawback to this is they tend to degrade at a much faster rate than the current silicon cells when under direct sunlight. 
  Dr. Fenning's lab employs an experimental method involving various samples of perovskite
film using different synthesis conditions and testing them under accelerated conditions –
intense sunlight and high temperatures – to track degradation speed of these films. The
challenge is that these experiments can last for weeks to months before conclusions are
clear regarding the synthesis conditions influencing degradation and how to design meaningful future experiments. A potential solution is to train a machine-learning model on past
experiments so we can learn which factors significantly impact film degradation and how
to optimize cell production for longer durability. Our project first created a pipeline that puts any new data daily into the graph database so it can be explored further, and another pipeline that performs the machine learning on the data from the graph database. 
# Data Description
  Our current data set currently contains 147 samples. Each sample includes different chemical compositions, manufacturing steps, solutes, and solvents. 
# Methods
Image Processing:
We are measuring the color change from black to yellow, where yellow is completely degraded. Here is a timelapse of the degredation process:

<video width="630" height="300" src="https://github.com/UdonK1ng/DSC180AB-Solar/assets/97561013/1c720849-723c-4f16-bc06-93d2ee27b3bd"></video>


# Results
# Future Work
  Future work involves adding more data to our database in order to make our machine learning models more accurate. We also want to figure out whether parameters x0 and k are independent or can a model be built that predicts both parameters. 
# Acknowledgements
Special thanks to Prof David Fenning and SOLEIL member Deniz Cakan for resources and guidance on our project!

