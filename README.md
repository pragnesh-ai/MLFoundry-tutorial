
# Mlfoundry Tutorial

What is MLFoundry?
As per the quoted definition of MLfoundy blog is "MLFoundry is world's first integrated experimented tracking & inference monitoring solution. Our client-side library allows you to log your experiments, models, metrics, data, features & predictions. Our interactive & intuitive dashboards allow you to track your Machine Learning models during development (experiment tracking) and post-deployment (inference monitoring)".

It can be divided into two-part.  
### Experiment Tracking:  
Helps you to create reproducible Machine Learning experiments and collaborate with your team by tracking your code, artifacts, hyperparameters & metrics all in one place. As of now, I have tested/Used this part in Mlfoundry which we will see in this blog.

### Inference Monitoring:
Helps you to track your model and feature health during inference. Supports model input/ output monitoring, feature drift and distribution tracking.
## Installation

Set up mlfoundry

Sign-up and login into your account(https://app.truefoundry.com/)  
Install mlfoundry library on your system.  
Login to the mlfoundry library on your system.
The CLI will prompt for an API key. Find your API key here(https://app.truefoundry.com/).
```bash     
pip install mlfoundry
```
    
## Usage/Examples

```javascript
import mlfoundry
mlfoundry.login()

client = mlfoundry.get_client()
run = client.create_run(project_name="First-wine-quality", run_name="first-run")
```

