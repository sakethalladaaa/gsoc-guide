# GSoC 2027 Guide 

A practical organization shortlist and contribution roadmap for preparing early for **Google Summer of Code 2027**.

> **Status:** The official GSoC 2027 mentoring organizations have not been announced yet. This guide uses recent GSoC participation, current 2026 organization data, technology fit, project depth, and community contribution paths to identify strong organizations to watch.

## Goal

The goal is **not** to collect random easy pull requests.

The goal is to become a credible contributor in one open-source community before the GSoC 2027 application period and be ready for a **Large project (~350 hours)** if the selected organization offers one.

Google currently describes project sizes as roughly:

| Project size | Approximate effort |
| --- | ---: |
| Small | ~90 hours |
| Medium | ~175 hours |
| Large | ~350 hours |

Official GSoC information: https://developers.google.com/open-source/gsoc

Official 2026 organization list: https://summerofcode.withgoogle.com/programs/2026/organizations

---

# Recommended Organizations to Watch for GSoC 2027

These are **targets to monitor**, not guarantees for GSoC 2027 participation.

## 1. Kubeflow

**Best for:** Go, Python, Kubernetes, AI/ML, MLOps, distributed training, cloud-native infrastructure

**Difficulty:** High

**Why it is strong:**

- Strong overlap between Kubernetes and machine learning infrastructure.
- Useful for contributors interested in controllers, APIs, training runtimes, distributed workloads, scheduling, observability and platform engineering.
- Excellent choice for someone who wants to become an AI infrastructure engineer rather than only build application-layer AI projects.

**Potential contribution areas:**

- Kubeflow Trainer
- Pipelines
- Katib
- KServe-related integrations
- Kubernetes controllers and APIs
- Testing and observability
- Distributed training infrastructure

**Suggested path:** start with one active Kubeflow repository and build depth there instead of jumping between all Kubeflow projects.

Official site: https://www.kubeflow.org/

GitHub: https://github.com/kubeflow

---

## 2. OpenVINO Toolkit

**Best for:** C++, Python, AI/ML, computer vision, inference, model optimization

**Difficulty:** High

**Why it is strong:**

- Strong real-world AI inference ecosystem.
- Good option for contributors who want a mixture of systems programming and machine learning.
- Previous GSoC workflows have included prerequisite contribution expectations, so early contribution matters.

**Potential contribution areas:**

- Inference runtime
- Generative AI tooling
- Model optimization
- GPU/CPU performance
- AI agents
- Computer vision
- Deployment tooling

GitHub: https://github.com/openvinotoolkit/openvino

GSoC information: https://github.com/openvinotoolkit/openvino/wiki/Google-Summer-Of-Code

---

## 3. NumFOCUS

**Best for:** Python, C++, R, Julia, data science, AI, numerical/scientific computing

**Difficulty:** Medium to High

**Important:** NumFOCUS is an umbrella organization. You normally contribute to a **specific participating project**, not to NumFOCUS generically.

Examples of the type of ecosystems associated with NumFOCUS include scientific Python, numerical computing, visualization, statistics and research software.

**Why it is strong:**

- Broad technology choices.
- Excellent for Python/data-science contributors.
- Lets you choose a subproject that matches your actual skills.

Official 2026 page: https://summerofcode.withgoogle.com/programs/2026/organizations/numfocus

Contributor guidance: https://github.com/numfocus/gsoc

---

## 4. Apache Software Foundation

**Best for:** Java, Go, Python, C/C++, backend systems, databases, distributed systems, cloud infrastructure

**Difficulty:** High

**Why it is strong:**

- Huge umbrella ecosystem with many mature projects.
- Excellent for backend and distributed-systems contributors.
- Strong engineering practices and review culture.

**Possible directions:**

- Data platforms
- Distributed systems
- Databases
- Streaming
- Cloud infrastructure
- Developer tooling

Official site: https://www.apache.org/

GitHub: https://github.com/apache

---

## 5. Jenkins

**Best for:** Java, Go, JavaScript, Docker, Kubernetes, CI/CD, DevOps

**Difficulty:** Medium to High

**Why it is strong:**

- Mature contributor onboarding.
- Strong DevOps and plugin ecosystem.
- Public GSoC project ideas and contributor guidance.
- Jenkins had five selected GSoC projects in 2026 and also participated in previous recent years.

**Potential contribution areas:**

- Jenkins core
- Plugins
- Developer tooling
- CI/CD integrations
- AI-assisted developer workflows
- Website/tooling improvements

GSoC page: https://www.jenkins.io/projects/gsoc/

2026 project ideas: https://www.jenkins.io/projects/gsoc/2026/project-ideas/

---

## 6. OpenCV

**Best for:** C++, Python, computer vision, robotics, deep learning

**Difficulty:** High

