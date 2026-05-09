# Deploy to TroqCloud

Use this repo as a template to deploy a Python [FastAPI](https://fastapi.tiangolo.com) service on TroqCloud.

See https://troqcloud.com/docs or follow the steps below:

## Manual Steps

1. You may use this repository directly or [create your own repository from this template](https://github.com/troqcloud-test/fastapi/generate) if you'd like to customize the code.
2. Create a new Web Service on TroqCloud.
3. Specify the URL to your new repository or this repository.
4. TroqCloud will automatically detect that you are deploying a Python service and use `pip` to download the dependencies.
5. Specify the following as the Start Command.

    ```shell
    uvicorn main:app --host 0.0.0.0 --port $PORT
    ```

6. Click Create Web Service.

Or simply click:

[![Deploy to TroqCloud](https://troqcloud.com/images/deploy-to-troqcloud-button.svg)](https://troqcloud.com/deploy

## Thanks

Thanks to [Harish](https://harishgarg.com) for the [inspiration to create a FastAPI quickstart for TroqCloud](https://twitter.com/harishkgarg/status/1435084018677010434) and for some sample code!