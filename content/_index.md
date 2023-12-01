---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Analyzing Open Source Software Ecosystems
      text: |
        This [Fall 2023](https://ckids-datafirst.github.io/website/editions/2023-fall/#dates) [DataFirst project](https://ckids-datafirst.github.io/website/) attempts to [analyze code commits(source code and patch discussions) of open source software to better understand them](problem-statement). It uses data from [Linux Kernel Mailing List](data). Our work focuses on [extracting clean messages from the raw data and performing keyword extraction and summarization on individual messages and patch discussions](approach). Our initial results indicate that [most clean messages can be extracted through regular expression, and keyword extraction and summarization can be accomplished with the help of large language models such as GPT4](results).

        Gaining a deeper understanding of OSS ecosystems will enable the open source community to identify potential vulnerabilities, and define better development practices.

    design:
      columns: "1"
---