**Why it is strong:**

- One of the best targets for serious C++ + computer-vision contributors.
- Work can involve algorithms, performance, image processing, camera geometry and AI integrations.

GitHub: https://github.com/opencv/opencv

---

## 7. Open Robotics / ROS ecosystem

**Best for:** C++, Python, ROS 2, robotics, simulation

**Difficulty:** Medium to High

**Why it is strong:**

- Excellent for robotics-focused contributors.
- Real-world systems work involving middleware, planning, simulation, drivers and tooling.

Useful ecosystems include ROS 2, Gazebo, ros-controls and Open-RMF.

ROS: https://www.ros.org/

GitHub: https://github.com/ros2

---

## 8. CERN-HSF

**Best for:** Python, C/C++, data analysis, AI, performance engineering, scientific software

**Difficulty:** High

**Why it is strong:**

- Large software engineering and scientific-computing problems.
- Many projects do **not** require physics knowledge.
- Current areas include machine learning, big data, performance optimization and container orchestration.
- Some recent project ideas are explicitly large (~350-hour) projects.

Official 2026 organization page: https://summerofcode.withgoogle.com/programs/2026/organizations/cern-hsf

Contributor information: https://hepsoftwarefoundation.org/activities/gsoc.html

---

## 9. Linux Foundation ecosystem

**Best for:** C, C++, Rust, Go, Linux, embedded systems, cloud-native infrastructure

**Difficulty:** High

**Why it is strong:**

Great option for contributors interested in systems engineering, kernels, embedded development, networking, security or cloud-native infrastructure.

Official site: https://www.linuxfoundation.org/

---

# Choose Based on Skill Stack

## Python + AI/ML

Recommended order:

1. Kubeflow
2. NumFOCUS subproject
3. OpenVINO
4. CERN-HSF

## C / C++

Recommended order:

1. OpenVINO
2. OpenCV
3. CERN-HSF
4. Linux Foundation ecosystem

## Go + Kubernetes / Cloud

Recommended order:

1. Kubeflow
2. Apache project with Go/cloud-native work
3. Jenkins / CI infrastructure
4. Linux Foundation ecosystem

## Java + Backend

Recommended order:

1. Apache Software Foundation
2. Jenkins
3. Suitable database/distributed-system project

## Robotics

Recommended order:

1. Open Robotics / ROS ecosystem
2. OpenCV
3. Linux Foundation projects related to robotics/embedded systems

## Data Science / Scientific Computing

Recommended order:

1. NumFOCUS subproject
2. CERN-HSF
3. OpenVINO if AI inference interests you

---

# Generic Top 5 if the Tech Stack Is Not Yet Fixed

If Praneeth has not yet decided on a specialization:

1. **NumFOCUS** — broadest scientific/data ecosystem
2. **Apache Software Foundation** — huge choice of serious backend projects
3. **Jenkins** — strong onboarding and DevOps ecosystem
4. **Kubeflow** — excellent AI + Kubernetes target
5. **OpenVINO** — excellent AI + C++/Python target

Do **not** choose purely based on this ranking. A smaller project matching your strongest skills is often a better GSoC target than a famous organization whose codebase you cannot contribute to effectively.

---

# GSoC 2027 Contribution Strategy

## Phase 1 — Explore

Pick:

- **1 primary organization**
- **1 backup organization**

Do not actively contribute to five unrelated organizations at once.

For each candidate:

- Read `README.md`
- Read `CONTRIBUTING.md`
- Understand repository architecture
- Build the project locally
- Run existing tests
- Join the public community channel if available
- Read recent issues and pull requests

---

## Phase 2 — First Contribution

The first PR should be small enough to finish correctly but meaningful enough to teach the contribution workflow.

Good examples:

- Small bug fix
- Regression test
- Missing validation
- Test infrastructure improvement
- Small developer-tooling improvement

Avoid building a profile made entirely of typo/documentation PRs.

Workflow:

```text
Inspect
  ↓
Reproduce
  ↓
Understand root cause
  ↓
Discuss approach if needed
  ↓
Implement smallest correct fix
  ↓
Add/update tests
  ↓
Run formatter/linter/tests
  ↓
Self-review diff
  ↓
Open PR
  ↓
Respond to maintainer review
```

---

## Phase 3 — Build Depth

After the first PR, stay in the same project.

Target progression:

```text
PR 1 → Small bug/test fix
PR 2 → Meaningful code contribution
PR 3 → Medium-complexity issue
PR 4+ → Work repeatedly in one subsystem
```

The goal is for maintainers to begin recognizing your GitHub username and technical area.

---

## Phase 4 — Specialize

Choose one subsystem and learn it deeply.

Examples:

