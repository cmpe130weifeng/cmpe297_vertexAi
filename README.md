# cmpe297_vertexAi
Do one end2end toy example full ml ops maturity level 4 pipeline end2end and show case all the details with demo presentation/video showcasing the deployment of model, auto deployment of the next trained model with prper monitoring of drift as well as skew as well verification/validation step.
</br>

</br>
I use Vertex Ai as the platform for this exercise. Vertex AI Pipeline is a product to run pipeline serverless. We use the pipeline toolkit, Kubeflow. Kubeflow is a machine learning toolkit. We build components(a component = a specific task; in the basic sample i provided, component just a function/method; but in the full demo, a component can be a whole meachine learning proecess, it can be a data preprocessing, a modeling, a training process, or others). We put all components into pipeline, and then run our pipeline using compiler. After you ran, you would get a output file (Json file). The Json file is like the "zip" file of our pipeline, it contains our components' "soul". We use the Json file as pipeline for Vertex Ai, it automatically does everything for endtoend. Pipeline is like a blackbox, you has no idea what it does inside, but it does everthing for you. You only need to take care of is your inputs and outputs.
</br>
</br>
Basic demo: https://youtu.be/skvLKqEiGvg </br>
</br>
Full demo: https://youtu.be/wymvzOvcHvA </br>
</br>
</br>
Driver folder for all colab files: https://drive.google.com/drive/folders/1t31qgJq99EUixGM-93BiyjsUzFvlFBmx </br>
</br>
</br>
</br>
Reference: </br>
[1] https://codelabs.developers.google.com/vertex-pipelines-intro#3 </br>
[2] https://github.com/microsoft/MLOps </br>
[3] https://github.com/solliancenet/Azure-Machine-Learning-Dev-Guide/blob/master/devops-for-ai/e2e-pipeline-code-sample.md </br>
[4] https://github.com/davew-msft/MLOps-E2E  </br>
[5] https://ml-devops-tutorial.readthedocs.io/en/latest/endtoend.html </br>
[6] https://github.com/GoogleCloudPlatform/mlops-with-vertex-ai </br>
[7] https://cloud.google.com/blog/topics/developers-practitioners/mlops-system-automl-and-pipeline-vertex-ai </br>


