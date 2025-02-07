# Autogen sample

## 코드스페이스 개발환경 구성

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new?quickstart=1)

## 환경 설정

  ```bash
  mv OAI_CONFIG_LIST_sample1.json OAI_CONFIG_LIST.json
  ```

```json
[
  {
    "model": "gpt-4o",
    "api_type": "azure",
    "api_key": "<your-api-key>",
    "base_url": "<your-base-url>",
    "api_version": "2024-02-01"
  },
  {
    "model": "gpt-4",
    "api_type": "azure",
    "api_key": "<your-api-key>",
    "base_url": "<your-base-url>",
    "api_version": "2024-02-01"
  }
]

```
## 심플 채팅 앱

  ```bash
  cd chainlit
  chainlit run app.py
  ```

## Autogen Studio

  ```bash
  autogenstudio ui --host 0.0.0.0
  ```

## Autogen 샘플 notebook

  * [1-get-started](./1-get-started.ipynb)

  * [2-task-solve-code-interpreter](./2-task-solve-code-interpreter.ipynb)

  * [3-data-visualize-groupchat](./3-data-visualize-groupchat.ipynb)

  * [4-nested-chat](./4-nested-chat.ipynb)
