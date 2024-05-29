# Learning Resources for Platform Engineers

At [Devops Days Philly 2024](https://devopsdays.org/events/2024-philadelphia/welcome/), we had a open spaces session to crowdsource learning resources for building Platform Engineer skills. This is the output of that session.

Resources are broken up by subject area, and there are a lot of subject areas. A lot of resources are free, but some are paid. 
|||
|---|----|
|📺|Video|
|🎓|Certification|
|🎟|Conference|
|🧑‍💻|Online Training|
|📄|Online Reading|
|📕|Book|
|🔨|Tool|
|💡|Concept|
|✅|Recommendation / advice|


### Security
* 📺 [Security from Scratch | LeadDev NYC 2023 talk](https://leaddev.com/new-york/leaddev/video/2023/security-scratch)
* 🎓 [CYSA Certification](https://www.comptia.org/certifications/cybersecurity-analyst)
* 🎟 [Bsides Conference](https://infosec-conferences.com/event-series/bsides/)
* 🎓 [CISSP certification](https://www.isc2.org/certifications/cissp)
* 📄 [WAF Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html)
* 🎓 [AWS Security Certification](https://aws.amazon.com/certification/certified-security-specialty/)
* 📄 [OWASP Top Ten](https://owasp.org/www-project-top-ten/)
* 🧑‍💻 [Bandit Wargame](https://overthewire.org/wargames/bandit/)
* 🔨 Security LLMs
   * [IntelGPT](https://github.com/phishing-hunter/intelgpt)
   * [Hacker GPT](https://github.com/Hacker-GPT/HackerGPT-2.0)

### Source Control / GitOps
* LeetCode for Git
* ✅ Do small project and host on Github
* 📄 [Open Gitops Group](https://opengitops.dev/get-involved) (discussion / volunteer)
* 📄 [Git Repository Best Practices](https://docs.github.com/en/repositories/creating-and-managing-repositories/best-practices-for-repositories)
* 📄 [PR Best Practices](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/best-practices-for-pull-requests)
* 📕 [Oh Shit, Git](https://wizardzines.com/zines/oh-shit-git/) by Julia Evans
* 📄 [/r/git subreddit](https://www.reddit.com/r/git/)

### Kubernetes / Container Orchestration
* 🎓 [CKAD cert](https://training.linuxfoundation.org/certification/certified-kubernetes-application-developer-ckad/)
* 🧑‍💻 [Kubernetes the hard way](https://github.com/kelseyhightower/kubernetes-the-hard-way)
* 📕 [Kubernetes Up and Running](https://www.oreilly.com/library/view/kubernetes-up-and/9781491935668/)
* 📕 [Kubernetes Resume Challenge](https://cloudresumechallenge.dev/docs/extensions/kubernetes-challenge/)
* 🧑‍💻 [killer.sh](https://killer.sh)
* 📄 [EKS User Guide](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html)

### Continuous Integration / Delivery / Deployment (CI/CD)
* ✅ Dummy app / ref architecture pipeline
* 📄 [Thoughtworks Radar](https://www.thoughtworks.com/radar)
* 📕 [Phoenix Project](https://itrevolution.com/product/the-phoenix-project/)
* 📕 [Devops Handbook](https://itrevolution.com/product/the-devops-handbook-second-edition/)
* 📕 [Accelerate](https://itrevolution.com/product/accelerate/)
* 📕 [Continuous Delivery Book](https://www.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912)

### Programming Languages
* 📕 [Learn _X_ the Hard Way](https://learncodethehardway.org/)
    * Python and Golang are probably the two most used languages in platform engineering, but you also will be very well served by understanding the language the product engineers at your company are writing this applictions in.
* ✅ Skip certs -- programming is an important skil in platform engineering, but the level language certifications require is most likely far too deep for what you'll need.
* [Learning Go](https://www.oreilly.com/library/view/learning-go/9781492077206/)
* 📕 [Rust Programming Langauge (book)](https://nostarch.com/rust-programming-language-2nd-edition) but also [available for free online](https://doc.rust-lang.org/book/ch00-00-introduction.html)
* 🧑‍💻 [Python For Pentesters](https://www.pentesteracademy.com/course?id=1)
* 🧑‍💻 [programmingexpert.io](https://www.programmingexpert.io/product)
* 🧑‍💻 [Screeps](https://screeps.com/)

### Cloud
* 🧑‍💻 [AWS Skill Builder](https://skillbuilder.aws/)
* 🎓 [AWS Certifications](https://aws.amazon.com/certification/)
* 🧑‍💻 [Cloud Resume Challenge](https://cloudresumechallenge.dev/)
* ✅ Do a project using the Azure Free Tier (.net inspire)
* 📄 Reading FAQs
* 🧑‍💻 [A Cloud Guru](https://www.pluralsight.com/cloud-guru)
* 🧑‍💻 [Tutorial Dojo](https://tutorialsdojo.com/)
* 📄 [AWS Well Architected Framework](https://aws.amazon.com/architecture/well-architected/)
* 📄 [Azure Well Architected Framework](https://learn.microsoft.com/en-us/azure/well-architected/)

### System Administration
* 🧑‍💻 [Sad Servers](https://sadservers.com/)
* 🧑‍💻 [OpenVIM Interactive Tutorial](https://www.openvim.com/)
* 🧑‍💻 [Kubernetes the hard way](https://github.com/kelseyhightower/kubernetes-the-hard-way)
* 🔨 [Shellcheck](https://github.com/koalaman/shellcheck) - Bash Linter
* 🧑‍💻 [Regex Golf](https://alf.nu/RegexGolf?world=regex&level=r00)
* 📕 [Wizard Zines Bite Size Pack](https://wizardzines.com/zines/bite-size-pack/)

### Infrastructure as Code (IAC)
* 📕 [The Terraform Book by James Turnbull](https://terraformbook.com/)
* Do docs / tutorials on TF
* 🧑‍💻 Plural Sight / A Cloud Guru
* 📺 [Pulumi Youtube Channel](https://www.youtube.com/channel/UC2Dhyn4Ev52YSbcpfnfP0Mw)
* Deploy your containers to cloud using IAC
* 💡 Idempotency - writing your IAC in a way that it can be applied and the same result will occur, regardless of the initial state.
* 💡 Immutable Infrastructure - writing your IAC that you only ever create and delete infrastructure, never update it.

### Observability (o11y) / SLA / SLO
* 📺 [Charity Majors SRE Con Keynote](https://www.usenix.org/conference/srecon24americas/presentation/majors-plenary)
* 📕 [Google SRE Handbook](https://sre.google/sre-book/table-of-contents/)
* 📕 [Google SRE Workbook](https://sre.google/workbook/table-of-contents/)
* 📕 [Cloud Native Observability book](https://www.oreilly.com/library/view/cloud-native-observability-with/9781801077705/) 
* 📄 [Open Telemetry Documentation](https://opentelemetry.io/docs/)
* 📕 [Observability Engineering book](https://www.oreilly.com/library/view/observability-engineering/9781492076438/)
* 📄 [DORA Metrics](https://cloud.google.com/blog/products/devops-sre/using-the-four-keys-to-measure-your-devops-performance)
* 📕 [Learning Observability by Austin Parker](https://www.oreilly.com/library/view/learning-opentelemetry/9781098147174/)
* 🧑‍💻 [Honeycomb Online Demo](https://www.honeycomb.io/sandbox)
* ✅ Follow [Charity Majors](https://twitter.com/mipsytipsy/) on Twitter

### Microservices
* 📄 [12 Factor App](https://12factor.net/)
* 📕 [Monolith to Microservices by Sam Newman](https://samnewman.io/books/monolith-to-microservices/)
* 📕 [Building Microservices by Sam Newman](https://samnewman.io/books/building_microservices_2nd_edition/)
* 📕 [Building Evolutionary Architectures by Neil Ford](https://www.oreilly.com/library/view/building-evolutionary-architectures/9781491986356/)
* 🧑‍💻 [Docker Tutorial](https://www.docker.com/101-tutorial/)
* 📕 [Bootstrappning Microservices by Ashley Davis](https://www.manning.com/books/bootstrapping-microservices-second-edition)
* 📄 [Fallacies of Distributed Computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)
* 🧑‍💻 Run container scanning tools on public images
* 📕 [Domain-Driven Design by Eric Evans](https://www.oreilly.com/library/view/domain-driven-design-tackling/0321125215/)
* 📄 [CNCF Working groups](https://contribute.cncf.io/about/working-groups/) (volunteer / discussion)
* 📕 [Linux Admin Handbook](https://www.oreilly.com/library/view/unix-and-linux/9780134278308/) (specifically the section on containers)
* 🧑‍💻 [Rancher Academy](https://www.rancher.academy/)
* 📺 [Malicious Compliance: Reflections on Trusting Container Scanners](https://kccnceu2023.sched.com/event/1Hybu/malicious-compliance-reflections-on-trusting-container-scanners-ian-coldwater-independent-duffie-cooley-isovalent-brad-geesaman-ghost-security-rory-mccune-datadog)

### PM / Product Planning
* 📕 [Wardley Maps](https://learnwardleymapping.com/book/)


----

The following sections were discussed during the session, but we didn't have time to come up with resources for them. Feel free to submit any suggestions you might have!!

### Marketing / Developer Relations (DevRel)

### Networking

### Internal Development Platforms (IDPs)

### Capacity Engineering

### Resilience Engineering

### Financial Operations (FinOps)

### Policy As Code (PAC)
