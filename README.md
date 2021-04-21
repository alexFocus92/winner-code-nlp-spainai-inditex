# nlp-spainai-transformers

## Solution for 1st prize in the NLP challenge of the Hackathon of SpainAI 2021

http://www.spain-ai.com/hackathon2020_reto_NLP.php#page_top

This challenge does not ask for a simple classification, but rather the generation of a product name based on its description.

In addition: none of the names of the train set appear in the test set, so it is not a classification problem, but rather it is requested to generate the name of the product.

## Description

You will have a train dataset with two columns: the product names, in the "name" column, and the descriptions associated with those names, in the "description" column.

The test dataset has a single column, with the description of a set of products, for which you have not seen the name before (they are not in the train set), and you will have to generate a name associated with the description.

Also: none of the names in the train set appear in the train set, so it is not a classification problem, but rather it is requested to generate the name.

As we know that it is a complicated challenge, you can submit different candidate names for each of the associated descriptions. Of course, the file that you send must respect the same order of the descriptions of the test set provided, since the validation program will check if any of the candidate names that you send for the first description correspond with the real name for that first product. , it will check if the second name corresponds to the second description and so on for all the lines of the file that you send us.
