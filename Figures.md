# Preferences for Kubernetes Tasks and Tools Survey

# The Research Gap
Developer surveys such as the CNCF show that there is an increased usage of Kubernetes in production. However, these developer surveys do not ask which Kubernetes tools are preferred in practice. Understanding the software tools that are preferred by developers and whether preference depends on the programming task at hand, is important for informing the future design and development of these tools. Therefore, we wrote a survey to help address this gap. 

We asked survey participants what their preference is among three tool modalities: Command Line Interface (CLI), Graphical Console, and IDE, and whether their tool preference varies across three programming task types: CRUD, debugging, and monitoring. From 44 respondents, we found that preference radically skews towards CLIs, except for monitoring tasks where a majority of respondents indicated that they prefer to use Graphical Consoles. 

# Kubernetes Survey Participants
We recruited survey participants within the IBM Hybrid Cloud Research group that have at least some Kubernetes experience. We reached out to others via open source Special Interest Group (SIG) meetings for CLIs and Usability to promote the survey and recruit more participants within the Kubernetes community. Google Forms was used to collect the survey data.

We asked participants what their level of experience with Kubernetes is, selecting from either Beginner, Intermediate, or Expert. We also asked participants to say how frequently they use Kubernetes, selecting from either Never, Monthly or even more rarely, Weekly, Once a day, or Many times each day. A majority of respondents said that they have an expert level of experience with Kubernetes and use Kubernetes many times each day, see Figures 1 and 2. None of the participants said they never use Kubernetes.  

We asked participants what their cloud providers are and allowed them to select all that were true from a set of popular providers (Azure, AWS, IBM, OpenShift) and select an “Other” option where they could write in an answer. A majority of respondents said that they use a single cloud provider, of which AWS is the most frequently mentioned cloud provider, as shown in Figures 3 and 4. In response to the question, one wrote, “I’m a consultant, so [it] varies!” One person gave us feedback on this survey question and said that OpenShift is a distribution and not a cloud provider. Perhaps not including OpenShift as an option would have encouraged more specific responses for other cloud providers not listed as popular options.

Figure 1: Among 44 survey respondents, 54.5% said they have an expert level of experience with Kubernetes, 34.1% said they have an intermediate level, and 11.4% said they have a beginner level.

Figure 2: Among 44 survey respondents, 75% said they use Kubernetes many times each day, 13.6% said weekly use, 6.8% said monthly or even more rarely use, and 4.5% said once daily use.

Figure 3: The most frequently named cloud provider for Kubernetes is AWS, with 20 responses. In other responses, people say they use Bare-Metal, with 1 specifying they use K3s, and On-Premise cloud providers, with 2 specifying they use vSphere.

# Most Frequent Kubernetes Programming Tasks
We asked participants how often they work on CRUD, debugging, and monitoring tasks when using Kubernetes. 20 respondents said they work on CRUD tasks many times each day, while 11 said they work on debugging tasks many times each day. 21 respondents said they work on debugging tasks weekly. 14 said they work on monitoring tasks weekly and 13 said they work on monitoring tasks monthly or even more rarely. One respondent said they never worked on any of these programming task types, so perhaps the task types could have been better explained or we could have included more task types. See Figures 6, 7, and 8 for more details.

Figure 4: A slight majority of respondents indicated that they use a single cloud provider.

# Tool Preferences for Kubernetes Developers
We asked participants what kind of tool they prefer to use when working on CRUD, debugging, and monitoring tasks. While a majority of participants said they prefer to use a CLI when working on CRUD and debugging tasks, a majority of participants said that they preferred to use a Graphical Console to work on monitoring tasks. The most preferred tool for Kubernetes beginners doing CRUD, debugging, and monitoring tasks is a CLI. Intermediate and expert Kubernetes developers prefer to use CLIs for CRUD and debugging tasks, and a graphical console for monitoring tasks. Two respondents said they preferred to use a combination of a CLI and Graphical Console for CRUD tasks, and one of the respondents said they preferred this combination for debugging tasks as well. Among the other tools mentioned in responses were: Kui and k9s (for CRUD, debugging, and monitoring), Helmfiles (for CRUD), and custom application monitoring (for monitoring). See Figure 9 and Figure 10 for more details.

Figure 6: Many respondents said they work on CRUD tasks many times a day.

Figure 7: Many respondents said they work on debugging tasks on a weekly basis. 

Figure 8: 14 respondents said they work on monitoring tasks on a weekly basis. 

Figure 9: The most preferred tool for Kubernetes CRUD and debugging tasks is a CLI. For Kubernetes monitoring tasks, a Graphical Console is preferred.

Figure 10: Intermediate and expert Kubernetes developers prefer to use a CLI for CRUD and debugging tasks, and a graphical console for monitoring tasks while beginners prefer to use CLIs for all task types. 

# Contribute to the Kubernetes Survey
This quick, 2-minute survey is still open to willing participants [here]()! Please reach out via email to ccoleman at ucsd.edu with any feedback or questions. We appreciate any feedback you may have on our survey.
