# Jenkins Master Slave pipeline
## Build project accessed from:
https://github.com/parvatijay2901/devopsIQ
## Steps:
1. Create Jenkins Master-Slave instances on AWS.
2. Install Jenkins on the master node.
3. Create the slaves’ nodes on dashboard and copy the agent.jar file to both the slaves.
4. Install Java and docker on both the slaves.
5. Connect Agent to Jenkins using JNLP connection.
6. Create and build projects.
7. Configure Jenkins to build the project on Slave 1. If the step was successful, Test2 should be built on Slave 2.
8. Trigger the job using git web-hooks.
