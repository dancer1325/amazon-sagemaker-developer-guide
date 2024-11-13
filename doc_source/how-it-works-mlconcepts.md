# Machine Learning with Amazon SageMaker<a name="how-it-works-mlconcepts"></a>

* goal
  * typical machine learning workflow
  * machine learning workflow -- via -- Amazon SageMaker 

* machine learning
  * goal
    * "teach" a computer -- to make -- predictions, or inferences
  * continuous cycle of steps
    * **generate example data**
      * type of data -- depends on the -- business problem / you want to solve 
      * uses
        * train the model
      * steps
        1. Fetch the data
           1. coming from
              * in-house example data repositories,
              * publicly available datasets 
           2. recommendation
              * pull ALL datasets | 1! repository
        2. Clean the data
           * Reason: 🧠 improve model training 🧠
           * _Example:_ remove data inconsistency
             * if your data has a `country name` attribute / values `United States` and `US` -> edit to follow SAME convention
        3. Prepare or transform the data
           * == additional data transformations
             * _Example:_ combine attributes
           * see 
             * [Explore, Analyze, and Process Data](how-it-works-notebooks-instances.md)
             * [data preparation](https://aws.amazon.com/marketplace/search/results?searchTerms=data+preparation&spellCheck=false&page=1) 
      * done -- via the -- provided by SageMaker's instance's Jupyter notebook
    * **train a model**
      * steps
        * Training the model
          * requirements
            * algorithm or
              * -- depends on -- several factors 
            * pre-trained base model 
            * compute resources / 
              * types
                * 1!-purpose instance
                * distributed cluster of GPU instances
              * see [Train a Model with Amazon SageMaker](how-it-works-training.md)
          * see [built-in SageMaker Algorithms or Pre-trained Models](algos.md)
          * if you want UI-based training solution -> see [SageMaker JumpStart](studio-jumpstart.md)
        * Evaluating the model
          * == check if the accuracy of the inferences is acceptable
            * -- via --
              * AWS SDK for Python (Boto) or
              * high-level Python library / -- provided by -- SageMaker
    * **Deploy the model**
      * -- independently from your -- application code
        * see [Deploy Models for Inference](deploy-model.md)
      * monitor the inferences, collect "ground truth," and -> start again the cycle 
        * as more example data more accuracy

    ![wokflow -- for creating a -- machine learning model](http://docs.aws.amazon.com/sagemaker/latest/dg/images/ml-concepts-10.png)
