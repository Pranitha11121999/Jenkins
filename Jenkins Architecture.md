Jenkins Architrcture:
It consists of 
1.Jnekins Controller Node - Central Hub ofen refered as Jenkins Server or Master Mind 
  - Plugins
  - Jobs
  - Nodes
  - credetials
  - Configurations

  TASK done by Jenkins Controller 
    1. Task Management - user authentication and authorization
    2. Manage JObs and Pipelines 
    3. Provide Web Interface - for configurations, setting up Plugins, Onboarding Users, and monitoring and managing the build within Jenkins.

  Basic Deplyment - controller and working are same 
  - its recommended to have controller and worker node- because of the security, speed and efficiency. It can also help to scalre the jenkins server as the automation aneeds increases
Nodes :
- Servers as worker machines that exexute the task     
- Connect with the ssh
- Configurational ammount of executal - which help with the execution and the number of executors help us to identify that ammount of parallelism that can be done

Agents
- Extention on jenkins that uses executors on a remote node
- 