- Kubernetes controllers
- Distributed systems
- Compiler/runtime internals
- ML inference
- Computer vision algorithms
- CI/CD infrastructure
- Robotics middleware
- Numerical/scientific computing

Study:

- architecture/design documents
- core source code
- test architecture
- issue history
- recent merged PRs
- roadmap/project ideas

---

## Phase 5 — Prepare for GSoC Ideas

When GSoC 2027 organization and project-idea pages become available:

1. Confirm that your primary organization was accepted.
2. Find project ideas overlapping the subsystem you already know.
3. Prefer a project where your earlier contributions prove relevant experience.
4. Talk publicly with mentors early.
5. Understand the problem before drafting the proposal.
6. Build a prototype or proof of concept if useful.
7. Get proposal feedback early rather than submitting on the final day.

---

# Target Profile Before Applying

A strong applicant should ideally have:

- A working local development environment for the project
- Multiple meaningful contributions
- At least one non-trivial contribution
- Experience receiving and resolving code review
- Familiarity with one subsystem
- Public technical interaction with maintainers/mentors
- Understanding of the proposed project's architecture
- A realistic milestone plan
- Testing strategy
- Risks and fallback plan

There is **no official requirement for a specific PR count**. Quality, relevance, communication and trust matter more than chasing a number.

---

# Suggested Preparation Timeline

## October–November 2026

- Decide primary technical direction
- Select primary + backup organizations
- Set up local environment
- Understand contribution rules
- Submit first useful PR

## November–December 2026

- Complete 2–3 meaningful contribution cycles
- Learn maintainers' review expectations
- Start focusing on one subsystem

## December 2026–January 2027

- Attempt a medium-complexity issue
- Read architecture/design documents
- Participate in technical discussions
- Build deeper project knowledge

## GSoC 2027 Organization Announcement Period

- Confirm whether the primary organization was accepted
- If not, activate the prepared backup
- Review the new year's project ideas

## Before Contributor Applications

- Discuss project scope with mentors
- Research existing implementation
- Write technical design
- Define milestones
- Identify testing strategy
- Identify risks
- Get feedback on the proposal
- Submit before the deadline, not at the last minute

---

# What NOT to Do

Avoid:

- Opening many trivial PRs just to increase contribution count
- Asking maintainers to assign an issue before understanding it
- Commenting "please assign me" on many issues
- Blindly submitting AI-generated code
- Ignoring repository contribution rules
- Working on an issue already being solved by another contributor
- Large unrelated refactors in a first PR
- Starting proposal preparation only after applications open
- Private-spamming mentors instead of using the community's preferred public channels

---

# Recommended Decision Framework

Score each candidate organization from 1–5:

| Factor | Weight |
| --- | ---: |
| Skill match | 5 |
| Can build/test locally | 5 |
| Active maintainers | 5 |
| Beginner contribution path | 4 |
| Interesting long-term subsystem | 5 |
| Recent GSoC participation | 3 |
| Large-project potential | 4 |
| Quality of documentation | 3 |
| Community responsiveness | 4 |

Choose the organization with the strongest **overall fit**, not simply the biggest name.

---

# Current Recommendation

Until Praneeth's exact strongest languages and project interests are known, use this decision tree:

```text
AI + Kubernetes/Go       → Kubeflow
AI + C++/Python          → OpenVINO
Scientific Python/Data   → NumFOCUS subproject
Java/Distributed Systems → Apache
DevOps/Java              → Jenkins
Computer Vision          → OpenCV
Robotics                 → Open Robotics / ROS
Scientific C++/Python    → CERN-HSF
Systems/Embedded         → Linux Foundation ecosystem
```

Once the exact stack is known, reduce this list to **one primary organization and one backup**.

---

# Official Resources

- Google Summer of Code: https://summerofcode.withgoogle.com/
- Google GSoC documentation: https://developers.google.com/open-source/gsoc
- GSoC 2026 organizations: https://summerofcode.withgoogle.com/programs/2026/organizations
- Google Open Source Blog: https://opensource.googleblog.com/
- Kubeflow: https://www.kubeflow.org/
- OpenVINO: https://github.com/openvinotoolkit/openvino
- NumFOCUS GSoC: https://github.com/numfocus/gsoc
- Apache Software Foundation: https://www.apache.org/
- Jenkins GSoC: https://www.jenkins.io/projects/gsoc/
- CERN-HSF GSoC: https://hepsoftwarefoundation.org/activities/gsoc.html
- OpenCV: https://github.com/opencv/opencv
- ROS: https://www.ros.org/

---

## Disclaimer

GSoC organizations and project ideas can change every year. Participation in 2026 or earlier years does **not** guarantee acceptance as a mentoring organization in 2027. Always treat the official GSoC website and the selected organization's current contributor documentation as the source of truth.

---

**Prepared as an early-start roadmap for GSoC 2027.**
