# Generate dynamic configurations with Okteto

This sample shows how to configure an okteto pipeline to generate a dynamic configuration file with values coming from the pipeline's context and from developer-defined Okteto variables.

To try it:
1. Login to Okteto, and [add a variable](https://cloud.okteto.com/#/settings/variables) called `MY_NAME` with your name.
2. Click [here](https://cloud.okteto.com/deploy?repository=https://github.com/okteto/pipeline-with-generated-variables) to deploy the pipeline defined in the `okteto-pipeline.yaml` file.
3. Check the applications logs and verify that the right values are printed.
