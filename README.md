<p align="center">
  <img src="https://raw.githubusercontent.com/ShreymShah/ShreymShah/main/assets/banner.svg" alt="Shrey Shah" width="100%"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shrey-shah-0881ba22a"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:shreysms04@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

I build cloud and generative AI systems for real clients as a Junior Software Developer at Amazon Web Services, usually as the only engineer, from the discovery call to the deploy. Computer Science senior at Cal Poly San Luis Obispo, graduating May 2027.

**Looking for:** 2027 new grad roles in software engineering, AI engineering, and forward deployed engineering.

### Client work
<sub>These live in the <a href="https://github.com/cal-poly-dxhub">cal-poly-dxhub</a> org, so they don't show in my repos. Click a project to expand it.</sub>

<details open>
<summary><b>Manifest MedEx Data Quality Platform</b>: serverless healthcare data platform for a health information exchange</summary>

<p><img src="https://img.shields.io/badge/AWS_CDK-FF9900?style=flat-square" alt="AWS CDK"/> <img src="https://img.shields.io/badge/Lambda-FF9900?style=flat-square" alt="Lambda"/> <img src="https://img.shields.io/badge/EventBridge-FF9900?style=flat-square" alt="EventBridge"/> <img src="https://img.shields.io/badge/SQS-FF9900?style=flat-square" alt="SQS"/> <img src="https://img.shields.io/badge/OpenSearch_Serverless-FF9900?style=flat-square" alt="OpenSearch Serverless"/> <img src="https://img.shields.io/badge/Aurora_PostgreSQL-FF9900?style=flat-square" alt="Aurora PostgreSQL"/> <img src="https://img.shields.io/badge/Cognito-FF9900?style=flat-square" alt="Cognito"/> <img src="https://img.shields.io/badge/CloudFront-FF9900?style=flat-square" alt="CloudFront"/> <img src="https://img.shields.io/badge/React-149ECA?style=flat-square" alt="React"/></p>

