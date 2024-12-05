# re:Invent24

My first experience in Las Vegas for the cornerstone AWS conference has been a realized dream after being deferred for a few years. Documenting all I can and using this as my notepad to take back all the stuff I learn and get into.
## Pre re:Invent24 Thoughts
### Operational Datalake and analytics platform

I've had my share of conversations about different tooling that are supposed to make observability in the cloud easier and more seamless for a multi-cloud organization. I've been in conversations on things from CNAPPs in cyber to Service Now with Ops. Both really good tools for different audiences, but what I can never really wrap my head around is: if both of those platforms are reading the same APIs I already have access to, why couldn't I create something myself?

I understand O&M is a crunch but, per usual, I'm always thinking what would I pursue if I knew I couldn't fail?

I'd pursue a multi-cloud observability platform that provides operational data in an easy to query, standardized format that aligns with the way things should be done at Duke. I know there's a balance between how we are different as a Utility, but also wanting to stay in touch with what the rest of the industry is doing, but I cant shake the feeling that I'd really love to build something that we can maintain in house and not pay someone else to use what they build and they keep going up on their pricing each renewal.

I'm not director, but I've sat and listened to them a bit about the things they care about…and contract renewals are a real pain. What if we could exchange that pain point with simply maintaining and upkeeping applications similar to the ones we already develop in house. What if we could leverage this incredible data source we already have access to m, but limit the amount of third party access we grant our vendors, because “oh we've got that covered”. 

One of the challenges and push back I've heard on building it ourselves is “well we don't have all of the requirements” i say that we do. We know exactly what we need to create. Whether that's attestation documentation as we put NERC data in the cloud, visibility into overly permissive policies that could introduce additional risk to a high priority application, or understand when the spikes are in data transfer over the express routes/direct connects, ect. All of that data doesn't have to be filtered through multiple tools to get the desired outcome. I'm also not one to say all vendors are unnecessary, because I understand an idea like mine would take some time to see come to light. But none the less I spent my entire time in Vegas exploring how to build something like what I'm looking for on AWS. That gave me a blueprint on how to adapt the same strategies to other CSPs.

### Upgrading the SCP
Before the re:Invent sessions started there were a few announcements on the use of RCPs that allow you to granularly control resource permissions and policies at scale. This along with declarative policies should be helpful in our endeavor to re-write the SCP with shorter character limits.


## Day 1
- [COP 202](day1/COP202-INT.md)
- [COP 404](day1/COP404-SC1.md)
- [SEC 326](day1/SEC326.md)

## Day 2
- [COP 315](day2/COP315.md)
- [COP 326](day2/COP326.md)
- [Datadog Breakfast](day2/DataDogBreakfast.md)
- [Hashi Whiteboard](day2/HashiBreakfast.md)
- [ObservabilityBooth](day2/ObservabilityBooth.md)

## Day 3
- [STG 323](day3/STG323.md)
- [SUP 401](day3/SUP401.md)
- [SUP 402](day3/SUP402-R.md)

## Day 4


