# Natural Language Understanding API Samples

This directory contains sample code for using Natural Language Understanding API.

OLAMI website and documentation: [http://olami.ai](http://olami.ai)

## Install:

```
npm install
```

## Run the application:

> 1. Replace **your_node_bin** to your PHP binary path.
> 2. Replace **api_url, your_app_key, your_app_secret, your_text_input** in accordance to your needs and your own data.

```
your_node_bin QuickstartTest.js api_url your_app_key your_app_secret your_text_input
```

- For example: (Simplified Chinese Request with the text "我爱欧拉蜜")

```
node QuickstartTest.js https://cn.olami.ai/cloudservice/api 172c5b7b7121407ba572da444a999999 2115d0888bd049549581b7a0a6888888 我爱欧拉蜜
```

- For example: (Traditional Chinese Request with the text "我愛歐拉蜜")

```
node QuickstartTest.js https://tw.olami.ai/cloudservice/api 999888777666555444333222111000aa 111222333444555666777888999000aa 我愛歐拉蜜
```
