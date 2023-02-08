# Game Genie AI

Toolkit for game creators to effortlessly generate concepts, stories, art and content.

## Setup
 
### Setting Up Frontend

1. `npx create-react-app client` in app folder to create react client in new folder.

2. `npm start` in `client` folder to run server.

3. `npm i file-saver` to install file-saver package.

4. `npm i react-csv` to install react-csv.

### Setting Up Backend

In the `server` folder:

1. `npm init`

2. `npm install express cors body-parser morgan openai dotenv --save`

3. setting up react router: `npm i react-router react-router-dom`

### Setting up Firebase Auth

1. `npm i firebase`
2. `npm i react-google-button react-twitter-button` 

## Resources

1. Documentation
- [OpenAI API](https://beta.openai.com/docs/introduction)
- [Huggingface Inference API](https://huggingface.co/docs/api-inference/index)

2. Video tutorials
- [Let's Build ChatGPT 2.0 with React JS and OpenAI on your PC!](https://youtu.be/qwM23_kF4v4)
- [How To Use ChatGPT With JavaScript (NodeJS & Express)](https://youtu.be/UQamG425RD0)

3. Buildspace tutorials
- [Build your own AI writing assistant w/ GPT-3](https://buildspace.so/builds/ai-writer)
- [Build your own AI Avatar generator w/ Stable Diffusion](https://buildspace.so/builds/ai-avatar)

4. Firebase Auth
- [Google Authentication With React JS & Firebase - Sign In With Google - Firebase v9](https://www.youtube.com/watch?v=cZAnibwI9u8)
- [Add Firebase to your JavaScript project](https://firebase.google.com/docs/web/setup)
- [Authenticate Using Google with JavaScript](https://firebase.google.com/docs/auth/web/google-signin)

A) TODO: Deploying backend to Vercel 
- https://vercel.com/guides/using-express-with-vercel
- https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel
- https://dev.to/andrewbaisden/how-to-deploy-a-node-express-app-to-vercel-2aa

B) Stretch: Fine-tuning OpenAI models
- https://www.mlq.ai/fine-tuning-gpt-3-question-answer-bot/
- https://github.com/openai/openai-cookbook/blob/main/examples/Question_answering_using_embeddings.ipynb
- https://github.com/openai/openai-cookbook/blob/57024c70cff473fb520105e9aea3ab4e514be0df/examples/fine-tuned_qa/olympics-1-collect-data.ipynb

(i) Preparing Dataset for fine-tuning
- https://www.reddit.com/r/GPT3/comments/10jjbf1/using_davinci003_with_our_docs_for_automated/
- https://www.patterns.app/blog/2022/12/21/finetune-llm-tech-support/

(ii) No-code model builder for fine-tuning
- https://www.reddit.com/r/OpenAI/comments/zpv2fy/why_arent_more_people_creating_custom_openai/
- https://no-code-ai-model-builder.com/custom-models
