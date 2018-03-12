<strong>Satellite Image Recognition</strong></br>
</br>
Problem Description: Drifting icebergs present threats to navigation and activities in areas such as offshore of the East Coast of Canada.
</br>
Currently, many institutions and companies use aerial reconnaissance and shore-based support to monitor environmental conditions and assess risks from icebergs. However, in remote areas with particularly harsh weather, these methods are not feasible, and the only viable monitoring option is via satellite.</br>
The remote sensing systems used to detect icebergs are housed on satellites over 600 kilometers above the Earth. The Sentinel-1 satellite constellation is used to monitor Land and Ocean. Orbiting 14 times a day, the satellite captures images of the Earth's surface at a given location, at a given instant in time. The C-Band radar operates at a frequency that "sees" through darkness, rain, cloud and even fog. Since it emits it's own energy source it can capture images day or night.</br>
The objects in the image can be visually classified. But in an image with hundreds of objects, this is very time consuming. </br></br>
Task: With given satellite image data, build an algorithm that automatically identifies if a remotely sensed target is a ship or iceberg.</br>
</br>
In this project we adopted data processing techniques, such as reshaping, normalization and augmentation. And we used a pre-trained VGG16 model from Keras with modification to suit our situation. The cross entropy we get is 0.1713.
It takes about 30 minutes to do the process and classification on a K80 GPU on Google Cloud Platform.</br>
For more details, please view the project report.

