ISPollute - Inject fake web traffic into your normal browsing stream to pollute the data collected about you by ISPs.

The United States Congress, in its infinite shortsighted-ness, has tacitly approved of the huge privacy violations in which ISPs engage by forcily collecting data on users' browsing habits.

Fuck ISPs.

This data is then sliced, diced, partitioned, cubed, k-means tested, and otherwise analyzed, before being sold to anyone with a few bucks. This is further compounded by the Third-Party Doctrine, which means users have NO 4th Amendment protection over that data.

Fuck that.

The value in this data stems from the fact that it's considered an accurate representation of a user's interests, employment, relationships, etc. Well, there's a saying in data science - "Garbage in, garbage out". This means that if enough inaccurate data is analyzed accurately, it will still produce inaccurate results. By sending garbage through an ISP's pipe, the "garbage" will propagate into the resultant data. At a minimum, the garbage will require sophisticated (read: expensive) new technologies to filter through.

Unfuck privacy.

Thus, the concept of this tool is to generate fake, but realistic, web traffic over a user's ISP pipe to send garbage into ISP data streams. If the volume of worthless data is great enough, and use of the tool becomes widespread and publicly known, ISPs will not have a product to sell.


Desired Characteristics:
- Usable by non-technical users (facilitate widespread adoption!)
- Locally autonomous - generates no communication(s) which indicate to an ISP that a user has deployed the tool
- Multiple & adaptable form factors - linux/mac/windoze service; rasppi build, usb stick, etc.
- Capable of modeling a wide variety of modern internet traffic - browsing, streaming, chatting, torrenting, etc.
- Persona-based - make ISP connection appear to be used by one or more users matching certain profiles (parent, teenager, cat lady, etc.)
- Non-associative & random - traffic is plausably comparable to real traffic such that neither appears anomalous
- Perfect is the enemy of the good - goal is to make data stream into garbage through volume, not provably random


Design Considerations:
- Generating which types of traffic
- Creating traffic profiles
- Bot framework
- ISP usage caps
- Traffic leakage
- Malleability of websites
- Deployment

