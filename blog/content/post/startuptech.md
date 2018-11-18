---
title: "Tech stack for your new startups"
date: 2018-11-18
draft: false
---

You've got a great idea for your startup, and a great team, but how do you get started with Azure to build this solution? So you go to the Azure portal or have a look at the list of the [Azure services](https://azure.microsoft.com/en-gb/services/) and there's a *lot* of services there. Azure can solve all the world's problems but you just want to get started so what to do?

First thing I'd say is to keep it as simple as possible. A good developer is a lazy developer. There's no need to reinvent things that have been solved by others, when you can focus on building out your good idea instead. Friends don't let friends build servers.

So if you're not building servers, where do you start? I'd recommend going with what's called a serverless approach. I could go into a fair bit more depth but it's explained well over [here](https://azure.microsoft.com/en-gb/solutions/serverless/) with lots of pretty pictures (and who doesn't like pretty pictures?). In particular I'd recommend starting with [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/). The way that I look at code is that it's nearly always responding to something - whether it's a user uploading a file, a regular time interval, an update to a data record etc. All you want to do is then write the code needed to respond to that event, and that's what serverless code allows you to do. Don't worry that you have to learn a new language - you can still go and use the ones you love - it's a different approach, not a different language.

Now that you know about Azure Functions you're going to want somewhere to store your data but isn't building a database a pain? Just like I told you not to build servers, don't go and build your own databases either. So Azure has an offering called [Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction) that does a lot of cool things. Of course it allows global reads in many regions, but it also allows global writes in many regions at the same time which is kind of cool when your startup is aiming for world domination. You also don't have to abandon your existing knowledge or code as it's SQL, MongoDB, Apache Cassandra and Gremlin compatible amongst others.

Of course you can link Functions and Cosmos DB together - here's a [quick quide](https://docs.microsoft.com/en-gb/azure/azure-functions/functions-bindings-cosmosdb-v2) using the SQL API to get you started.

Now I'm presuming that you're wanting to use a bit of AI in your application as it adds value to your ~~share price~~ application but you've also heard how hard it can be. You might even be a bit like me and started on some of [Andew Ng's great courses](https://www.coursera.org/instructor/andrewng) and never quite finished them. Never fear - Microsoft believes in democratising AI so we've made it easy for you. Go over to [Azure Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/) and you'll see lots of prebuilt services that you can add to your application in minutes - whether it's to understand intent or recognising objects you'll find something that really helps your startup.

## Next steps

So now that you've got a high level understanding of the technology how do you learn in more detail? [Microsoft Learn](https://microsoft.com/learn) is a great place to start - it's a new training site that Microsoft has built that allows you to learn while actually using Azure without having to pay a penny. What's more you can get cool badges, and who doesn't want that? Microsoft Learn is built on top of http://docs.microsoft.com where you can also see many code examples, and even contribute back to the documentation as it's all hosted on GitHub!

Now I know startups don't always have a lot of money - so not only is training free but you can also start with Azure for free at https://azure.com/free/.

## And a little bit more

Once you've got the basics working, what next? There's a few things that you might want to learn about to help you:

- [Monitor Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-monitoring) - so you can check performance, errors etc
- [Azure Advisor](https://docs.microsoft.com/en-us/azure/advisor/advisor-overview) - this will give you a few tips, including how to save money
- [Security Center](https://docs.microsoft.com/en-us/azure/security-center/security-center-intro) - you're a great coder I know, but never hurts to check you've set things up properly

And here's a few more as you grow your startup:

- [Containers](https://azure.microsoft.com/en-us/overview/containers/) - whether it's Kubernetes or needing a container registry there are plenty of options
- [Azure Data Lake](https://azure.microsoft.com/en-us/blog/a-closer-look-at-azure-data-lake-storage-gen2/) - now with Azure your object storage and big data processing can all be in the same place
- [Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/) - like I said earlier, who wants to run servers when you can have hosted environments?
- [Azure DevOps](https://azure.microsoft.com/en-us/solutions/devops/) - you don't want to be doing everything by hand do you?

Now go out and then build something great!
