
 Fillimisht shkot te ky page: https://ui.shadcn.com/docs

npx create-next-app@latest discord-clone --typescript --tailwind --eslint

Need to install the following packages:
create-next-app@13.4.19
Ok to proceed? (y) y
✔ Would you like to use `src/` directory? … No / Yes
✔ Would you like to use App Router? (recommended) … No / Yes
✔ Would you like to customize the default import alias? … No / Yes
Creating a new Next.js app in /Users/division5/Desktop/discord-clone.

Using npm.

Initializing project with template: app-tw 


Installing dependencies:
- react
- react-dom
- next
- typescript
- @types/react
- @types/node
- @types/react-dom
- tailwindcss
- postcss
- autoprefixer
- eslint
- eslint-config-next



Shko te direktoria e projektit qe krijove:
Cd discord-clone

Me pas bed run komanden:   npx shadcn-ui@latest init


Need to install the following packages:
shadcn-ui@0.3.0
Ok to proceed? (y) y
✔ Would you like to use TypeScript (recommended)? … no / yes
✔ Which style would you like to use? › Default
✔ Which color would you like to use as base color? › Stone
✔ Where is your global CSS file? … app/globals.css
✔ Would you like to use CSS variables for colors? … no / yes
✔ Where is your tailwind.config.js located? … tailwind.config.js
✔ Configure the import alias for components: … @/components
✔ Configure the import alias for utils: … @/lib/utils
✔ Are you using React Server Components? … no / yes
✔ Write configuration to components.json. Proceed? … yes

✔ Writing components.json...
✔ Initializing project...
✔ Installing dependencies...

Success! Project initialization completed.



So the components.json is added.

Now run: ‘npm run dev’ and you application will start  on localhost:3000

Run  npx shadcn-ui@latest add button
 So inside of components folder you have a new folder called ui and button.


Shko me pas te page: https://clerk.com/   per pjesen e autentifikimit te userave:

Ben check email address the google(popular) dhe me pas te gjenerohen keys qe I vendos te file .env qe krijova.


Follow these steps https://clerk.com/docs/quickstarts/nextjs 

We create sign up sign in pages

Next we install :  npm i next-themes   

Then go to doc https://ui.shadcn.com/docs/dark-mode

We did the right installation for dark mode later we installed prima by: 

npm i -D prisma

 npx prisma init

Later I go to https://planetscale.com/

Create discord database with Hobby:


https://www.prisma.io/docs/concepts/components/prisma-schema

https://app.planetscale.com/ildjanamamo123/discord/connect

username: w0fmlcenvevecxb21j39

password: pscale_pw_N4MFbOAJDwDaj8keE9IuUoi2MtcJeJF6Myl9Nm7YqzM


Add the models to  schema.prisma file and then do:

npx prisma generate

And   npx prisma db push
















