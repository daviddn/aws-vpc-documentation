# AWS

## Code Pipeline

![Pipeline](https://docs.aws.amazon.com/codepipeline/latest/userguide/images/PipelineFlow.png)

Code pipelining allows developers to automate their software deployment process. The process helps solve two of the main problems that DevOps Engineers generally work with:
- It works on my machine
- Code in the pipeline for 30 days.

## CI/CD

### Continuous Integration

Continuous Integration (CI) practices merging code developers' working code into a "master" repository several times throughout the code pipeline. The code being pushed has to be tested in the same environment, so that standardization can be achieved.

### Continuous Delivery

Continuous Delivery (CD) follows CI, where the code can be automatically tested in a staging environment. This approach ensures that developers get almost immediate feedback, therefore they can improve their software faster.

### Continuous Deployment

Continuous Deployment (CD) leads to the release of the code to the production environment, where it undergoes finally testing. After said testing, the code is ready to be released to the software's users.
