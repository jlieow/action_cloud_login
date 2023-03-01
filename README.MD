Logs in to AWS, Azure and GCP with their respective CLI

Example:

```
- name: Logs in to AWS
  id: cloud_login
  uses: jlieow/action_cloud_login@V1 # Uses an action in the repo terraformx_apply owned by jlieow tagged as V1
  with:
    cloud_env: INPUT_CLOUD_ENV (Logs in to Cloud. Accepted values are AWS, AZURE and GCP) 
    aws_access_key_id: INPUT_AWS_ACCESS_KEY_ID
    aws_secret_access_key: INPUT_AWS_SECRET_ACCESS_KEY
    profile_name: INPUT_PROFILE_NAME
```
