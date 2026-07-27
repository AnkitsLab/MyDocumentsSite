# OpenShift Interview Preparation

## Core concepts
- What is OpenShift?
- Difference between Kubernetes and OpenShift
- Operators
- Routes
- SCC vs RBAC

## Sample commands

```bash
oc get nodes
oc get pods -A
oc describe clusterversion
```

## Questions I faced
1. Explain OpenShift upgrade strategy.
2. What happens when a node becomes NotReady?
3. How do you troubleshoot image pull issues?

!!! note "Exam tip"
    Learn the difference between `oc` and `kubectl`.

=== "OpenShift"
    ```bash
    oc get clusterversion
    ```

=== "Kubernetes"
    ```bash
    kubectl get nodes
    ```