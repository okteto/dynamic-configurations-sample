# Generate dynamic configurations with Okteto

This sample shows how to configure an okteto pipeline to generate a dynamic configuration file with values coming from the pipeline's context and from developer-defined Okteto Secrets. 

To try it:
1. Login to Okteto, and [add a secret](https://cloud.okteto.com/#/secrets) called "MY_NAME".
2. [Deploy your pipeline](https://cloud.okteto.com/deploy?repository=https://github.com/okteto/pipeline-with-generated-secrets).
3. Verify that the right values are printed in the application logs.
