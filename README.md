# Arrr! Next.js on Netlify Platform Starter

[Live Demo](https://nextjs-platform-starter.netlify.app/) — Set yer sails an' witness this fine vessel in action!

A scurvy but modern starter forged with Next.js 14 (App Router), Tailwind, and the mighty [Netlify Core Primitives](https://docs.netlify.com/core/overview/#develop) fer Edge Functions, Image CDN, 'n Blob Store.

In these waters, Netlify Core Primitives be workin' both behind the scenes (fer Route Handlers, image lootin' via `next/image`, 'n more) and afore yer very eyes in yer own code.

Implicit usage means ye just hoist the sails usin' any Next.js feature an' all the riggin' be handled fer ye. Explicit usage be framework-agnostic an' often more bountiful than what Next.js alone provides.

## Deployin' to Netlify

This here site be needin' [Netlify Next Runtime v5](https://docs.netlify.com/frameworks/next-js/overview/) fer full sails an' riggin'. If ye ain't aboard v5 yet, ye'll be prompted t' climb the riggin' when ye first land on the Site Overview deck.

[![Deploy t' Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/netlify-templates/next-platform-starter)

## Developin' Locally, Ye Landlubber

1. Clone this treasure map o' a repo, then run `npm install` in its root hold.

2. To sail smoothly with edge functions an' blob loot locally, make sure ye got the latest Netlify CLI. Run:

   ```bash
   npm install netlify-cli@latest -g
   ```

3. Link yer local repo t' yer deployed Netlify site, so ye use the same runtime on both the high seas an' port:

   ```bash
   netlify link
   ```

4. Then fire up the development galley with Netlify CLI:

   ```bash
   netlify dev
   ```

If yer browser don't hoist yer site automatically, point it t' [localhost:8888](http://localhost:8888) an' let 'er rip.
