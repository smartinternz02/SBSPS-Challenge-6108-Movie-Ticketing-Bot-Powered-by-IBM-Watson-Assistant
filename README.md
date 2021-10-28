# SBSPS-Challenge-6108-Movie-Ticketing-Bot-Powered-by-IBM-Watson-Assistant
<h1>Movie Ticketing Bot Powered by IBM Watson Assistant</h1>
  
  <h2> Chat Bot Preview LINK :- </h2>   https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=eu-gb&integrationID=1b71a886-a6df-4d8e-b579-53c26702ef3c&serviceInstanceID=8aa61aa7-06e4-4aa3-b7dc-32b5c0045cf7
  
  <h2>VIDEO DEMONSTRATION LINK:- </h2>https://drive.google.com/file/d/1J1FcTWGs9YKGq0TyXZemgnTEaB45et_g/view?usp=sharing
  
<h2>Watson Assistant</h2>

The Watson Assistant service available as a Platform as a Service (PaaS) on IBM Cloud provides a AI tooling that can easily allow creating converstaional solutions that fits one's business needs.
<h1>Basic Concepts & Terminologies Workspace</h1>
A workspace in Watson Assistant is a container for all artifacts that define the behaviour of your system, i.e. Chatbot.

<h3>Utterance</h3>
An utterance or user example is an input that a user provides when prompted, including questions and statements.

<h3> Intent</h3>
An intent is the purpose expressed by user input, which usually acts as a label for a group of utterances. For instance, if "Where can I find the gym?" is the question provided by a user, the Watson Assistant service understands that the user’s intent is to ask about the location of something (in this case, the gym, which is called the entity).

<h3>Entity</h3>
An entity is usually a classification of objects aimed to help alert the response to an intent. Using the same example of the user asking "Where can I find the gym?", the Watson Assistant service understands that the entity being asked about is the gym. The entity could have been something else like the restaurant, to which the Watson Assistant service would have provided a different response, despite the intent being the same.

<h3>Context</h3>
Context is information gathered from an external source to customize responses.

<h3>Response</h3>
A response is what the Conversation service returns to the user’s utterances based on the detected intent, and entity can be in the form of text or an action like displaying a map.

<h3>Dialog</h3>
A dialog defines the conversational flow, which is simply a logical flow that determines responses based on a met condition. The dialog flows in a top-to-bottom, left-to-right fashion.

<h3>Dialog Node</h3>
A diaglog node is a single interaction in a conversation that is triggered when a condition is met and provides a response back to the user.

<h3>Slots</h3>
Slots are considered the easiest way to gather information from users, allowing what usually takes serveral dialog nodes to be consolidated into a single node.
