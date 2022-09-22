#Kubernetes Questions and Answers Part 1

- What are the components of the control plane and worker nodes ?
    1. [Kubernetes Components | Kubernetes](https://kubernetes.io/docs/concepts/overview/components/)
    2. [Kubernetes Architecture: 11 Core Components Explained](https://spot.io/resources/kubernetes-architecture-11-core-components-explained/)
    3. [A sysadmin's guide to basic Kubernetes components](https://www.redhat.com/sysadmin/kubernetes-components)
- How have you used admission controllers before in production?
    1. [ValidatingAdmissionWebhook that called registered webhook in parallel](https://kubernetes.io/docs/reference/access-authn-authz/admission-controllers/#validatingadmissionwebhook)
    2. [Enabled ResourceQuota to control developer resource usage per namespace](https://kubernetes.io/docs/concepts/policy/resource-quotas/)
    3. [I used PodSecurityPolicy which is replaced with PodSecurity standard for security enforcement within our cluster](https://kubernetes.io/docs/concepts/security/pod-security-standards/)
- How does CoreDNS work?
    1. https://blog.opstree.com/2020/06/16/a-closer-look-at-coredns/
    2. https://coredns.io/plugins/kubernetes/
    3. https://coredns.io/plugins/forward/
    4. 
- We notice that the pod IP is not being registered in CoreDNS, how do I fix that?
    - https://coredns.io/plugins/kubernetes/#syntax
- Once CoreDNS is installed in the cluster, how does it know what to write into Pod resolv.conf?
    1. https://github.com/tsacha/infra/blob/4e6cda90d38d6bbb16cc42111f37412e29e5a954/modules/k8s-hard/files/kubelet.yaml#L14

- How would you write an operator?

