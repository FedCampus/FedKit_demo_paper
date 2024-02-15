# Addressing Reviewers' Comments

## Reviews

### **Demo Submission Reviews 1**
>
> - The authors compare their contributions with other works in Table I.
>     When comparing with reference \[5\], it appears that FEDKIT merely
>     adds features for training acceleration and MLOps. If so, why not
>     integrate these features into reference \[5\] instead of developing
>     a new system? These two features do not seem overly complex, raising
>     questions about the necessity for a new system.

We forgot to cite \[4\] when mentioning the Flower FL Framework. Adding.

> - In Section II, Part A, Subsection 2, the authors describe their
>     method for setting parameters on CoreML but do not compare it with
>     methods from other works. Is this solution unique to this paper? If
>     it is, how does it compare in effectiveness and efficiency with
>     others?

We removed the mentioning that it is undocumented. Adding that back.

### **Demo Submission Reviews 2**

> The paper does not discuss how platform differences might affect model
> performance,

Because we did not explore that.

> and the YouTube demo provided is inaccessible.

Fixed by using `hyperref`.

### **Demo Submission Reviews 3**

> It is unclear how the version of the OS in cross-platform affects the
> training, or can the model trained on one platform affect the
> aggregation with other models?

### **Demo Submission Reviews 4**

> Not enough benchmarks are compared with. The live demonstration only
> demonstrate the reduction of training loss but it is not enough to
> showcase the performance of the system.
>
> The only concerning the reviewer has is that there is not
> enough assessment for their proposed FedKit system except the train time
> is in a few seconds (for two local epochs). Still, it seems slow and we
> do not know how it scales, like how many parameters are used in the
> model, the size of dataset, etc. and some details of the training model
> are missing. Some discussion on that is expected.

### **Demo Submission Reviews 5**

> - The authors only provided results on an Android device and an iOS
>     device while results on more devices particularly Android devices
>     from different manufacturers are expected.

This demo is not (yet) a benchmark.

> - It is better that Fig. 3 is to show training progress rather than a
>     photo illustrating the setup.

Unclear how we can show the training progress in a photo…
We only have these photos.
