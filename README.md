# gpt2-large

This is the basic model in GPT-2.

generate senctence based gpt2-large model

# How to use
This API has 2 routing address

# POST parameter

/long

text : begining of the text you want to generate

number_samples : the number of sentence that will be generated

length : the length of each sentence

/short

text : begining of the text you want to generate

number_samples : the number of word that will be generated

# With CLI :

curl --location --request POST 'https://main-gpt2-large-jeong-hyun-su.endpoint.ainize.ai/gpt2-large/short' --form 'text=We have more cases' --form 'num_samples=5'

curl --location --request POST 'https://main-gpt2-large-jeong-hyun-su.endpoint.ainize.ai/gpt2-large/long' --form 'text=We have more cases' --form 'num_samples=5' --form 'length=10'


# With swagger :

You can test this API with swagger.yaml on swagger editor