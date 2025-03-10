# [Teach Anything](https://www.teach-anything.com/)

Teach you anything in seconds use AI.

https://user-images.githubusercontent.com/2337506/216798367-2b5e3bc7-5cbd-4173-9ea7-0e1e85ea87dc.mov

## Sponsor

<table>
  <tr>
    <td>
        <a href="https://e.cash" target="_blank" >
            <img alt="eCash" src="public/ecash.png" height="64px;" >
        </a>
    </td>
    <td >
        <a href="https://neuronadigital.academy/" target="_blank" >
            <img alt="eCash" src="public/NeuronaDigital.jpg" height="64px;" >
        </a>
    </td>
  </tr>
   <tr>
    <td >
        <a href="https://sailboatui.com/?ref=teach-anything" target="_blank" >
            <img alt="eCash" src="public/sailboatui.svg" height="64px;" >
        </a>
    </td>
    <td >
        <a href="https://www.buymeacoffee.com/lvwzhen" target="_blank" >
            ❤️ Your logo
        </a>
    </td>
  </tr>
</table>


## Language support
`English`, `Simplified Chinese`, `Traditional Chinese`, `Japanese`, `Italian`, `German`, `Spanish`,`French`,`Dutch` ,`Korean`,`Khmer`, `Hindi`

PR welcome

## How it works

Inspired by [TwtterBio](https://github.com/Nutlope/twitterbio) and [Danny Richman](https://twitter.com/DannyRichman/status/1598254671591723008?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1598254671591723008%7Ctwgr%5Eb7deab6eb03d86a1b9ac13f7e38cdeab57a40cbb%7Ctwcon%5Es1_&ref_url=https%3A%2F%2Fwww.buzzfeednews.com%2Farticle%2Ftomwarren%2Fai-app-dyslexic-email-writer-help)

Powerd by [OpenAI](https://openai.com/), [Next.js](https://nextjs.org/), [Vercel](https://vercel.com/) and [Tailwind CSS](https://tailwindcss.com/).

This project uses the [OpenAI GPT-3 API](https://openai.com/api/) (specifically, text-davinci-003) and [Vercel Edge functions](https://vercel.com/features/edge-functions) with streaming. It constructs a prompt based on the form and user input, sends it to the GPT-3 API via a Vercel Edge function, then streams the response back to the application.

Video and blog post coming soon on how to build apps with OpenAI and Vercel Edge functions!

## Running Locally

After cloning the repo, go to [OpenAI](https://beta.openai.com/account/api-keys) to make an account and put your API key in a file called `.env`.

Then, run the application in the command line and it will be available at `http://localhost:3000`.

```bash
npm run dev
```

## One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/lvwzhen/teach-anything&env=OPENAI_API_KEY&project-name=teach-anything&repo-name=teach-anything)
