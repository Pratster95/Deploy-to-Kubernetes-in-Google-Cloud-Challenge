<h5>Continuation from Task 2</h4>

<h4>Push the Docker image from the previous task in the Container Repository</h5>

**Execute all the these commands in the Google Cloud Shell:** <br>
1. cd .. <br>
2. cd valkyrie-app <br>
3. docker tag valkyrie-app:v0.0.1 gcr.io/$GOOGLE_CLOUD_PROJECT/valkyrie-app:v0.0.1 <br>
4. docker push gcr.io/$GOOGLE_CLOUD_PROJECT/valkyrie-app:v0.0.1 <br>

