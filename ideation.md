@authors Matthew Herbst, Arielle Vanlderstine, Nick Poelma, Mike Shi, Rodrigo Argumedo, Vishnu Ravi, Victor Lourng

1. Actions:
	1. Website
		1. Register
		2. Login
		3. RSS feeds off the site?
		4. View user profiles
	2. User profile
		1. Customize profile
		2. Connect social media accounts
		3. Feed of git commits and/or tweets
		4. Delete user profile =(
			1. And all associated history?
			2. (Matt Herbst): Not content, though we can obfuscate public data such as names on posts
				* Might need to retain this internally for legal reasons?
		* (And because you should never delete anything - makes looking stuff up later easier then tracking someone down)
	3. Find Hackers Around You
	4. Create Events
		1. Hackathons
			1. Organize and promote hackathons
			2. Say you’re “going” to hackathons
			3. Also hackdays, etc.
		2. Meetups
			1. Browse by location or by content (language, technology used)
			2. Online meetups? Google+
	5. Post content
		1. Create new epics/sub-forums/whatever we call it
			* Create new topics within/associated to these
		2. Pin/Star/Mark Important posts for future use
			* For resources like good Medium posts on how to organize a hackathon, for example
	6. Information Feed
		1. Searchable
			1. Tags/filters
				* Use AI to make more relevant searches so it isn't plainsearch bringing up content with the exact tag?
			2. Be able to toggle algorithmic filtering for your feed?
	7. Message other Users
	8. Follow Users
		* Their posts are automatically put into feed
2. Requirements
	1. Site
		1. Restrictions on viewing site content if not logged in?
			* What content?
				* Full Names?
				* Links to other sites? (IE Stalking to Facebook or w/e)
	2. User profile
		1. Real identification (Facebook, LinkedIn, Google+)
		2. Do we have an age restriction?
			* 13 is min age to avoid COPPA
	3. Posting content
		1. Real name will be shown with post
		2. Integrate external content into posts? (IE Facebook previews when you post a link?)
			1. HH specific integrations (Can it be implemented with Socket.io?)
				* GitHub, SO, ChallengePost, etc.
			2. Blogging
				* Medium, WP, LiveJournal, Blogger, Tumblr
			3. How to handle content from unrecognized service?
				* MEETTTAAAA tags
		3. Integrate internal content into posts?
			* GIFs EVERYWHERE
3. Features
	1. Site
		1. Settings
		2. Information Feed
			1. Searchable
				1. Tags/filters
				2. Machine Learning
					* Use AI to make more relevant searches so it isn't plainsearch bringing up content with the exact tag?
				3. By categories/sub-things
		3. Styles of viewing content and posting
			1. Tweet style - on front page
			2. Blog style - on profile page
			3. Forum Style - on non-front pages
	2. User Profile
		1. OAuth and Other Social Logins
			* ID
			* Real Name
			* Email
			* Other known names?
		2. Contact info
			* hackthons.com email?
			* Messaging services (Facebook, Skype, IRC, Instagram, Viber, Wechat, Snapchat, Kik, Yo, Xfire, MSN, Myspace, AIM, Yahoo Messenger)
		3. Message inbox
		4. Profile Comments
			* Leaving a quick message
		5. Profile Picture
		6. School(s), Job(s) (company pages?) #tagyourtags
			* Can be pulled from LinkedIn/Fb if available
		7. `is_admin?`
			* Can ##
			* hascheezburger
		8. Settings
			1. Privacy
				* Toggle showing identifying information to non-logged in (public) users
				* Ability to block/unblock a user
				  * What does this mean? Is content blocked, user profile viewing, etc...
				* Create lists (i.e. friends, acquaintances, etc.)
				* 2-step auth to prevent unauthorized access to the account?
			1. Social Media
				* Manage social media account logins
				  * What information is shared to hackthons.com (this is available via those accounts, but we can pro-actively show the user what we have access to)
