# PartyRock-Champs
Private notes on good PartyRock.aws apps

All apps are public, if not stated otherwise:

* Most generic of all PartyRock apps:
  https://partyrock.aws/u/fspiess/QTaVfsukl/Prompt-Interpreter  
  Snippet of “getCompletion” request to backend:
  “text”: "Based on the user's prompt:
  Explain different types of prompt engineering., generate a relevant response."
  In turn, the only system prompt here is "Based on the user's prompt:" which is as generic as possible!
  "modelName": "bedrock-anthropic.claude-3-5-sonnet-v2-0",

* K8s Manifest Generator: https://partyrock.aws/u/fspiess/MnqyMNxWc/Kubernetes-Manifest-Generator 
  -> super useful, especially in on-the-fly example creation in an EKS class. So far, I never encountered any mistakes!

* AWS CLI script generator: https://partyrock.aws/u/fspiess/YOveBtNbW/AWS-CLI-Script-Generator
  creates bash scripts containing one or more AWS CLI commands

* Dockerfile generator and deployment assistant: https://partyrock.aws/u/fspiess/tM63Spm3z/LLM-Dockerfile-Generator-and-Deployment-Guide-Assistant

* Call for Papers (CFP) helper created by Brooke Jamieson: https://partyrock.aws/u/brooke/yHmCgdiIO/CFP-Helper/
  * related article: https://community.aws/content/2pOziGeyjl5wXVmxaL82dpihvq4/10-aws-cfp-ideas-for-2025-how-to-write-your-own-with-partyrock-and-amazon-q
