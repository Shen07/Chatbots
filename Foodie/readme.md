 # Env Setup for Rasa 2.0


- Python: 3.8.3 
 - Tensorflow: 2.3.1 
 - Rasa Version     : 2.0.2 
 - Rasa SDK Version : 2.0.0 
 - Rasa X Version   : latest (0.3.8) 
 - Python Version   :3.8.3

## Dependencies
 
 1. Microsoft visual c++ build tools (for rasa x)  
 2. `conda install git`(for running rasa x locally in windows)  
 3. pip version should be less than 21.0 for rasa x to work (any os)

 
 


 **Installing on windows**

    

    pip install rasa[spacy]==2.0.2

for installing rasa x locally in windows follow the steps
  - *option 1* `pip install --upgrade pip==20.2`
  - then `pip3 install rasa-x --extra-index-url https://pypi.rasa.com/simple`
  - *option 2* `pip install --use-deprecated=legacy-resolver rasa-x --extra-index-url https://pypi.rasa.com/simple`

 
 
**for server install** 
 
 https://rasa.com/docs/rasa-x/installation-and-setup/installation-guide/
 
 
 
 
 
 
 
 
 
 

>  links for resources

 
 [rasa tutorials](https://blog.rasa.com/tag/tutorials/)
 
 [rasa docs](https://rasa.com/docs/rasa/)
 
 [rasa-x_common installation issue](https://forum.rasa.com/t/unable-to-install-rasa-x/39951)
 
 
 [ rasa workflow explained](https://medium.com/@Zack.hardtoname/rasa-mechanism-work-flow-simply-explained-b44e85d5a6f1#:~:text=Rasa%20has%20become%20a%20popular,Core%20(mainly%20constructing%20conversations))
 
 
[rasa bot building](https://towardsdatascience.com/a-chatbot-from-future-building-an-end-to-end-conversational-assistant-with-rasa-ai-51a1c93dabf2)
 
[Analytics vidya tutorial](https://www.analyticsvidhya.com/blog/2019/04/learn-build-chatbot-rasa-nlp-ipl/#:~:text=Overview%20of%20the%20Rasa%20Chatbot&text=As%20soon%20as%20Rasa%20receives,is%20handled%20by%20Rasa%20NLU&text=Rasa%20then%20tries%20to%20predict%20what%20it%20should%20do%20next.)
 
 
[chatbot with rasa 2.0](https://towardsdatascience.com/chatbots-made-easier-with-rasa-2-0-b999323cdde)
 
 [rasa installation](https://rasa.com/docs/rasa/installation/)


> Videos
> 
[Step by step tutorial using rasa (old version)](https://www.youtube.com/watch?v=sazsWmP2d3o)

[Assistant with Rasa 2.0](https://www.youtube.com/watch?v=xK1I9z52IB4)

[Creating NLU data with rasa 1.8.0](https://www.youtube.com/watch?v=k5UeywXA28k)
 this is still useful.
