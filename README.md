# Keyless Chatbot UI with WindowAI

Keyless Chatbot UI allows simplifies the connection between the Chatbot UI kit and any chat model (OpenAI, Cohere, GPT) by leveraging [ChatbotUI](https://github.com/mckaywrigley/chatbot-ui) Frontend and [WindowAI](https://github.com/alexanderatallah/window.ai)) decentralized LLM key handling. 

The idea is that as an LLM App developer, you shouldn't have to care about what models are being used and what are the users credentials. This is a huge friction point at the moment given that you have to either pay for the credits upfront or add a section for users to paste their own key (with the associated trust issues).

See a [demo]().

![Chatbot UI](./public/screenshot.png)



## Built by:
- [Jan 🚀](https://twitter.com/jcllobet)
- [Jonny Xu 🦄](https://twitter.com/chemocheese)
- [Nolan Clement 🥶](https://twitter.com/nolangclement)
- [Yanni Kouloumbis 🐐](https://twitter.com/ykouloumbis)


## Updates

Keyless Chatbot UI will be updated over time. Expect frequent improvements.

We currently supports GPT3.5-turbo. Open to contributions with integrations that support:
- GPTNeo
- Cohere
- Local
- GPT4

Given that those are all the models that WindowAI supports at the moment.

## TODO
- WindowAI --> integrate with window.ai --> (window as any).ai.getCompletion() -->
- Display current model from async getCurrentModel(): Promise<LLM>
- GPT4 potential support on LLM objects (for once he has it)



## Fo
**Next up:**
- [ ] Add support for GPT4
- [ ] Add support for GPTNeo
- [ ] Add support for Cohere
- [ ] Add support for Local

**Recent updates:**
- Everything from [Chatbot UI]() until 3/27/23 including:
    - Prompt templates
    - Regenerate & edit responses
    - Folders
    - Search chat content
    - Stop message generation
    - Import/Export chats
    - Custom system prompt
    - Error handling
    - Search conversations
    - Code syntax highlighting
    - Toggle sidebar
    - Conversation naming
    - Github flavored markdown
    - Markdown support

## Modifications

Modify the chat interface in `components/Chat`.

Modify the sidebar interface in `components/Sidebar`.

Modify the system prompt in `utils/index.ts`.

## Deploy

**Vercel**

Live demo: [here]()

Host your own live version of Chatbot UI with Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YanniKouloumbis/chatbot-ui)

**Replit**

Fork Chatbot UI on Replit [here]().

**Docker**

- Not yet supported. Open to contributions.

## Running Locally

**1. Clone Repo**

```bash
git clone 
```

**2. Install Dependencies**

```bash
npm i
```

**3. Provide OpenAI API Key**

No need! It is all handled by WindowAI.

**4. Run App**

```bash
npm run dev
```

**5. Use It**

You should be able to start chatting.

## Configuration

When deploying the application, the following environment variables can be set:

## Demo:

We have a live demo of the site hosted on Vercel that you can check out [here] (https://chatbot-ui-alpha-six-31.vercel.app/)

## Contact

If you have any questions, feel free to reach to join the [windowAI discord](https://discord.gg/wZsdGtAp) or ping [Yanni}() or [Alex](), co-founder of [WindowAI]() and former CTO of OpenSea.
