# llSPS-INT-928-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding

Enhanced a typical chatbot with the ability to access Watson Discovery collections. To improve search results, used Smart Document Understanding to build a better model in Watson Discovery.This repository contains the project report and the Node-Red flow of the chatbot developed using various IBM Watson Services.

The typical customer care chatbot can answer simple questions, such as store locations and hours, directions, and maybe even making appointments. When a question falls outside of the scope of the pre-determined question set, the option is typically to tell the customer the question isn’t valid or offer to speak to a real person.

In this project, there will be another option. If the customer question is about the operation of a device, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the device’s owners manual. So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the owners manual to help solve our customers’ problems. So unless and untill customer specifically asks for a customer representative the bot will try to solve all your queries.

Smart document understanding (SDU) allows you to train IBM Watson Discovery to interpret structural elements of complex and diverse documents, including document fields like footers and headlines as well as tables and text. Visually annotate a sampling of your documents and instantly visualize how the machine learning model will interpret your text, updating your model in real time to achieve the desired results. Use this feature across roles and use cases to reduce the time experts spend reviewing and analyzing complex documents without compromising accuracy or increasing risks. Smart document understanding in IBM Watson Discovery helps you rapidly extract new insights in context for deeper understanding, cleaner answers, and confident recommendations.

Then using Watson actions as webhook, Watson Discovery can be integrated with Watson assistant. Finally using Node-Red, Watson assistant can be integrated with a web UI. This UI can then be used to connect with Watson assistant and chat with it.

Watson Discovery Document: LG user manual

Node-Red Dashboard Link: https://project-ic.eu-gb.mybluemix.net/ui/#!/0?socketid=KWMd-SOR4Dor1G65AAAm

Youtube Video Link: https://youtu.be/YyenwhKj4G4
