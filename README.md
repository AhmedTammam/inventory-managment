# Inventory Management
This project manages the product's inventory.


## Technologies

This is a [T3 Stack](https://create.t3.gg/) project.


- [Next.js](https://nextjs.org)
- [NextAuth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [Chakra UI](https://chakra-ui.com/)
- [tRPC](https://trpc.io)

## How to use?

- npm install

#### Next-auth
- Update ``.env`` file. You can generate the ``NEXTAUTH_SECRET`` via 'openssl rand -base64 32' on Linux
- `` NEXTAUTH_URL ``
for development you can set ``http://localhost:3000``, In production set it to your domain
- ``Provider`` I used `google provider`you need to follow this [link](https://next-auth.js.org/providers/google) to configure your credentials . Also you can use any provider you want from [here](https://next-auth.js.org/providers)
- More info: https://next-auth.js.org/configuration/options#secret








