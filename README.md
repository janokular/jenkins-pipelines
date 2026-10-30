## Jenkins Pipelines
### Adding Jenkins Pipeline from this repository
  1. In Jenkins, select **New Item**.
  2. Enter a name for the job, such as **Example Pipeline**.
  3. Select **Pipeline**, then click **OK**.
  4. In the job configuration, find the Pipeline section.
  5. Set Definition to **Pipeline script from SCM**.
  6. Set SCM to **Git**.
  7. In Repository URL, enter `https://github.com/janokular/jenkins-pipelines.git`.
  8. Set Branch Specifier to `*/main`.
  9. Set Script Path to the path of the `path/inside/this/repo/Jenkinsfile` you want to use.
  10. Click **Save**, then select **Build Now** to run the pipeline.
