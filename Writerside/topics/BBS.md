# BBS

We run a bulletin board system with a built-in mail system and channel directory! 

<warning>
- Don't share sensitive or private information.<br></br>
- No spam, harassment, or other unwanted behavior.<br></br>
- Moderators may delete posts if needed.<br></br>
- If a post is inappropriate or if you have any issues with the system itself, please let me know.
</warning>

## Topics
<tabs>
<tab title="General">
Post general stuff here.
</tab>
<tab title="Info">

</tab>
<tab title="News">
Have any important news to share? Post it here!
</tab>
<tab title="Urgent">
Reserved for emergency situations. 
</tab>
</tabs>

## How to
Just send a message over to KYBB! From there you should get a message with the command tree.
Once in the command tree, you can use the commands key code (surrounded in brackets) to execute the command.


### Command Tree
```mermaid
graph LR
	A[Root]
	A -- Q --> B[Quick Commands]
        B -- SM --> E[Send mail]
        B -- CM --> F[Check mail]
        B -- PB --> G[Post Bulletin]
        B -- CB --> H[Check Bulletin]
	A -- B --> C[BBS]
        C -- M --> I[Mail]
            I -- R --> L[Read]
            I -- S --> M[Send]
        C -- B --> J[Bulletins]
            J -- G --> N[General]
            J -- I --> O[Info]
            J -- J --> P[News]
            J -- K --> Q[Urgent]
        C -- C --> K[Channel Directory]
	        K -- V --> Z[View]
	        K -- P --> AA[Post]
	A -- U --> D[Utilities]
	    D -- S --> BB[Stats]
	        BB -- N --> DD[Nodes]
	        BB -- H --> EE[Hardware]
	        BB -- R --> FF[Roles]
	    D -- F --> CC[Fortune]
```

## Contact
- Discord: firewire_
- Mesh: FWM or FWMQ