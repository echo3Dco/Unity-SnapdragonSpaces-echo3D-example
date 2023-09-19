# Snapdragon Spaces & echo3D

Adding echo3D to Snapdragon Spaces SDK sample

## Register
Don't have an API key? Make sure to register for FREE at [echo3D](https://console.echo3D.co/#/auth/register).

## Getting Started
To see how echo3D works with the Spaces Unity SDK, you can either clone this project, or follow this guide:
* Open the sample project that arrives with the [Spaces Unity package](https://docs.spaces.qualcomm.com/unity/setup/SetupGuideUnity.html) and open the [Hand Tracking Sample](https://docs.spaces.qualcomm.com/unity/samples/HandTrackingSample.html) scene.
* Export the Mirror and Player objects from the models folder of the scene located in [here](/Assets/Samples/Snapdragon%20Spaces/0.7.0/Core%20Samples/Scenes/Hand%20Tracking%20Sample/Models). To export, right click on the model, then choose "Export glTF" and choose glTF-Binary. Alternatively, you can use the models in our [_Models_ folder](/Models/)
* Upload the exported files to your echo3D project.
* [Add the metadata](https://docs.echo3D.co/web-console/manage-pages/data-page/how-to-add-data#adding-metadata). You can use the data files in our [_Data_ folder](/Data/)
* [Install the echo3D Unity SDK](https://docs.echo3D.co/unity/installation).
* [Set the API key](https://docs.echo3D.co/unity/using-the-sdk) in the Inspector of the echo3D game object. In the tags filed, write "handTracking".
* Disable the Mirror and Player objects in your unity scene.<br>
![Mirror Disable](/Screenshots/Unity-spaces%20sample-%20no%20models.png)

## Run
Simply press the _Play_ button in Unity.

## Screenshots
![echo3D Models](/Screenshots/echo3D-console.png)
![echo3D Additional Data](/Screenshots/echo3D-additional%20data.png)
![Unity screenshots 1](/Screenshots/Snapshot_59.PNG)
![Unity screenshots 2](/Screenshots/Snapshot_60.PNG)
