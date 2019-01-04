# Celebrity Recognition Compared to Face Search<a name="celebrity-recognition-vs-face-search"></a>

Amazon Rekognition offers both celebrity recognition and face recognition functionality\. These functionalities have some key differences in their use cases and best practices\. 

Celebrity recognition comes pre\-trained with the ability to recognize hundreds of thousands of popular people in fields such as sports, media, politics, and business\. It is designed to match celebrity faces and their various alter egos \(for example, Johnny Depp without makeup, Johnny Depp as “Edward Scissorhands,” and Johnny Depp as “Jack Sparrow”\)\. This functionality is designed to help you search large volumes of images or videos in order to identify a small set that is likely to contain a particular celebrity\. It is not intended to be used to match faces between different people that are not celebrities\. In situations where the accuracy of the celebrity match is important, we recommend also using human operators to look through this smaller amount of marked content to help ensure a high level of accuracy and the proper application of human judgment\. Celebrity recognition should not be used in a manner that could result in a negative impact on civil liberties\. 

On the other hand, face recognition is a more general functionality that allows you to create your own face collections with your own face vectors to verify identities or search for any person, not just celebrities\. Face recognition can be used for applications such as authenticating building access, public safety, and social media\. In all these cases, it’s recommended that you use best practices, appropriate confidence thresholds \(including 99% for public safety use cases\), and human review in situations where the accuracy of the match is important\.

For more information, see [Searching Faces in a Collection](collections.md)\.