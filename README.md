# spam-ham-classifier
This project is about classifying the spam-ham emails after doing work count vector transformation

steps followed to build a machine learning model are:
<ol>
  <li>download the datasets</li>
  <li>load all the emails</li>
  <li>get the count of email structure</li>
  <li>pre-process the data</li>
    <ul>
        <li>build the train test split</li>
        <li>convert from email to text</li>
        <li>build custom transformers to convert Emails to word counters(EmailToWordCounterTransformer,WordCounterToVectorTransformer)</li>
    </ul>
  <li>creating pipeline to fit the previously defined trasnfomers</li>
  <li>train the logistic regression model to a data</li>
  <Li>evaluate the model with precision score,accuracy score</Li>
</ol>
