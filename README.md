![Stay home, learn Beam](https://github.com/aijamalnk/beam-learning-month/raw/master/images/banner.png)

Welcome to Beam Learning Month's repository! Here, you will find links to the recordings and source files that were used during the presentations. 

If you have feedback on on how to improve Apache Beam and these webinars, please fill out [this form](https://docs.google.com/forms/d/1uw3gvhp7gHmrFiPixYoQcpBqnUbjJhABf0KCGsFekn4/edit). We will use your feedback to prepare future webinar content and prioritize feature requests in Apache Beam. 

If you have an interesting use case with Apache Beam and would like to speak at future webinars, please submit your talk to the [Beam Summit 2020](http://beamsummit.org/) or reach out to Apache Beam mailing list at <dev@beam.apache.org> with your talk details. 

We also created a [#beamlearningmonth-05-2020 Slack channel](https://bit.ly/2RO9TmO) if you want to connect to other attendees of the Beam Learning Month and have further discussions on Beam.

## Webinar 1: An interactive introduction to Apache Beam

In this presentation, Sam Rohde and Ning Kang introduced Apache Beam using Jupyter Notebooks by live coding a batch 
pipeline using publicly available COVID-19 data.

They also had prepared a streaming pipeline, but due to time constraints, they couldn't present it. Nonetheless, they made the code available.

### Materials

- [Recorded session on Youtube](https://www.youtube.com/watch?v=w0L1rjU_Ib4)
- [Presentation slides](https://docs.google.com/presentation/d/1TSuhvNLlvQxLJAwthtyktzvIgzBLn59DiOXVViPJBbM/edit?usp=sharing)
- [A colab that you can use to run the examples](https://colab.sandbox.google.com/drive/13gMtIoGCrU66ZY8-VkoQosal6yEtHQPF?usp=sharing)
- [README on Interactive Beam](https://github.com/apache/beam/blob/master/sdks/python/apache_beam/runners/interactive/README.md) and [examples](https://github.com/apache/beam/blob/master/sdks/python/apache_beam/runners/interactive/examples).

## Webinar 2: Best practices for a Production-ready Beam Pipeline

In this presentation, Pablo Estrada introduces some Apache Beam utilities and practices to develop and test the 
correctness of your pipelines. Interactively developing a pipeline that performs some simple analytics on our data.

### Materials

- [Recorded session on Youtube](https://www.youtube.com/watch?v=Cf3-Z_HQRdE)
- [Presentation slides](https://docs.google.com/presentation/d/1x0nEZDVYwzWYifKG6hdxxhPiUfHJGL-VRj4mAm5pcps/edit#slide=id.p)
- [Github Repository with the code to walk along](https://github.com/pabloem/beam-covid-example)

## Webinar 3: Apache Beam Everywhere. An Introduction to the Spark Runner

In this presentation, Ismaël Mejía introduces the Beam Spark Runner and motivates its use by explaining its history, how it works and the advantages of using Spark as an execution system.

### Materials

- [Recorded session on YouTube](https://www.youtube.com/watch?v=XI9Y85qks1w)
- [Presentation slides](https://docs.google.com/presentation/d/1OAeji_E3QbRRvBVW_Wgt4e06Y5upYkR3c9NcB3IY75M/edit?usp=sharing)


## Webinar 4: The Best of Both Worlds: Unlocking the Power of Apache Beam with Apache Flink

Presenter: Maximilian Michels 

Apache Beam is a framework for writing stream and batch processing
pipelines using multiple languages such as Java, Python, SQL, or Go.
Apache Beam does not come with an execution engine of its own. Instead,
it defers the execution to its Runners which translate Beam pipelines
for any supported execution engine. Thus, users have complete control
over the language and the execution engine they use, without having to
rewrite their code.

In this talk, we will look at running Apache Beam pipelines with Apache
Flink. We will explain the concepts behind Apache Beam's portability
framework for multi-language support, and then show how to get started
running Java, Python, and SQL pipelines.

### Materials

- [Recorded session on YouTube](https://www.youtube.com/watch?v=ZCV9aRDd30U)
- [Presentation slides](Unlocking%20the%20Power%20of%20Apache%20Beam%20with%20Apache%20Flink.pdf)

## Webinar 5: Feature Powered by Apache Beam

In this talk, Kobe Feng introduces how eBay marketing builds feature pipelines with Apache Beam. To unify feature extraction and selection in online and offline, to speedup E2E iteration for model training, evaluation and serving, to support different types (streaming, runtime, batch) of features, etc. eBay leverages Apache Beam for their streaming feature SDK as a foundation to integrate with Kafka, Hadoop, Flink, Airflow and others in eBay.

### Materials

- [Recorded session on Youtube](https://www.youtube.com/watch?v=Ncg3Re6OZ00)
- [Presentation slides](https://docs.google.com/presentation/d/1zqexjraqzjln-XITt3zLwsZrx-BqLjO9q0LcRtGjTk0/edit?usp=sharing)

## Webinar 6: Distributed Processing for Machine Learning Production Pipelines

In this talk, Developer Advocates from Google - Reza Rokni and Robert Crwoe discuss production ML applications and review TensorFlow Extended (TFX), Apache Beam, and Google experience with ML in production.

Production ML workloads often require very large compute and system resources, which leads to the application of distributed processing on clusters. On premises or cloud-based infrastructure cost requires maximum efficient use of resources. This makes distributed processing pipeline frameworks such as Apache Beam ideal for ML workloads. In addition, production ML must address issues of modern software methodology, as well as issues unique to ML. Different types of ML have different requirements, often driven by the different data lifecycles and sources of ground truth. Implementations often suffer from limitations in modularity, scalability, and extensibility.

### Materials

- [Recoded session on Youtube](https://www.youtube.com/watch?v=wVXds1gVtn8&t=15s)
- [Slides from their presentation](https://drive.google.com/file/d/1lNb8ROlhxvBTCJNnIkPM_JuCeR_IA2ak/view?usp=sharing)
- [Developing interactively with Apache Beam notebooks](https://cloud.google.com/dataflow/docs/guides/interactive-pipeline-development)

---
## Information for Speakers

### Resource checklist:
- Link to the presentation (make sure to give “view” access to the world)
- Source files that were used during the presentation/demo 
- Links to additional colabs, related talks or README files

Add your webinar to this file like this:

```
## Webinar (N): (TITLE)
In this section, write a brief description of your talk, and provide speaker information.

### Materials

- [Recoded session on Youtube](LINK)
- [Slides from their presentation](LINK)
- [Code](LINK)
```
### Instructions for the speakers:
- You are already registered as a speaker, you should receive the join link from zoom.us.
- On the day of the event, we will start the meeting 10 mins before the meeting time to test your audio/video. If you don't have Zoom, you can download a Zoom client (no need to create a Zoom account) or join from the browser  (after you click the link in your email, it opens up the web browser and then you can click "Join from browser").
- Find a quiet and comfortable place to deliver the talk.
- Test and make sure the laptop microphone works.
- Keep track of time. It is a good practice to spend 30-40mins on presentation, and another 10-15 mins on Q&A. 

### Extra tips to run successful virtual presentation:

- Speak slower than you normally do at in-person conversation. It will be easier for the attendees to understand you, and it will help if there are network delays.
- If possible, turn on the video so the audience can see you. In general the audience will be more engaged if they can see the speakers :-).
- Use a large font for slides and coding demos.
- Avoid animations on slides. 
- Avoid quick switching of the slides or bullet points, as it is harder for the attendees to follow with the smaller screen and network delays.
- When you are done with the presentation and it is a Q&A section, show your Q&A/Thank you slide, or turn on the camera so that the recording is not blank. 

## Help us promote your session
Share your upcoming session on LinkedIn or Twitter and tag @ApacheBeam twitter handle or use #ApacheBeam hashtags.
