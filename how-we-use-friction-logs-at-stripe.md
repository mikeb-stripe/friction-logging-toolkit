# How we use friction logs to improve products at Stripe

**Authored by** [Mike Bifulco](https://twitter.com/irreverentmike) and [Charlie Gerard](https://twitter.com/devdevcharlie).

_This article was originally published on [dev.to](https://dev.to/stripe/how-we-use-friction-logs-to-improve-products-at-stripe-i6p)._

Friction logging is a practice that can be used by engineering teams building products to track and improve upon issues that users experience while using a product. The goal of friction logging is to make a given product better for everyone involved. End users and developers get a product that delivers value more directly, the team building the product gets a more attached, happier user base, and salespeople have an easier time showing value to potential customers.

At [Stripe](https://stripe.com), we use Friction logs to share feedback with product teams about the products we build. This is at least part of the mission of our DevRel team. Our goal is to be the voice for devs who use Stripe’s products to build their own. We often serve as the liaisons between these worlds: the devs using our products, and the engineering teams building them.

Stripe also encourages all employees to actively participate in giving feedback. During onboarding, every new Stripe is given training on how to give feedback on products, and the process for creating friction logs.

## Parts of a friction log

![Screenshot including the redacted first page of a 3 friction log documents](/images/image-1.jpg)

### Context

The context describes the persona of the person reviewing the feature, as well as what they were trying to accomplish. For example, if you are reviewing a new API endpoint and this is your first time using the feature, it is important to mention this as part of your persona. You can try to write the context by answering the following questions:

- How experienced are you with the feature?
- What were you trying to build?
- Which parts of the feature is this friction log about?

Below is an example of context for a friction log about setting up a new printer:

![Screenshot of the context section](/images/image-2.png)

### Pros and cons

Once you’ve written the context, you can move on to summarizing the pros and cons you’ve experienced.

This part should be a list of bullet points clearly stating the parts of the feature or experience that you enjoyed or thought were useful, and the ones that you think could be better or did not match your expectation of how the feature should work.

![Include sections for Pros and Cons near the top of your friction log](/images/image-3.png)

### Detailed stream of consciousness

Finally, the detailed stream of consciousness is the part where you should be giving feedback without necessarily following a specific structure. You should write it as you are going through your experience trying to use the feature. It can include anything you think could be useful to the team, no matter how small. Feel free to add screenshots, GIFs showing your interaction with the tool, links, etc.

We are all different in how we use tools, our level of knowledge and expertise, the applications we’re trying to build, so any piece of feedback is valuable to help improve a product.

To give you an idea, here’s an example of how this part of the friction log might look:

![Screenshot of Stream of Consciousness section](/images/image-4.jpg)

## Framework for a great Friction log

### Share size (S/M/L) up front

**Small** - The friction log is small and manageable. It can be completed in a reasonable amount of time without feeling like a burden.

**Medium** - The friction log is of a moderate size. It may take some time to read, but it is not excessively long.

**Large** - The friction log is large and may take some time to consume. These likely capture larger user journeys, and show a holistic view of a process, as opposed to a small bit of confusion with a single feature.

### Make the journey clear

The friction log should make it clear what journey the user is taking, and what steps they are taking along the way, as well as context on their persona ("I'm brand new to collecting payments on the web", or "This is the 3rd major release of my product, but we need to add support for taking payments in Canada"). Additionally, The log should be easy to follow so that the intended audience can understand it -- whenever possible, use language that your product teams and stakeholders will understand without having to go do research of their own.

### Highlight both joy & frustration

While it is critical to share opportunities for improvement in a product, it is also extremely valuable to share what is going well. This helps to build trust with your engineering team, and can be a good reminder that you all share the same goal: making the product as good as it possibly can be.

### Be illustrative

Wherever it may be helpful, provide screenshots, videos, or other visuals to help explain the process you’ve undertaken, and the real experiences you’ve had. This may take the form of a link to a developer screencast for longer friction logs.

### Describe issues objectively

This is where emotional intelligence is critical. Avoid using emotionally loaded language, and instead describe the issues objectively. Something like "I got confused between steps 6 and 7, and went back to this docs page to look for what I missed" is far more helpful than "I wasted 2 hours on this, it's so bad!".

### Share your feedback broadly

At Stripe, when a friction log is completed, it is shared to an email list that includes the entire company, as well as with the specific team working on the feature or product being highlighted. This takes advantage of the network effect: when everyone can see your feedback, it’s more likely that you'll start a conversation with a broad audience of affected parties.

You may find that there are people who actively disagree with your perspective - don't fret, this is usually a good thing! Exposing your friction log to people with a diversity of experience and background means that any suggested changes to your product will be more considerate of a larger userbase.

### Follow-up!

It's also good practice to follow up directly with people who may be tasked with coming up with fixes related to your friction log. Keeping an open dialog is important - it helps ensure that feedback is given and received in good faith, and that the outcome of your work is a meaningful solution (even if it isn't implemented right away).

**This is where the magic happens.** All your work in crafting a great friction log is worthless if you don’t follow through and make sure that it has an impact on the product your company is building. Making sure that your log results in the creation of new feature requests and bugs is a good starting point - do your best to be a steward for these tickets after their creation, so that they are prioritized thoughtfully in your team’s backlog.

The last bit of follow up comes after the implementation and release of updates to the product: tell the world! Update docs and release notes with the new changes, and follow up directly with affected users wherever possible. This is your opportunity to show them that your team is working hard to make things better for them. Let them know that you built something because of them, and that you’re always open to more feedback. This creates attachment and loyalty, and is the virtuous cycle that great product teams strive for.

## On giving feedback

A friction log is essentially a detailed piece of feedback, so to ensure that it is helpful and received well, there are a few important points you need to keep in mind.

### Emotional intelligence is important

Emotional intelligence encompasses self-awareness, social awareness, empathy and relationship management. Writing a friction log focuses on your personal experience with a feature or product, however, you have to keep in mind that it will be read by people who have put a lot of time and effort into building what you are using.

Try to put yourself in their shoes and avoid using language that isn’t very considerate. For example, instead of saying something like “This is by far the worst API I’ve ever used”, which is not only rude but also unhelpful, you could change it to “I’ve struggled using this API because X, Y, Z”. This way, your feedback changes from a general comment to one more focused on your personal experience, and it is more helpful to explain what you struggled with so the team can take action to make improvements. Additionally, try not to use the pronoun “you” to address your feedback. Instead of saying “the API endpoint you implemented isn’t clear”, you could say “This API endpoint was a bit unclear to me”. This focuses your comments on the feature itself, instead of whoever implemented it.

### Trust is a critical ingredient

When giving any kind of feedback, trust is very important. In general, your teammates want you to do well and you should have a common goal of making the experience better for your users so, when receiving feedback, you should know it comes from a place of care. However, if your company doesn’t have a great collaboration culture or if you only recently joined, it can be difficult to have this sense of trust. Before you try to implement friction logs as part of your process, make sure that you get to know your team members. If necessary, schedule calls to go through your friction logs with people so they can understand the state of mind you were in when you wrote your feedback.

### Giving feedback is hard; receiving it is even harder

A bit earlier in this post, I talked about emotional intelligence and how you should put yourself in other people’s shoes when writing your friction log. This can be a difficult process when the feedback you need to give is not the most positive. However, remember that receiving feedback is even harder. If you’re on the receiving side, try to detach yourself from what you are reading and remember that this is an opportunity to improve. If this is not something you are used to doing, it can be a bit difficult at first and might take a few tries to get comfortable with. Hopefully, the more you do it, the more you’ll realize how beneficial it is, not only on a personal level but for all your users.

### Summary

If you're not already using friction logging as part of your product development process, you should definitely consider adopting it. Here's why:

- It can help you identify opportunities for improvement in your product, by highlighting bottlenecks and weaknesses.
  Showing that you listen to users and actively make changes to your product based on their feedback builds user trust and loyalty
- Friction Logging can help to build a culture of trust and feedback, and incentivize emotional intelligence in communication between your colleagues
- In the long run, friction logging can help you save time and money by ensuring that your product is constantly improving.
  Get our friction logging templates
- We’ve created a [friction logging toolkit](https://github.com/mikeb-stripe/friction-logging-toolkit) for you to use if you’re interested in getting started with Friction Logging at your company
- You may also want to check out [frictionlog.com](https://frictionlog.com) - they provide lots of great articles, examples, and resources on Friction logging.

## About the authors

<center>

![Charlie Gerard headshot](/images/charlie-headshot.png)

</center>

[Charlie Gerard](https://twitter.com/@devdevcharlie) is a Developer Advocate at Stripe, a [creative technologist](https://charliegerard.dev/) and [Google Developer Expert](https://developers.google.com/community/experts). She loves researching and [experimenting with technologies](https://charliegerard.dev/). When she's not coding, she enjoys spending time outdoors, trying new beers and reading.

<center>

[![Mike Bifulco headshot](/images/mike-headshot.png)](https://twitter.com/irreverentmike)

</center>

[Mike Bifulco](https://mikebifulco.com) ([@irreverentmike](https://twitter.com/irreverentmike) on twitter) is a Developer Advocate at Stripe. He's also a serial entrepreneur, host of the [APIs You Won't Hate podcast](https://apisyouwonthate.com/podcast), and an espresso fanatic. Mike writes about product design and building with React on his own site, [mikebifulco.com](https://mikebifulco.com).
