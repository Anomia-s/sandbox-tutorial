 <meta name="twitter:image:src" content="https://repository-images.githubusercontent.com/307118850/926c7980-16e0-11eb-853b-4701d7259e4d" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary_large_image" /><meta name="twitter:title" content="TENEIDAE/Roblox-Clone-Tutorial" /><meta name="twitter:description" content="LEARN TO MAKE A LEGO SITE! Contribute to TENEIDAE/Roblox-Clone-Tutorial development by creating an account on GitHub." />
    <meta property="og:image" content="https://repository-images.githubusercontent.com/307118850/926c7980-16e0-11eb-853b-4701d7259e4d" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="TENEIDAE/Roblox-Clone-Tutorial" /><meta property="og:url" content="https://github.com/TENEIDAE/Roblox-Clone-Tutorial" /><meta property="og:description" content="LEARN TO MAKE A LEGO SITE! Contribute to TENEIDAE/Roblox-Clone-Tutorial development by creating an account on GitHub." />
# Roblox-Clone-Tutorial
LEARN TO MAKE A LEGO SITE!

![aaaaaaaaaaa](https://media.discordapp.net/attachments/724012957432021062/769947872266420285/Sin_titulo.png?width=1204&height=677)
#### First Step - Organize yourself.

You cant make a roblox clone overnight, actually, roblox clones take quite a good ammount of time. 

Lets start off with a simple test!

Do you know any programming languages that can be used for web development?
[HTML AND CSS DO NOT COUNT]

In case you do are they any of these?

JAVA - PYTHON - PHP - JavaScript - C# - Ruby

(You must know them VERY WELL!)

If so, then you're qualified to start off a roblox clone by yourself or with help. Else you will need LOTS OF HELP.


#### Step 2 - Pricing and Organizing the site.

Here we will talk about PRICING AND SITE PROGRAMMING! First of a slap of reality: ***you cant make a roblox clone without investing atleast 10$***

What will the site run on?
---
The roblox clone must have a language asssigned for the backend, for instance you cant make a roblox clone on scratch or Google sites. No, they dont work.

For the backend any language mentioned before works. In my personal opinion i'd say Javascript, PHP, Python and Ruby are the best options. Making a roblox clone in C# or Java is kinda "Overengineering" the web development. 

**Overengineering**: Overengineering is a programming term used to reference when something is way too complex for a simple task.

An exampel in js:

This code counts days until the other day. It's really simple.
```js
// fn(number,number) -> fn(date) -> number
const daysUntil = (day, month) => daysBetween(now, futureDateFrom(day, month));

const today = new Date(); // side effect
console.log(daysUntil(1, 12)(today));
```
Now here's the overengineered version:

```js
function daysUntil(day, month) {
  const today = new Date();
  const sameYear = new Date(today.getFullYear(), month - 1, day);
  if (sameYear > today)
    return Math.ceil((sameYear - today) / (1000 * 60 * 60 * 24));
  else {
    const nextYear = new Date(today.getFullYear() + 1, month - 1, day);
    return Math.ceil((nextYear - today) / (1000 * 60 * 60 * 24));
  }
}
```

Its really bad.
Site Pricing!
---

You can use some free alternatives to reduce the cost a lot, for instance, sites like freenom offer free domains with extensions such as .tk or .cf, these domain extensions tend to be fishy links and are not recommended, but still, its free.

Now, here's the good thing, a server. You can either choose hosting on a VPS or locally. 

 For a VPS you will need to make a pricing plan comparison depending on what the site will run. 

In case you're too lazy to even do that i made one simple comparison:

https://docs.google.com/spreadsheets/d/1CrQyoBndtiEoLCMArVJodBuI40E6NH5kV_d9ZfdwwMs/edit?ouid=100689913364494900750&usp=sheets_home&ths=true

If you're hosting it yourself, then you just need to lookup a cheap industrial computer. They work very well, they are small and are designed to last long.

![wow](https://media.discordapp.net/attachments/743605655247651006/769938568700755998/unknown.png)

---

#### Step 3 - The team and Site Development.

Alright, you now have both a domain and a server. Now we need the site itself. 

If you know web development in the languages stated before but dont know much in general you should look for a team to help you.

How do i look for a team?

Well, first of all, do not go asking every single person you know. Make a serious project proposal. Making yourself look serious will make you gain better developers.

Test their knowledge too! Make them show to you their projects in the past. Its not the first time i see roblox lua scripters as "Web Developers".

Ask them for their github, if they know what http protocols are, and some bases of web programming in the language you had choosen.

### Step 4 - Social management.

DO NOT PROMOTE THE DISCORD SERVER OR SITE BEFORE MAKING THE SITE.

It's where 90% of roblox clones fail. They release the discord and say "Site soonTM" leading to pressure on site development. And more when the developers are fake.

DO NOT MAKE HATS OR ANY DESING BEFORE THE SITE IS DONE.

Because that's also where the project dies.

MAKE A PRIVATE DEVELOPMENT DISCORD SERVER. **PRIVATE** means no one except the developers should be there. And EVERY SINGLE THING that is done on the site MUST be reported there.

HOST YOUR CODE ON A VERSIONING PLATFORM.

this will make sure all developers have access to the same code.  A versioning platform is Github or Bitbucket as of examples.

### Step 5 - Site release

Alright, here comes another key part. Do not release the site public yet. You need to do testing. Make the site password only and only accesible by beta testers that will have to be actively doing actions on the site. Changing settings. Foruming etc...

After all testing is done, you can release the site to the public.

SOONTM MORE INFORMATION


