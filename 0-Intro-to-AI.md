### How machine learning works
	Data scientists can use all of that data to train machine learning models that can make predictions and inferences based on the relationships they find in the data.

	For example, suppose an environmental conservation organization wants volunteers to identify and catalog different species of wildflower using a phone app. The following animation shows how machine learning can be used to enable this scenario.
		- A team of botanists and scientists collect data on wildflower samples.
		- The team labels the samples with the correct species.
		- The labeled data is processed using an algorithm that finds relationships between the features of the samples and the labeled species.
		- The results of the algorithm are encapsulated in a model.
		- When new samples are found by volunteers, the model can identify the correct species label.

### Understand anamoly detection
	Imagine you're creating a software system to monitor credit card transactions and detect unusual usage patterns that might indicate fraud. Or an application that tracks activity in an automated production line and identifies failures. Or a racing car telemetry system that uses sensors to proactively warn engineers about potential mechanical failures before they happen.

	These kinds of scenario can be addressed by using anomaly detection - a machine learning based technique that analyzes data over time and identifies unusual changes.

	Let's explore how anomaly detection might help in the racing car scenario.

		- Sensors in the car collect telemetry, such as engine revolutions, brake temperature, and so on.
		- An anomaly detection model is trained to understand expected fluctuations in the telemetry measurements over time.
		- If a measurement occurs outside of the normal expected range, the model reports an anomaly that can be used to alert the race engineer to call the driver in for a pit stop to fix the issue before it forces retirement from the race.

	*Anomaly detection in Microsoft Azure*
	In Microsoft Azure, the Anomaly Detector service provides an application programming interface (API) that developers can use to create anomaly detection solutions.

### Understand computer vision
	Computer Vision is an area of AI that deals with visual processing. Let's explore some of the possibilities that computer vision brings.

	The Seeing AI app is a great example of the power of computer vision. Designed for the blind and low vision community, the Seeing AI app harnesses the power of AI to open up the visual world and describe nearby people, text and objects.

	Computer Vision models and capabilities
	**Image classification**: Image classification involves training a machine learning model to classify images based on their contents. For example, in a traffic monitoring solution you might use an image classification model to classify images based on the type of vehicle they contain, such as taxis, buses, cyclists, and so on.
	**Object detection**: Object detection machine learning models are trained to classify individual objects within an image, and identify their location with a bounding box. For example, a traffic monitoring solution might use object detection to identify the location of different classes of vehicle.
	**Semantic segmentation**: Semantic segmentation is an advanced machine learning technique in which individual pixels in the image are classified according to the object to which they belong. For example, a traffic monitoring solution might overlay traffic images with "mask" layers to highlight different vehicles using specific colors.
	**Image analysis**: You can create solutions that combine machine learning models with advanced image analysis techniques to extract information from images, including "tags" that could help catalog the image or even descriptive captions that summarize the scene shown in the image.
	**Face detection, analysis, and recognition**: Face detection is a specialized form of object detection that locates human faces in an image. This can be combined with classification and facial geometry analysis techniques to recognize individuals based on their facial features.
	**Optical character recognition (OCR)**: Optical character recognition is a technique used to detect and read text in images. You can use OCR to read text in photographs (for example, road signs or store fronts) or to extract information from scanned documents such as letters, invoices, or forms.

### Understand natural language processing
	Natural language processing (NLP) is the area of AI that deals with creating software that understands written and spoken language.

	NLP enables you to create software that can:

	Analyze and interpret text in documents, email messages, and other sources.
	Interpret spoken language, and synthesize speech responses.
	Automatically translate spoken or written phrases between languages.
	Interpret commands and determine appropriate actions.
	For example, Starship Commander is a virtual reality (VR) game from Human Interact that takes place in a science fiction world. The game uses natural language processing to enable players to control the narrative and interact with in-game characters and starship systems.

