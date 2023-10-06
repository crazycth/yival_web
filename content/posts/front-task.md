---
title: "front-task"
date: 2023-10-05T11:10:36+08:00
draft: false
language: en
featured_image: ../assets/images/featured/post-demo-featured.jpg
summary: Use Yival, the open source AIGC framwork in action for cases like startup company headline generations and more.
description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed cursus, odio nec venenatis lacinia, lacus lectus varius nisi, in tristique mi purus ut libero. Vestibulum vel convallis felis. Ut finibus lorem vestibulum lobortis rhoncus.
author: YiVal
authorimage: ../assets/images/global/yival_author_img.jpeg
categories: Blog
tags: ["YiVal", "prompting"]
---

# Yival Tutorial

We provide some easy-to-use demos for you to directly experience the effect
of Yival in the README on Github.

## Startup Company Headline Generation 🤖

<!-- google colab:[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1EiWUL8rE_kfNLXVPowCWCh6hwHFagvs_?usp=sharing) -->

-   google colab: [headline_generation_colab](https://colab.research.google.com/drive/1EiWUL8rE_kfNLXVPowCWCh6hwHFagvs_?usp=sharing)
-   notebook : [headline_generation](./headline_generation.ipynb)

The goal of this demo is to generate corresponding page headlines based on the
names of startup companies. YiVal supports automatic generation of related prompts
and test data according to this goal, and self-evaluation based on the configured
evaluator. It provides different result selection methods such as AHP to confirm
the final result.

For how to confirm the prompt used by the generator, we recommend using a
step-by-step optimization pipeline mode, continuously adjusting based on
the test case results. We provide an example : [pipeline_prompt_generation](https://colab.research.google.com/drive/1tr5s_adAPmI9Mv6Zz97JnTGIh3mGojsi?usp=sharing)

<!-- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tr5s_adAPmI9Mv6Zz97JnTGIh3mGojsi?usp=sharing) -->

## Basic Demo

### Basic Interactive Mode

To get started with a demo for basic interactive mode of YiVal, run the following
command:

```shell
yival demo --basic_interactive
```

Once started, navigate to the following address in your web browser:

<http://127.0.0.1:8073/interactive>

<details>
  <summary>Click to view the screenshot</summary>
  
  ![Screenshot 2023-08-17 at 10 55 31 PM](https://github.com/YiVal/YiVal/assets/1544154/a720c3ad-1288-4830-8a3d-377d9827f46e)
  
</details>

For more details on this demo, check out the [Basic Interactive Mode Demo](https://github.com/YiVal/YiVal/blob/master/docs/docs/basic_interactive_mode.md#demo).

### Question Answering with expected result evaluator

```shell
yival demo --qa_expected_results
```

Once started, navigate to the following address in your web browser:
<http://127.0.0.1:8073/>

<details>
  <summary>Click to view the screenshot</summary>
  
 <img width="1288" alt="Screenshot 2023-08-18 at 1 11 44 AM" src="https://github.com/YiVal/YiVal/assets/1544154/4e9a182f-07ba-413e-9160-f38bfdc743ce">

</details>

For more details, check out the [Question Answering with expected result evaluator](https://github.com/YiVal/YiVal/blob/master/docs/qa_expected_results.md#demo).

<!-- ### Fun Cast Fortune Telling

Dive into the world of YiChing and discover your fortune on our index page.
A fun and interactive way to get started with Yival.

![Screenshot 2023-08-16 at 10 50 57 PM](https://github.com/YiVal/YiVal/assets/1544154/b5c04295-7809-4331-8cce-cc4a1ceea73c) -->
