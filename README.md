# AirBnB Pinger

Get notified for new search results on AirBnB.

### Implementing the AirBnB Pinger

So, this is a really simple task => we can go serverless.

#### Steps

-   [x] (0) Setup
    -   [x] [install serverless](https://serverless.com/framework/docs/providers/aws/guide/installation/)
    -   [x] [add aws credentials](https://serverless.com/framework/docs/providers/aws/guide/credentials/)
        -   I had have them in my `env`.
-   [ ] (1) Hello World!
    -   [x] [node example hello world](https://serverless.com/framework/docs/providers/aws/examples/hello-world/node/)
    -   [ ] capture the AirBnB search result
    -   [ ] use curl, or puppeteer, or screenshot
-   [ ] (2) Storage
    -   [ ] [aws fetch and store](https://serverless.com/examples/aws-node-fetch-file-and-store-in-s3/)
-   [ ] (3) compare it to a previous version
-   [ ] (4) notify if different
    -   [ ] need to _define_ different
    -   [ ] [upload => post-process](https://serverless.com/examples/aws-node-upload-to-s3-and-postprocess/)
-   [ ] (5) repeat
    -   [ ] [aws cron](https://serverless.com/examples/aws-python-scheduled-cron/)

#### Optional

-   (a) settings
    -   [env variables](https://serverless.com/examples/aws-node-env-variables/)
    -   [encrypted env variables](https://serverless.com/examples/aws-node-env-variables-encrypted-in-a-file/)
