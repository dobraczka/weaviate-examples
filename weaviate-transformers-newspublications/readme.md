# Example docker-compose configuration file with text2vec-transformers, NER, spellcheck, Q&A and demo dataset

Here you find an example docker-compose configuration file to start up Weaviate with the [`text2vec-transformers module`](https://www.semi.technology/developers/weaviate/current/modules/text2vec-transformer.html), a News Publications example dataset and three other modules: [`ner-transformers`](https://www.semi.technology/developers/weaviate/current/modules/ner-transformers.html), [`text-spellcheck`](https://www.semi.technology/developers/weaviate/current/modules/spellcheck.html) and the [`qna-transformers module`](https://www.semi.technology/developers/weaviate/current/modules/qna-transformers.html). Note that the `docker-compose-gpu.yaml` example assumes you have a GPU available.

## How to use

Download the `docker-compose.yml` file. In the folder where you stored the file, run `docker-compose up`. Now, Weaviate, the modules and the dataset will be retrieved, Weaviate will start up with the text2vec-transformers module, and load in the demo data. Weaviate will be running at `localhost:8080`. You can then navigate to [console.semi.technology](https://console.semi.technology/) and connect to `http://localhost:8080`, to query the dataset.