# Houser  API
This is a unique API,In of it self,it acts like a [Kubernetes(K8Ss)](https://kubernetes.io) cluster.You can setup new  endpoints,Add to existing endpoints and add entire new stuff or use the existing components in your project.See the list of components and their definitions:

---

1. Redirect component
The Redirect component redirects one or more devices to the specified location.The locations can be:
- Files
- URLS
- Apps

2.Service Component
The service component is like a redirect component, but very different. It serves as a connector  different components. For example, if you want some devices that when are on [YouTube](https://youtube.com), they redirect to [YouTube Kids](https://youtubekids.com) only on you're children's devices you can use a service so that change is for all devices in your Wi-Fi

3. Pod Control Component
The pod control components uses notifications when you want to track  your child's screen time over the week and more statistics like what they have been wtach the Video URLS.

4. Master Control Component
The Mater Control Compoenent is a center where you can manage all of these components

5. The Config Component
The config component is a  place for  storing key-value pairs