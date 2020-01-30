# AmazonLexBasicBot
This is a very basic Amazon Lex bot illustrating integration with a Lambda function.
You can read more here:https://medium.com/@CobusGreyling/creating-a-chatbot-with-amazon-lex-and-aws-lambda-a72eb2e08598

The idea is to have a Amazon Lex bot asking your name, and passing the name as a slot value to a Lambda function.  
This funciton in turn returns the dialog to be displayed to the user, with the intent name, slot name and contextual variables.
