<div align="center">
    <a href="https://kronos.earth"><h1 align="center">kronos.earth</h1></a>
    
Kronos is currently built with [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/), [Upstash](https://upstash.com), [Contentlayer](https://www.contentlayer.dev/) and deployed to [Vercel](https://vercel.com/).

</div>

<br/>



## Running Locally


```sh-session
git clone https://github.com/kronos-lp/kronos.git
cd kronos
```

Create a dotenv file with these variables
```sh-session
GA_TRACKING_ID=G-NB01X73EJF
NEXT_PUBLIC_BEAM_TOKEN=39d01dd1-4aef-42b0-8bb0-1d231af28f79
UPSTASH_REDIS_REST_TOKEN=AZCgASQgODkxMGFlMjgtNTFhMS00ZTU1LWEwNzAtNzljMWExYjI3OGQ3ODNkMmI4YzhmY2I3NDBjNWI5NmExNTMyMGQ4ZDBiYmQ=
UPSTASH_REDIS_REST_URL="https://learning-shrimp-37024.upstash.io"
```

Then install dependencies and run the development server:
```sh-session
pnpm install
pnpm dev
```