### Understand knowledge mining

	Knowledge mining is the term used to describe solutions that involve extracting information from large volumes of often unstructured data to create a searchable knowledge store.

	**Knowledge mining in Microsoft Azure**
		One of these knowledge mining solutions is Azure Cognitive Search, a private, enterprise, search solution that has tools for building indexes. The indexes can then be used for internal only use, or to enable searchable content on public facing internet assets.

		Azure Cognitive Search can utilize the built-in AI capabilities of Azure Cognitive Services such as image processing, content extraction, and natural language processing to perform knowledge mining of documents. The product's AI capabilities makes it possible to index previously unsearchable documents and to extract and surface insights from large amounts of data quickly.

	**Knowledge mining in Microsoft Azure**
		One of these knowledge mining solutions is Azure Cognitive Search, a private, enterprise, search solution that has tools for building indexes. The indexes can then be used for internal only use, or to enable searchable content on public facing internet assets.

		Azure Cognitive Search can utilize the built-in AI capabilities of Azure Cognitive Services such as image processing, content extraction, and natural language processing to perform knowledge mining of documents. The product's AI capabilities makes it possible to index previously unsearchable documents and to extract and surface insights from large amounts of data quickly.
### Challenges and risks with AI
	**Bias can affect results**: A loan-approval model discriminates by gender due to bias in the data with which it was trained
	**Errors may cause harm**: An autonomous vehicle experiences a system failure and causes a collision
	**Data could be exposed**: A medical diagnostic bot is trained using sensitive patient data, which is stored insecurely
	**Solutions may not work for everyone**: A home automation assistant provides no audio output for visually impaired users
	**Users must trust a complex system**: An AI-based financial tool makes investment recommendations - what are they based on?
	**Who's liable for AI-driven decisions?**: An innocent person is convicted of a crime based on evidence from facial recognition – who's responsible?

### Understand Responsible AI
	At Microsoft, AI software development is guided by a set of six principles, designed to ensure that AI applications provide amazing solutions to difficult problems without any unintended negative consequences.

	**Fairness**
		AI systems should treat all people fairly. For example, suppose you create a machine learning model to support a loan approval application for a bank. The model should predict whether the loan should be approved or denied without bias. This bias could be based on gender, ethnicity, or other factors that result in an unfair advantage or disadvantage to specific groups of applicants.

		Azure Machine Learning includes the capability to interpret models and quantify the extent to which each feature of the data influences the model's prediction. This capability helps data scientists and developers identify and mitigate bias in the model.

		Another example is Microsoft's implementation of Responsible AI with the Face service, which retires facial recognition capabilities that can be used to try to infer emotional states and identity attributes. These capabilities, if misused, can subject people to stereotyping, discrimination or unfair denial of services.
	**Reliability and safety**
		AI systems should perform reliably and safely. For example, consider an AI-based software system for an autonomous vehicle; or a machine learning model that diagnoses patient symptoms and recommends prescriptions. Unreliability in these kinds of systems can result in substantial risk to human life.

		AI-based software application development must be subjected to rigorous testing and deployment management processes to ensure that they work as expected before release.

	**Privacy and security**
		AI systems should be secure and respect privacy. The machine learning models on which AI systems are based rely on large volumes of data, which may contain personal details that must be kept private. Even after the models are trained and the system is in production, privacy and security need to be considered. As the system uses new data to make predictions or take action, both the data and decisions made from the data may be subject to privacy or security concerns.
	**Inclusiveness**
		AI systems should empower everyone and engage people. AI should bring benefits to all parts of society, regardless of physical ability, gender, sexual orientation, ethnicity, or other factors.
	**Transparency**
		AI systems should be understandable. Users should be made fully aware of the purpose of the system, how it works, and what limitations may be expected.

	**Accountability**
		People should be accountable for AI systems. Designers and developers of AI-based solutions should work within a framework of governance and organizational principles that ensure the solution meets ethical and legal standards that are clearly defined.


