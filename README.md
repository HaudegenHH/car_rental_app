# Car rental app

- using: NextJS, Tailwindcss, headless UI, TypeScript, 
- and concepts like: mobile responsiveness, api management
- also using RapidApi / the  api to get detailed information about every specific unique car model 


**create new NextJS project**
- mkdir "car_models" open in vscode
```sh
npx create-next-app@latest ./
```
..which will install the latest version in the current folder

For the following configuration i choose:\
Typescript - yes\
ESLint - no\
Tailwind - yes\
src directory - no\
app router - yes\
customize import alias - no

## RapidApi

- to use this api sign up on rapidapi, search for "Cars by API-Ninjas" - api and subscribe to it
- that allows 3000 request a month!
- look at the optional paramters that you can give to the request, meaning: these are the filtering options
- click the button "Test Endpoint" to see what response is coming back 
(each car has 12 properties, and we are getting 5 cars per page whats just the default limit and can be changed via params)
- copy the code and paste it into utils/index.ts
- addtionally copy the credentials from that code snippet to the .env.local

## Imagin Studio - car image api

https://www.imagin.studio/car-image-api

- sign up for 60 days free trial
- get the customer key and copy/paste into .env.local