[Repo →](https://github.com/cal-poly-dxhub/manifest-medex-data-analysis)

- Ingests HL7 v2 messages and CCDA documents. Sole engineer across infrastructure, backend, and frontend. I joined the discovery calls, gathered the requirements, and scoped the project with the customer.
- Designed the architecture for their volume of about 60 million messages a month: S3, EventBridge, SQS with a dead-letter queue, Lambda, OpenSearch Serverless, and Aurora PostgreSQL in a private VPC, with a Cognito-protected React explorer behind CloudFront.
- Stored the files in S3 and the metadata in Aurora for cost and compute, and chose Aurora because the customer wanted SQL search.
- Prototype, now in customer testing.

</details>

<details>
<summary><b>Orcutt Schools Chatbot</b>: RAG chatbot on Amazon Bedrock, live for a school district</summary>

<p><img src="https://img.shields.io/badge/Amazon_Bedrock-FF9900?style=flat-square" alt="Amazon Bedrock"/> <img src="https://img.shields.io/badge/RAG-6E40C9?style=flat-square" alt="RAG"/> <img src="https://img.shields.io/badge/OCR-6E40C9?style=flat-square" alt="OCR"/> <img src="https://img.shields.io/badge/React-149ECA?style=flat-square" alt="React"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" alt="Python"/></p>

[Repo →](https://github.com/cal-poly-dxhub/orcutt-schools-chatbot)

- Built solo for a district of about 5,000 students and 700 staff. It answered about 700 questions in its first five months.
- The only source was a stale, disorganized website, and many board meeting summaries were images. I added OCR, extracted meeting dates as metadata, and had the model prioritize nearby meetings.
- Answers can be scoped to one school with a dropdown, and a classifier picks the school from the question when none is selected.
- Worked with the district on quality: I wrote a test question set and had staff test it with their own questions.

</details>

<details>
<summary><b>Health Integration Engine</b>: drag-and-drop builder for AWS Step Functions workflows</summary>

<p><img src="https://img.shields.io/badge/Step_Functions-FF9900?style=flat-square" alt="Step Functions"/> <img src="https://img.shields.io/badge/CloudFormation-FF9900?style=flat-square" alt="CloudFormation"/> <img src="https://img.shields.io/badge/API_Gateway_WebSocket-FF9900?style=flat-square" alt="API Gateway WebSocket"/> <img src="https://img.shields.io/badge/S3-FF9900?style=flat-square" alt="S3"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square" alt="TypeScript"/></p>

[Repo →](https://github.com/cal-poly-dxhub/health-integration-engine)

- Took an early prototype and built it into an open-source tool that lets non-engineers design healthcare data pipelines, such as HL7 message routing, and deploy them to AWS without writing code.
- Deploys through CloudFormation, with live progress over WebSocket and S3 event triggers that start workflows.

</details>

<details>
<summary><b>Invoiceable</b>: Bedrock invoice extraction, deployed for Cal Poly Pomona</summary>

<p><img src="https://img.shields.io/badge/Amazon_Bedrock-FF9900?style=flat-square" alt="Amazon Bedrock"/> <img src="https://img.shields.io/badge/AWS_CDK-FF9900?style=flat-square" alt="AWS CDK"/></p>

[Repo →](https://github.com/cal-poly-dxhub/ap-invoice-extractor)

- Started as a student project I mentored. I engineered the AWS CDK infrastructure, handled the customer engagement, and deployed it to production.

</details>

<details>
<summary><b>React + OpenSearch RAG framework</b>: reusable chatbot reference architecture I wrote</summary>

<p><img src="https://img.shields.io/badge/Amazon_Bedrock-FF9900?style=flat-square" alt="Amazon Bedrock"/> <img src="https://img.shields.io/badge/OpenSearch-FF9900?style=flat-square" alt="OpenSearch"/> <img src="https://img.shields.io/badge/AWS_CDK-FF9900?style=flat-square" alt="AWS CDK"/> <img src="https://img.shields.io/badge/React-149ECA?style=flat-square" alt="React"/></p>

[Repo →](https://github.com/cal-poly-dxhub/react-opensearch-chatbot-framework)

- A starting point for prototyping and deploying RAG chatbots quickly.

</details>

### Personal projects

<details>
<summary><b>AI Stock Screener</b> (currently building): Python computes the financials, the LLM only writes the narrative</summary>

<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" alt="Python"/> <img src="https://img.shields.io/badge/LLM-6E40C9?style=flat-square" alt="LLM"/> <img src="https://img.shields.io/badge/SEC_EDGAR-2F4F4F?style=flat-square" alt="SEC EDGAR"/> <img src="https://img.shields.io/badge/Finnhub-2F4F4F?style=flat-square" alt="Finnhub"/></p>

[Repo →](https://github.com/ShreymShah/ai-stock-screener)

- Equity research for US and Indian markets. Python computes every ratio, a ROIC-versus-WACC moat test, and a DCF, and the prompts forbid the model from stating any number it was not given. The one AI-extracted figure, insider ownership from SEC proxy filings, is labeled with its source quote.
- Pulls data no single API has: India shareholding from screener.in, US institutional flow from Nasdaq, and peer medians from Finnhub, reconciled against SEC EDGAR filings.
- Caught a case where Yahoo Finance reported 7.5% insider ownership and the SEC filing showed 41.5%. The report now shows both and explains the gap.

</details>

<details>
<summary><b>Futures Breakout Trading Bot</b>: async Python bot for TastyTrade</summary>

<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" alt="Python"/> <img src="https://img.shields.io/badge/asyncio-3776AB?style=flat-square" alt="asyncio"/> <img src="https://img.shields.io/badge/TastyTrade_API-2F4F4F?style=flat-square" alt="TastyTrade API"/> <img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square" alt="Telegram"/> <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square" alt="pytest"/></p>

[Repo →](https://github.com/ShreymShah/breakout-trading-bot)

- OCO bracket orders, and if a bracket cannot be placed after three retries, the bot market-closes the position instead of leaving it unprotected.
- Pauses new entries after repeated auth failures and resumes on its own, reconciles open trades with the broker after a restart, and alerts on Telegram if the candle stream goes quiet.
- Dry-run by default, with unit tests for the strategy, risk, and state logic.

</details>

### Systems

<details>
<summary><b>Unix Systems Programming in C</b>: multithreaded HTTP server, file system simulator, and parallel downloader</summary>

<p><img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square" alt="C"/> <img src="https://img.shields.io/badge/POSIX-2F4F4F?style=flat-square" alt="POSIX"/> <img src="https://img.shields.io/badge/pthreads-2F4F4F?style=flat-square" alt="pthreads"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square" alt="Linux"/></p>

[Repo →](https://github.com/ShreymShah/unix-systems-programming-c)

- Multithreaded HTTP/1.1 server on TCP sockets, with a thread per connection, GET and HEAD support, path-traversal protection, and correct status codes.
- Inode-based file system simulator with directory entries and binary file I/O.
- Parallel downloader built on fork, execvp, and waitpid, with a concurrency limit.

</details>

<details>
<summary><b>Reliable Transport and P2P</b>: TCP Reno over UDP and a peer-to-peer file-sharing network</summary>

<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" alt="Python"/> <img src="https://img.shields.io/badge/UDP-2F4F4F?style=flat-square" alt="UDP"/> <img src="https://img.shields.io/badge/TCP_Reno-2F4F4F?style=flat-square" alt="TCP Reno"/> <img src="https://img.shields.io/badge/Sockets-2F4F4F?style=flat-square" alt="Sockets"/></p>

[Repo →](https://github.com/ShreymShah/reliable-transport-p2p)

- TCP Reno congestion control implemented from scratch over UDP: slow start, congestion avoidance, fast retransmit, fast recovery, and timeouts, with cwnd graphs.
- P2P file-sharing network with a central tracker, a custom binary wire protocol, retransmission, and MD5 integrity checks. Standard library only.

</details>

### Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=py,ts,js,c,java,aws,react,nodejs,postgres,mysql,git,linux" alt="Python, TypeScript, JavaScript, C, Java, AWS, React, Node.js, PostgreSQL, MySQL, Git, Linux"/>
</p>

### Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ShreymShah/ShreymShah/main/profile-3d-contrib/profile-night-rainbow.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ShreymShah/ShreymShah/main/profile-3d-contrib/profile-green-animate.svg" />
  <img src="https://raw.githubusercontent.com/ShreymShah/ShreymShah/main/profile-3d-contrib/profile-night-rainbow.svg" alt="3D contribution graph" />
</picture>
