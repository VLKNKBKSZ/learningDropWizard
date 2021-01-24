# learningDropWizard

This repository is using the https://www.dropwizard.io/en/latest/getting-started.html as a start point.
I managed to make it work but there is one thing which still is a manual job.
After you run mvn package the fat jar will be in the target folder.
When you run java -jar fatjar.jar server hello-world.yml it will not found the yml file because it is not there.
For learning purposes i put it there by hand, but in prod you want to create a mvn-copy task for it.
