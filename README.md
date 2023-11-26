## Cloud-Native Web Voting Application with Kubernetes
### This cloud-native web application is built using a mix of technologies. It's designed to be accessible to users via the internet, allowing them to vote for their preferred programming language out of six choices: C#, Python, JavaScript, Go, Java, and NodeJS.

### Technical Stack
 <b>Frontend: </b> The frontend of this application is built using React and JavaScript. It provides a responsive and user-friendly interface for casting votes.

<b> Backend and API: </b> The backend of this application is powered by Go (Golang). It serves as the API handling user voting requests. MongoDB is used as the database backend, configured with a replica set for data redundancy and high availability.

<b>To deploy and manage this application effectively, we leverage Kubernetes and a variety of its resources: </b>

<b> Namespace:</b> Kubernetes namespaces are utilized to create isolated environments for different components of the application, ensuring separation and organization.

<b> Secret:</b> Kubernetes secrets store sensitive information, such as API keys or credentials, required by the application securely.

<b> Deployment:</b> Kubernetes deployments define how many instances of the application should run and provide instructions for updates and scaling.

<b> Service: </b> Kubernetes services ensure that users can access the application by directing incoming traffic to the appropriate instances.

<b> StatefulSet: </b>For components requiring statefulness, such as the MongoDB replica set, Kubernetes StatefulSets are employed to maintain order and unique identities.

<b> PersistentVolume and PersistentVolumeClaim: </b> These Kubernetes resources manage the storage required for the application, ensuring data persistence and scalability.

### Screenshots of Project
![cloudnative](https://github.com/Mahadevan777/mn-eks-rgm/assets/72142581/7d11604d-e005-4644-b3ad-3282046753cc)

![Screenshot (161)](https://github.com/Mahadevan777/mn-eks-rgm/assets/72142581/e63354c7-2d8c-46cb-bd0d-78eac0ab3f52)

![Screenshot (175)](https://github.com/Mahadevan777/mn-eks-rgm/assets/72142581/8bd4c861-fcc3-451b-b2f4-25566f086a70)

![Screenshot (176)](https://github.com/Mahadevan777/mn-eks-rgm/assets/72142581/f5642898-5d92-44de-bf3e-4daeee632bb7)

![Screenshot (174)](https://github.com/Mahadevan777/mn-eks-rgm/assets/72142581/e7ef12af-da71-4ccf-b4c4-6319d333c870)

![Screenshot (170)](https://github.com/Mahadevan777/mn-eks-rgm/assets/72142581/3d12a90d-e992-46dd-8bac-9143747ad018)

![Screenshot (166)](https://github.com/Mahadevan777/mn-eks-rgm/assets/72142581/bddf192e-79f7-4e54-8a1c-24fe235281e0)

![Screenshot (163)](https://github.com/Mahadevan777/mn-eks-rgm/assets/72142581/687769cb-0b7c-4bd4-a24d-e1d0811ce4f0)

![Screenshot (164)](https://github.com/Mahadevan777/mn-eks-rgm/assets/72142581/ed64256e-de24-4431-b0b5-4381804d90b0)

![Screenshot (178)](https://github.com/Mahadevan777/mn-eks-rgm/assets/72142581/39c5b5b9-705c-4289-ba69-2605e49313a4)

