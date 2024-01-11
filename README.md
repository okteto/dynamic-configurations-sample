# Generate dynamic configurations with Okteto

This sample shows how to configure an app with Okteto to generate a dynamic configuration at deploy time and from developer-defined [Okteto Variables](https://www.okteto.com/docs/manifest/okteto-variables/). 

To try it:
1. Login to your Okteto instance, and [add a variable](https://www.okteto.com/docs/manifest/okteto-variables/#manage-okteto-variables-from-the-okteto-dashboard) called `MY_NAME` with your name.
2. Deploy the application via the [deploy dialog](https://www.okteto.com/docs/1.17/deploy/deploy-from-git/#deploy), pointing to this Git repository.
3. Check the application's logs and verify that the right values are printed.
