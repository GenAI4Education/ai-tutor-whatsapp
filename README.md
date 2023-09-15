![Building WhatsApp Clone0-2000x840px](https://github.com/GetStream/fullstack-nextjs-whatsapp-clone/assets/39677/0c74c0e7-e802-4041-8d8f-17228cca9faf)

# Fullstack WhatsApp clone using Next.js, Vercel and Supabase

This project contains all the code to run the FullStack WhatsApp clone using Next.js and Supebase.

The purpose of this repository is to demonstrate below:

- Implementing UI elements by customizing existing Stream Chat and Stream Video components.
- How to implement authorization using Supabase.
- How to integrate Stream Video in a Stream Chat implementation.

To run this code, you need to have an active [Stream](https://getstream.io/chat/trial/) and [Supabase](https://database.new) account.

<!-- ## ✍️ Technical Content -->

<!-- If you're interested in the overall architecture, each layer, and Compose themes that are used in this project, check out **[Fullstack WhatsApp clone using Next.js and Vercel](https://getstream.io/blog/fullstack-whatsapp-clone-using-nextjs-and-vercel/)**. -->

## How to use

1. Create a [new Supabase project](https://database.new)
1. Sign up for a [Stream trial account](https://getstream.io/chat/trial/)
1. Rename `.env.local.example` to `.env.local`
1. Update the values for `NEXT_PUBLIC_SUPABASE_URL` and `NEXT_PUBLIC_SUPABASE_ANON_KEY` from [your Supabase project's API settings](https://app.supabase.com/project/_/settings/api)
1. Update the values for `NEXT_PUBLIC_REACT_APP_STREAM_KEY` and `REACT_APP_STREAM_SECRET` from [your Stream project's dashboard](https://dashboard.getstream.io/)
1. Run `npm run dev` to start the local development server

### Deploy your own instance

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FGetStream%2Ffullstack-nextjs-whatsapp-clone&env=NEXT_PUBLIC_SUPABASE_URL,NEXT_PUBLIC_SUPABASE_ANON_KEY,NEXT_PUBLIC_REACT_APP_STREAM_KEY,REACT_APP_STREAM_SECRET&envDescription=This%20project%20requires%20credentials%20for%20Supabase's%20and%20Stream's%20APIs.&envLink=https%3A%2F%2Fgithub.com%2FGetStream%2Ffullstack-nextjs-whatsapp-clone)

Make sure you have the Supabase and Stream credentials available when you want to deploy to Vercel. The deployment will ask for these environment values:

- `NEXT_PUBLIC_SUPABASE_URL`
- `NEXT_PUBLIC_SUPABASE_ANON_KEY`
- `NEXT_PUBLIC_REACT_APP_STREAM_KEY`
- `REACT_APP_STREAM_SECRET`

## 🛥 Stream Chat SDK

**Fullstack WhatsApp clone using Next.js and Vercel** is built with **[Stream Chat SDK for React](https://getstream.io/chat/sdk/react?utm_source=Github&utm_medium=Github_Repo_Content_Ad&utm_content=Developer&utm_campaign=Github_Nov2023_Jeroen_WhatsAppReact&utm_term=DevRelOss)** to implement messaging systems. And **[Stream Video SDK for React](https://getstream.io/video/sdk/react/?utm_source=Github&utm_medium=Github_Repo_Content_Ad&utm_content=Developer&utm_campaign=Github_Nov2023_Jeroen_WhatsAppReact&utm_term=DevRelOss)** to implement video calling.
If you’re interested in adding powerful In-App Messaging to your app, check out the **[React Chat Messaging Tutorial](https://getstream.io/chat/react-chat/tutorial/?utm_source=Github&utm_medium=Github_Repo_Content_Ad&utm_content=Developer&utm_campaign=Github_Nov2023_Jeroen_WhatsAppReact&utm_term=DevRelOss)**! And for video, check out the **[React Video Tutorials](https://getstream.io/video/sdk/react/#tutorials?utm_source=Github&utm_medium=Github_Repo_Content_Ad&utm_content=Developer&utm_campaign=Github_Nov2023_Jeroen_WhatsAppReact&utm_term=DevRelOss)**!

## Related Information

- [Stream Chat SDK](https://getstream.io/chat/sdk/react/)
- [Stream Video SDK](https://getstream.io/video/sdk/react/)
- [Supabase Auth and the Next.js App Router](https://github.com/supabase/supabase/tree/master/examples/auth/nextjs)
- [Next.js Auth Helpers Docs](https://supabase.com/docs/guides/auth/auth-helpers/nextjs)

## 🤝 Contribution

Anyone can contribute and improve this project following the [Contributing Guideline](https://github.com/GetStream/fullstack-nextjs-whatsapp-clone/stargazers/blob/main/CONTRIBUTING.md).

## Find this repository useful? 💙

Support it by joining **[stargazers](https://github.com/GetStream/fullstack-nextjs-whatsapp-clone/stargazers)** for this repository. :star: <br>
Also, follow **[maintainers](https://github.com/jeroenleenarts)** on GitHub for our next creations! 🤩

# License

```xml
Copyright 2022 Stream.IO, Inc. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
