# Topics Covered in DevOps Course

Throughout the course, I have learnt numerous topics in the field of DevOps pertaining to the streamling of development and deployment. DevOps taught me how to use various tools such as Kubernetes, Helm and Istio to help automate and maintain various software solutions. Below are some of the topics covered in my course:

## Docker

Docker is platform that is used to simplify the process of deploying applications through containerization. Containerization is when all the conponents needed in an application are packaged together in a lightweight space. This package contains all the software's dependencies, meaning it can run in any environment that it is deployed in without irregularities.

## Kubernetes

Kubernetes is a platform that is used to managed containerized applications to enhance and automate deployment. It contains tools to scale applications, ensure availability in case of interruptions, manage resources efficiently, provide security and more, all done automatically. Using kubernetes a developer can focus more on development instead of micromanaging deployed softwares.

## Istio

When depolying a distributed system you run the issues of having multiple different services communicating with one another while maintianing security and managing traffic. Here is where Istio comes in as a service mesh that allows controlling, securing and detailing of these various communications. It can provide a way to control traffic which can be especially useful when deploying updates to running systems. Encryption is also a feature to maintain security in these communications, useful for privacy heavy systems. To identify any faults in a system, Istio provides fault injection to see how a systems responds in various scenarios. Istio can also maintain a detailed log on communications in oder to identfiy any sources of faults.

## Helm

Helm is a package manager for Kubernetes that simplifies the deploying and managing Kubernetes applications. It does this by packaging the application in a standardized chart which contains the applications configurations. These charts are easy to upgrade and even version should you wish to rollback to previous iteration of an application. Essentially these charts serve as a template for the application through a collection of yaml files that contain configurations and dependencies.

## CI/CD and Jenkins

CI/CD is the practice of continuous integration and deployment in software development that aims to speed up the software development cycle. CI, continuous integration, is when code is placed into a single shared repository that multiple developers work on. This allows any changes to the the code to be integrated immediately without needed to merge individual code blocks. Whenever code is integrated, it is immediately compiled and tested for any errors. CD, continuous deployment, occurs after all automated testing has completed, the build is then deployed to end users so that real time feedback can occur. This can speed up the process of further improving the next build, and releasing the software into the market. CI/CD is implemented through a pipleline containing all the various steps that need to be completed for development.

Jenkins is a Kubernetes tool created to simplify this practice by automating the more tedius and repetitive parts of development. Although Jenkins can be complex to set up and potentially costly, it is a powerful tool to automate what would normally be a manual process.



