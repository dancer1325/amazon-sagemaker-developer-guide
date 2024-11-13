# What Is Amazon SageMaker?<a name="whatis"></a>

* Amazon SageMaker
  * == fully managed machine learning service
    * allows
      * build & train machine learning models
      * deploy them | production-ready hosted environment
        * -- via -- few clicks | 
          * SageMaker Studio or
          * SageMaker console
      * integrate machine learning-based models | your applications
    * provides
      * integrated Jupyter authoring notebook instance
        * -> NOT have to manage servers
      * common machine learning algorithms / are optimized
        * ALSO, you can bring-your-own-
          * algorithms
          * frameworks
      * flexible distributed training options
  * see ALSO [Amazon SageMaker developer resources](http://aws.amazon.com/sagemaker/developer-resources/)

**Topics**
+ [Amazon SageMaker Features](whatis-features-alpha.md)
+ [Amazon SageMaker Pricing](#whatis-pricing)
+ [Are You a First\-time User of Amazon SageMaker?](#first-time-user)

## Amazon SageMaker Pricing<a name="whatis-pricing"></a>

* Training and hosting are billed / minutes of usage
  * NO minimum fees
  * see [SageMaker Pricing](http://aws.amazon.com/sagemaker/pricing/)

## Are You a First\-time User of Amazon SageMaker?<a name="first-time-user"></a>

1. **Read [How Amazon SageMaker Works](#how-amazon-sagemaker-worksa-namehow-it-worksa)**
2. **[Set Up Amazon SageMaker Prerequisites](gs-set-up.md)**
3. Amazon SageMaker Autopilot
   1. TODO: simplifies the machine learning experience by automating machine learning tasks\. If you are new to SageMaker, it provides the easiest learning path\. It also serves as an excellent ML learning tool that provides visibility into the code with notebooks generated for each of the automated ML tasks\. For an introduction to its capabilities, see [Automate model development with Amazon SageMaker Autopilot](autopilot-automate-model-development.md)\. To get started building, training, and deploying machine learning models, Autopilot provides:
      + [Samples: Explore modeling with Amazon SageMaker Autopilot](autopilot-samples.md)
      + [Videos: Use Autopilot to automate and explore the machine learning process](autopilot-videos.md)
      + [Tutorials: Get started with Amazon SageMaker Autopilot](autopilot-tutorials.md)

1. **[Get Started with Amazon SageMaker](gs.md)** – This section walks you through training your first model using SageMaker Studio, or the SageMaker console and the SageMaker API\. You use training algorithms provided by SageMaker\.

1. **Explore other topics** – Depending on your needs, do the following:
   + **Submit Python code to train with deep learning frameworks** – In SageMaker, you can use your own training scripts to train models\. For information, see [Use Machine Learning Frameworks, Python, and R with Amazon SageMaker](frameworks.md)\.
   + **Use SageMaker directly from Apache Spark** – For information, see [Use Apache Spark with Amazon SageMaker](apache-spark.md)\.
   + **Use SageMaker to train and deploy your own custom algorithms** – Package your custom algorithms with Docker so you can train and/or deploy them in SageMaker\. To learn how SageMaker interacts with Docker containers, and for the SageMaker requirements for Docker images, see [Using Docker containers with SageMaker](docker-containers.md)\. 

1. **View the [API Reference](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Reference.html)** – This section describes the SageMaker API operations\.

### How Amazon SageMaker Works<a name="how-it-works"></a>

* goal
  * overview of SageMaker,
  * key concepts,
  * core components

1. [Machine Learning with Amazon SageMaker](how-it-works-mlconcepts.md)
2. [Explore, Analyze, and Process Data](how-it-works-notebooks-instances.md)
3. [Train a Model with Amazon SageMaker](how-it-works-training.md)
4. [Deploy a Model in Amazon SageMaker](how-it-works-deployment.md)
5. [Use Machine Learning Frameworks, Python, and R with Amazon SageMaker](frameworks.md)
6. [Get Started with Amazon SageMaker](gs.md)