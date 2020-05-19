# 2DMonogameSoftbody
Experiment with creating a 2D softbody in C# for Monogame. Adapted from Maciej Matyka's paper, "How to Implement Pressure Soft Body Model" -   http://panoramx.ift.uni.wroc.pl/~maq/eng/index.php.

If the simulation does not appear, you may need to install the Monogame framework, the downloads and instructions for which can be found at https://www.monogame.net/.

In order to see the simulation, Open "2DMonogameSoftBody.sln using VisualStudio and hit Play. To adjust the parameters of the soft body, change the values inside the SoftBody constructor of the Initialize method in "SoftBodyGame.cs". Extremely high values may cause the softbody to react violently.
