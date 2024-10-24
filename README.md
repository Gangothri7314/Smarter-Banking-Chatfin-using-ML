# Smarter-Banking-Chatfin-using-ML
The purpose of the project is to make any domain-specific website, in our case banking, more usable by integrating a chatbot that serves as an interface for customer inquiries about services. This reduces customer interaction time with websites, thereby valuing their time and improving their overall experience. As part of this project, we explored and attempted to create an intelligent chatbot that could extract relevant information, recognize various intents and execute the pre-mapped actions. To create a contextual assistant for the above purpose, we used the RASA framework. To train the model, we constructed a custom dataset that includes multiple intents and entities. Additionally, we provide some python scripts (RASA actions) that will be executed when some intents are detected. Our solution consisted of creating a pipeline having a chatbot and several actions triggered by the chatbot. These actions will connect with the database and then provide the required data or make changes according to the user’s query and display the feedback back to the user via the chat widget.
To create this contextual assistant we use Django is a robust and versatile Python-based web framework that's widely used to build scalable and secure applications, including fintech solutions like Smarter Banking ChatFin. Here’s how Django is typically used in a smarter banking solution that integrates machine learning (ML):

1. Framework Overview:
Django's architecture supports the Model-View-Template (MVT) pattern, which helps organize the development process for financial applications. The primary components are:

Models: Represent the database schema (e.g., users, transactions).

Views: Handle business logic, processing user requests.

Templates: Render the interface for end users.

2. Why Django for Smarter Banking:

Security: Django comes with built-in security features such as protection against SQL injection, cross-site scripting (XSS), and cross-site request forgery (CSRF), crucial for banking systems.

Scalability: Django is designed to handle high traffic, making it perfect for financial applications that need to process thousands or millions of requests simultaneously.
Rapid Development: Django's built-in functionalities and extensive libraries allow for quick prototyping and development of features, important for dynamic banking environments.

ORM (Object-Relational Mapping): Django ORM allows seamless integration between the database and the Python code, which helps manage complex banking datasets (transactions, accounts, etc.).
