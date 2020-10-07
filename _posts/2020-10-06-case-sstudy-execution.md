---
layout: post
title: Case Study - Execution
excerpt: "Just about everything you'll need to style in the theme: headings, paragraphs, blockquotes, tables, code blocks, and more."
modified: 2020-09-23
tags: [study,notes]
comments: true
pinned: true

---
# <font color=A6AFBE>How would you find the cause of a 15% drop in Facebook Groups usage?
## <font color=EAC493>Answer Structure
1.**Clarify**. 
Ask for clarification if you are unclear about what the interviewer is asking.
2.**List high-level reasons**. 
Start by listing the high-level reasons, components, or user behaviors that are causing the problem.
3.**Gather context information**. 
Ask questions to understand the context of the problem. For example, is the problem regional? Is the problem a one-time event or progressive?
4.**Discard issues outside of scope**. 
If the answers to questions about context are outside the scope of Facebook Groups features, discard them.
5.**Establish a theory of probable cause**. 
For each of the high-level reasons, components or behaviors you mentioned, recursively ask yourself why are these problems occurring, and list possible causes.
6.**Explain how to test your theory and fix the problem**. 
Describe how you would test each probable cause. If possible, explain how you would resolve the problem.

## <font color=EAC493>Answer Example
##### <font color=99CCFF> Clarify
INTERVIEWEE: By usage, do you mean the creation of groups or user engagement or both?

INTERVIEWER: Strictly engagement.

INTERVIEWEE: Okay, how do you measure engagement? Is it by the number of posts created, the number of replies to posts, the number of reactions to posts, or the number of shared posts?

INTERVIEWER: All of those things. The total count of all those activities, or total engagement for Facebook Groups, has declined by 15%.

##### <font color=99CCFF> List High-level Reasons
INTERVIEWEE: Okay, at a very high-level the decline in engagement is due to:

1.Users creating, replying, reacting, and sharing fewer posts on Facebook Groups, and/or

2.Users going to an alternative feature.

To start diagnosing the cause of these behaviors, I would begin by asking the following questions to understand the context in which the decline in engagement was detected.

##### <font color=99CCFF> Gather Context Information
**TIME: Is the decline in engagement a one-time event or has it happened progressively?**
<br>If it is a one-time thing, then it is possible a technology glitch caused the problem, such as a downtime in the services that support Facebook Groups. Therefore, I would ask if there were technical problems that coincided. If the decline in engagement is progressive, then the cause is still there, and we can dig deeper into data, which I will go through later.

**REGION: Is the decline happening in an isolated region? **
<br>If this is true, the problem might be related to a country’s regulations or a competitive product in that region. For example, if there is a new competitive social-group product that is more suited to the social mores of the region than Facebook, I would do some ethnographic studies on that population to understand their needs better; and I would consider developing features for those needs.

**PLATFORMS: Is the decline happening on specific platforms, like iOS, Android or others?** 
<br>If so, I would compare the drop of Facebook Groups engagement on each platform with engagement across all platforms. As long as the overall engagement metric is steady, I would not worry much about the decline of engagement on a particular platform. Users could be, for example, switching mobile platforms and still using Facebook Groups.

**OTHER FEATURES: Is the decline in engagement happening in other Facebook features besides Facebook Groups?**
<br>If so, then there is a much bigger problem, and we would need to look at the overall engagement of the entire platform.

**COMPETITORS: Is the decline in engagement also happening in competitive products?** 
<br>This data is difficult to come by, but if this were true, then the cause is also affecting other companies. For example, the decline in engagement could be a PR problem with privacy perceptions about social networks. This kind of problem would be out of scope for a product team and best handled by a corporate management team.
##### <font color=99CCFF>Establish a Theory of Probable Cause
To continue with a more in-depth analysis, let’s assume that the engagement is progressive, and none of the other situations are happening. Meaning, the problem is not regional, not platform-specific, and no additional Facebook feature or competitor is exhibiting the same decline in engagement. I would continue diagnosing what could cause users to behave in the two ways I described:
<br>1.Creating, replying, reacting, and sharing fewer posts,
<br>2.And, going to an alternative social-group feature.
##### <font color=99CCFF> Test Your Theories and Fix the Problem
Concerning creating, replying, reacting, and sharing fewer posts, I would ask the following questions:

Is there a problem with the creation of posts? Maybe posts are created but not displayed on group members’ feeds. If this were the case, it could explain why users are not engaging. However, I think a decline in engagement would have been drastic and not progressive. So, the probability of this being the cause of a progressive decline in engagement is small.
Are the notifications of new group posts working correctly? Perhaps group members are not engaged because they are not getting notifications about new posts. Like the previous case, I think this malfunction would cause a drastic decline, not a progressive one. So the probability of this being the cause is small.
Is there a problem with the UI for replying, reacting or sharing of posts on Facebook Group pages? If this were the case, I think users and the Q&A team would notice right away, and fix it. So, I do not believe this would be the cause of a progressive decline in engagement.
Has there been an increase in spam posts on Facebook Groups? Spam could cause users to leave groups, and be a possible cause of a progressive decline in engagement. I would investigate this further and ask my engineering team to check whether there are signs of cyber attacks and find ways to increase protection against those attacks.
In relation to users going to an alternative social-group feature, I would ask the following questions:

Is there a new Facebook feature that is cannibalizing Facebook Groups? If there is a new feature similar to Facebook Groups, then I would look for two things: 1) What is the proportion of users of the new feature that are also users of Facebook Groups? And, 2) What is the percentage of users that switched that have exhibited a significant decline in engagement with Facebook Groups since the problem started? Answers to these questions would determine if there has been an exodus of active Facebook Group users to the new feature. If this were the case, it does not mean bad news. It is possible that the new feature brings more revenue to Facebook and adds more value to users. So, I would get together with all stakeholders to assess whether it makes sense to keep Facebook Groups.
Is there a competitor of Facebook Groups that has increased its engagement numbers while Facebook Groups’ engagement decreased? I would imagine this internal data is challenging to get, but if it became public knowledge, I would find out what the competitor did differently. Then I would implement these new ideas on a test drive with a controlled group of users. If the new features increased engagement, I would implement them.
In summary, my approach to finding the cause of lower user engagement of Facebook groups is as follows: I started by understanding the context so that I could discard issues related to regions, specific platforms, side effects of other Facebook features, and marketing problems. Then, I dug deeper to identify what could affect user behavior to stop them from engaging. Of the six possible causes, I think the most plausible ones are: an increase in spam posts, cannibalization by another Facebook feature, and an external new competitive feature. I would test each of these probable causes to identify the exact source and then fix it.