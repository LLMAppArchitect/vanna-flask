# vanna-flask
Web server for chatting with your database



https://github.com/vanna-ai/vanna-flask/assets/7146154/5794c523-0c99-4a53-a558-509fa72885b9



https://vanna.ai/account/profile




# Setup

## Set your environment variables
```
VANNA_MODEL=
VANNA_API_KEY=
SNOWFLAKE_ACCOUNT=
SNOWFLAKE_USERNAME=
SNOWFLAKE_PASSWORD=
SNOWFLAKE_DATABASE=
SNOWFLAKE_WAREHOUSE=
```

## Install dependencies
```
conda create -y --name vanna python=3.10
conda activate vanna

pip install -r requirements.txt
```

``` 
pip install 'vanna[chromadb,openai,postgres]'
```

## Run the server
```
python app.py
```

