# DevOps-Notes
Let's learn DevOps together free and simple

# DevOps

![458156574_8228612993887856_6048930979761790545_n](https://github.com/user-attachments/assets/0db0e091-2d08-433a-886c-8fae9eff498e)


# What is DevOps?

DevOps is a software development methodology that prioritizes automation, continuous delivery, and collaboration to deliver high-quality products to clients in a timely and effective manner. DevOps facilitates smoother communication, quicker time-to-market, and more customer satisfaction by dismantling communication gap between the development and operations teams.

The full application lifecycle—from development to testing, operations, and deployment—can be managed by a team using this method. Code is swiftly and reliably deployed to production through automation and repeatability, demonstrating collaboration between the Development and Operations teams.

In DevOps, every stage of the software development lifecycle—from planning to coding to testing to deployment and monitoring—is highly automated. As a result, the development process is more productive, consistent, and has fewer errors. DevOps encourages a continuous improvement culture as well, incorporating feedback loops into the process to speed up iterations and improve decision-making. Adopting DevOps can help organizations become more agile, reduce expenses, and innovate more quickly.

# Why DevOps?

The goal of DevOps is to increase an organization’s speed when it comes to delivering applications and services.

# Responsibilities

Build and Maintain tools: Develop and oversee the use of tools that streamline the deployment and development of software.

Collaborate with Teams: Work closely with software developers and IT staff to ensure smooth and fast delivery of applications.

Monitor systems: Monitor system performance and address any problems to make sure everything functions as it should.

Improve processes: Always be on the lookout for methods to improve the efficiency of the software development and deployment processes.

Ensure Security: Implement practices to keep systems secure from potential threats.

# How DevOps Works?

The DevOps Lifecycle divides the SDLC lifecycle into the following stages:

![11](https://github.com/user-attachments/assets/d6a10a39-2bc0-4be8-becc-7e67cc96950b)

![12](https://github.com/user-attachments/assets/e92061a7-42fe-47bf-9137-b3fdb62a5513)


# 1. Continuous Development: 

Continuous Development is important for DevOps because it increases productivity each time a piece of code is developed, tested, built, and put into production. Code is written in small, continuous pieces rather than all at once. Continuous Development improves the code's quality and speeds up the process of fixing errors, vulnerabilities, and faults. It makes it easier for developers to focus on writing excellent code.

![Code-developing](https://github.com/user-attachments/assets/086c7d6f-2167-4c0a-92b9-bfd095163024)


# 2. Continuous Integration:

In DevOps, there are four primary stages that describe continuous integration. They are listed in the following order:

1. Obtaining SourceCode using SCM
2. Constructing the code 
3. Code quality assessment
4. The building of artifacts' storage

The Continuous Integration flow consists of the stages listed above. We can use any tool that best fits our needs at each stage, and one of the most widely used tools is GitHub for source code management (SCM). As a developer writes code on his local computer, he pushes it to GitHub, a remote repository from which anyone with access can pull, clone, and edit the code as needed.From there, we can test the Junit scenarios and build them into the necessary package (war, jar, and ear) using Maven.When SonarQube does code quality reviews, it evaluates the source code's quality and produces a report in HTML or PDF format. Jenkins, a continuous integration tool, is used throughout the process to create the build artifacts, and Nexus will assist us in storing the artifacts created with Maven.

![DevOps-Flow-2](https://github.com/user-attachments/assets/830f027c-ba07-4362-8379-c24eea9bb8b3)

# 3. Continuous Testing:

Continuous testing can be implemented by any organization using the agile and DevOps approaches. Testsigma, Selenium, LambdaTest, and other automation testing tools can be used for continuous testing, depending on our needs. These technologies allow us to test our code quicker and intelligently, as well as prevent issues and code smells. An additional advantage is that the entire process may be automated with the help of a continuous integration platform like Jenkins.

![continuous-testing](https://github.com/user-attachments/assets/b0b041be-7e3b-48cc-967a-268a77a04389)


# 4. Continuous Deployment/Continuous Delivery

The technique of automatically delivering an application into the production environment when it has finished the build and testing phases is known as continuous deployment. Everything from getting the source code of the application to deploying it will be automated in this case.

![continuous-delivery-1](https://github.com/user-attachments/assets/db6c33f5-6b26-401a-aaab-07bda69b9326)

# Continuous Delivery

Continuous Delivery refers to the process of manually deploying an application into production servers when it has finished the construction and testing phases. Although the continuous integration processes      will now be automated, manual intervention is still necessary to deploy it to the production environment.

![continuous-delivery-2](https://github.com/user-attachments/assets/9c755063-2bc6-4e8a-8915-d81f0804a071)

![DevOps-Flow-1](https://github.com/user-attachments/assets/42556cf8-4ff4-4710-b19c-d6584de0a5ed)



# 5. Continuous Monitoring: 

If continuous monitoring is excluded from the DevOps lifecycle, it is incomplete. Prometheus and Grafana enable continuous monitoring, allowing us to keep an eye on things and receive alerts before they get out of hand. We may collect a wide range of performance metrics with Prometheus' assistance, such as error rates, network traffic, CPU and memory usage, and application response times. Data from time series, such as CPU and memory consumption, can be visually represented and tracked with Grafana.

# 6. Continuous Feedback

After the program is made available to the public, end users will utilize it and, after providing us with several feedbacks, will let us know how well it performs and if there are any bugs that negatively impact the user experience. In order to reduce errors or bugs in the code we are currently developing and to produce much more effective results for end users, the DevOps team will analyze the feedback provided by end users and then reach out to the development team to try and rectify any mistakes they may have made. Additionally, we will eliminate any needless steps involved in deploying the application. Constant Feedback can improve the application's functionality and lower the number of bugs in the code making it smooth for end users to use the application.

# 7. Continuous Operation:

By introducing continuous operation, we will be able to maintain the better application uptime while reducing maintenance downtime that could negatively affect end users' experiences. Continuous operations lead to improved quality control, reduced production costs, and increased productivity.



