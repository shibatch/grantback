## VOD Reaction License \- A Community Licensing Model for Streamers

This project provides a template for a custom license designed to facilitate content reuse, particularly "reaction" style content, among streamers on popular video sharing and streaming platforms such as Twitch and YouTube.  

The "VOD Reaction License Version 0.4" is an experimental, custom license that allows content creators (Licensors) to grant specific permissions to their community (Licensees) to reuse designated VODs.  

Key features include:  

* Permission for Reuse: Clearly grants rights to create derivative works (like reaction videos, compilations, reviews) from the Licensor's VODs.  
* Platform Limitation: Reuse by Licensees is restricted to specific platforms designated by the adopting Licensor (the template provides Twitch and YouTube as primary examples).  
* Attribution: Requires Licensees to provide clear attribution to the original Licensor.  
* Grant-Back Clause: Licensees grant back a license to the original Licensor to reuse the new "Derivative Work" created by the Licensee, under mostly symmetrical conditions. This fosters dialogue and allows Licensors to engage with community creations.  
* Community Focused: Aims to encourage interaction, collaboration, and mutual promotion within the streaming community.
* A Different Approach to Problem-Solving: Unlike many FOSS licenses that aim to manage rights in an automatic and unambiguous way, this license model intentionally focuses on encouraging dialogue between creators to resolve issues, reflecting a different philosophy.

This License Template was originally conceived and drafted by [Naoki Shibata](https://github.com/shibatch/). The drafting and refinement process for this template and its accompanying guides involved iterative conceptual exploration and textual assistance from Google's AI model, Gemini. The final structure, terms, and intent of this license model are those of Naoki Shibata.  

### TL;DR: Just Read This Part

* A "license" is a promise of permission that sets the rules for how public content (like videos) can be used. By using this license, a creator clearly declares, "It's okay to make reaction videos," so viewers and other creators know exactly what they can create and what rules they need to follow to avoid issues.

* Simply fill out the license template with your information and link to it from your Twitch "About" panel or YouTube channel description. This turns your VODs into content that everyone can feel safe reacting to.

* Anyone who reuses your videos must do so only on the platforms you specify (e.g., YouTube, Twitch), give you proper credit (attribution), and notify you after they publish their new work.

* If your VOD contains copyrighted material from others (e.g., background music, game footage, art), the person reusing your VOD is responsible for securing the rights to use that third-party content.

* When another creator reuses your video to make their own, they grant you the right to reuse their new video under nearly identical conditions. This is called the "Grant-Back" feature.

* For more detailed rules, specific examples, and help with troubleshooting, please see the full guides.


### Why This License Model?

The creation of this license model was motivated by several observations and goals common in the streaming world:

1. Popularity of Reaction Content: Reaction-style content is a major way streamers engage with each other's material and communities.  
2. Copyright Clarity: Simply reacting to content doesn't automatically grant the necessary rights. This license aims to provide a clear permission pathway.  
3. Supporting Growth: For many streamers (especially those building their audience), having their content reacted to by others can significantly boost visibility and engagement. This license is designed to actively encourage such interactions.  
4. Enabling Dialogue and Response: The grant-back feature ensures that the original Licensor can respond to, feature, or otherwise engage with reactions to their content, which is particularly useful for addressing misleading or bad-faith reactions and fostering a balanced conversation.  
5. Controlled Sharing: The ability to designate specific Permitted Platforms serves two key purposes. First, it allows Licensors to better manage the spread of their content beyond their desired ecosystems. Second, as the rights to stream certain content, such as video games, are often granted by publishers only for specific platforms, this platform restriction is also essential for complying with the original content's licensing terms.
6. Flexibility for Corporate or Agency Guidelines: The license is adaptable to specific reuse guidelines set by a company or agency a licensor may be affiliated with. The license template provides a dedicated section where the licensor can add their own custom rules—such as prohibiting commercial use or restricting use with certain types of content—to align with corporate policies.

For content reuse, creators often have to rely on the concept of "fair use." However, fair use is a legally complex doctrine, and the final determination of whether a particular use qualifies as fair must be made by a court of law. The purpose of this license is to eliminate the need for relying on the uncertainty of fair use. A Licensor's decision to apply this license to certain VODs, or a Licensee's decision to reuse content under its terms, does not affect the legal status of any other content. For videos where the creator has not granted explicit reuse permissions, **you can still attempt to use the video under fair use**.

<details>
<summary>Relationship Between This License Model and the Hosseinzadeh v. Klein Case</summary>
&nbsp;  

To understand the background of this license model, the landmark U.S. copyright case Hosseinzadeh v. Klein (the h3h3Productions case) serves as a helpful reference. In this case, a court ruled that a critical commentary video on YouTube (a "reaction video") did not infringe on the original work's copyright and was protected by the U.S. doctrine of "fair use".

While this ruling was a significant victory for creators of reaction videos, its scope is limited. Judge Katherine B. Forrest, who delivered the judgment, made a clear distinction between critical commentary, like the Kleins' video, and a mere "group watching session without comment," cautioning that not all reaction videos would qualify as fair use. Furthermore, YouTube's own official policy states that the final determination of whether a use is fair is made by a court of law, not the platform.

It is widely believed that simply using a small amount of copyrighted content (e.g., a 10-second clip) or adding comments automatically qualifies as "fair use." However, the principle of fair use is a complex legal concept that depends on four main factors: the purpose and character of the use (transformativeness), the nature of the copyrighted work, the amount and substantiality of the portion used, and the effect of the use upon the potential market for or value of the copyrighted work. Simply "rewatching a VOD with minimal commentary" is generally not considered transformative enough to qualify as fair use. "Unauthorized" use is presumptively an infringement, and relying on fair use is an affirmative defense that may require proof.

This means that creators who rely on "fair use" always face the following uncertainties:

* The ambiguity of whether their video will be legally recognized as "transformative" criticism.
* The fact that the platform will not necessarily protect them from a copyright infringement claim.
* The need to be prepared for a potentially expensive legal battle to ultimately prove fair use in court.

In addition, it is important to note that the concept of fair use itself is fundamentally specific to the U.S. legal system. Legal systems vary significantly from country to country; for example, Canada, the EU, and Japan—which has no general fair use provision—all have different laws. For creators who operate globally, this legal diversity is a source of further uncertainty.

The VOD Reaction License offers a clear solution to these problems.

This license eliminates the need for community creators (Licensees) to guess whether their content qualifies as fair use and to bear the associated legal risks. This is because the license provides explicit, upfront permission from the original creator (Licensor) to create derivative works like reaction videos.

Furthermore, this license features a Grant-Back clause, which is not found in the fair use doctrine. This clause allows the Licensor to reuse the Licensee's derivative work, which encourages a two-way dialogue and activates the entire community, moving beyond one-sided content use.

The VOD Reaction License is designed to overcome the differences in national laws and provide a consistent, collaborative framework that allows creators to produce content with peace of mind.
</details>


<details>
<summary>Comparison with Existing FOSS Licenses</summary>
&nbsp;  

While this license's architecture may seem unusual compared to standard FOSS licenses, it is a logical result of the need to address the following practical constraints:

* Handling of Third-Party Content: With existing licenses like Creative Commons, it is difficult to license VODs that contain third-party content (e.g., in-game music), as they are premised on the licensor holding all necessary rights. This license solves this by allowing for such VODs while making it the licensee's responsibility to clear the rights for any reuse.

* Flexibility for External Obligations: Real-world streaming often requires adherence to external rules, such as agency guidelines. Traditional FOSS licenses with fixed terms cannot accommodate this. This license addresses the issue by allowing the licensor to add custom restrictions (under Clause 3.f), ensuring compliance.

* Guaranteed Grant-Back: The licensor's right to reuse a derivative work (the grant-back) must be guaranteed to foster dialogue. This requires a critical asymmetry in the license terms. While the licensor can add restrictions, the licensee cannot add new restrictions to the grant-back. If a licensee could add their own terms, they could effectively block the licensor's reuse, rendering the grant-back clause meaningless. This asymmetrical structure, where the grant-back conditions (Clause 4) are fixed, is therefore indispensable. It is further strengthened by the licensee's obligation to furnish a copy of their work upon request (the "Provided Copy" as defined in Clause 3.d), and to warrant that this copy is clear for reuse (Clause 4.e.iv), ensuring the licensor can use it reliably.

Thus, the architecture adopted by this license is necessary to satisfy all three of these constraints simultaneously.
</details>

### What's in This Repository?

This repository contains the following key documents:

* [VOD\_REACTION\_LICENSE.md](VOD_REACTION_LICENSE.md): The full text of the "VOD Reaction License Version 0.4" template. This is the core legal document that adopting Licensors will customize.  
* [GUIDE\_FOR\_ADOPTERS.md](GUIDE_FOR_ADOPTERS.md): A guide for streamers who wish to adopt this VOD Reaction License model for their own channel's VODs. It explains how to customize and implement the license template.
* [GUIDE\_FOR\_LICENSEES.md](GUIDE_FOR_LICENSEES.md): A user-friendly guide for viewers and content creators who want to reuse VODs from a streamer who has adopted this license. It explains how to do so under the terms set by that streamer. (Adopting Licensors should adapt this guide for their own community).  

### How to Use This License Model

For Viewers/Creators (Potential Licensees of a Streamer's VODs):

If a streamer indicates that their VODs are available under a "VOD Reaction License," look for a link on their channel (e.g., in their "About" section, video descriptions, or a pinned post) to their specific version of the license text and any accompanying usage guide they provide. Read those carefully to understand the terms they are offering.

For Streamers Wanting to Adopt This License Model for Their Own VODs (Adopting Licensors):

1. Read the [GUIDE\_FOR\_ADOPTERS.md](GUIDE_FOR_ADOPTERS.md) in this repository carefully. This guide provides step-by-step instructions on how to adapt and implement this license model.  
2. Customize the Template: Copy the [VOD\_REACTION\_LICENSE.md](VOD_REACTION_LICENSE.md) template and fill in all the bracketed placeholders \[Placeholder\_Name\] with your specific channel information.  
3. Host Your License: Publish your customized version of the license text on a publicly accessible platform (e.g., your own GitHub repository, a personal website, or a GitHub Gist).  
4. Inform Your Community: Clearly state on your channel(s) that your designated VODs are offered under your instance of the "VOD Reaction License Version 0.4" and provide a direct link to your hosted version of the license.  
5. Provide Guidance: It is highly recommended to also provide a version of the [GUIDE\_FOR\_LICENSEES.md](GUIDE_FOR_LICENSEES.md), customized for your channel, to help your community understand how they can reuse your content.

<details>
<summary>A Note on the Scope of "Licensed Content"</summary>
&nbsp;  

While this license is named the "VOD Reaction License" and its documentation often uses examples from the streaming world, its scope is intentionally much broader. The core term in the license is "Licensed Content," which is defined to comprehensively cover a wide range of digital materials. This includes not only videos and audio (such as podcasts), but also still images (like comics and illustrations), 3D models, and computer programs. For the precise definition, please always refer to the actual license document.

It should be noted that the VOD Reaction License is incompatible with the GNU General Public License (GPL). For instance, if a Licensee displays the source code of GPL-licensed software in their derivative work, that work itself could potentially be considered a derivative of the GPL software, leading to licensing conflicts.
</details>


### Licensing of These Documents

The [VOD\_REACTION\_LICENSE.md](VOD_REACTION_LICENSE.md) text template in this repository is offered with specific permissions for its use as a template:

* You are permitted to copy and distribute verbatim copies of this license document.  
* You are permitted to modify this license document solely by filling in the designated placeholder sections (e.g., \[Licensor's Primary Channel Name\]) with your own information to create your instance of the license.  
* If you modify any of the core legal terms beyond these placeholders, you may not call your modified version the "VOD Reaction License Version 0.4" or any confusingly similar name. Such a modified document would be your own new, distinct license. (Please see Clause 11 of the [VOD\_REACTION\_LICENSE.md](VOD_REACTION_LICENSE.md) template for full details on these permissions).

The accompanying guide documents ([GUIDE\_FOR\_LICENSEES.md](GUIDE_FOR_LICENSEES.md) template and [GUIDE\_FOR\_ADOPTERS.md](GUIDE_FOR_ADOPTERS.md)) in this repository remain licensed under the Creative Commons Attribution-ShareAlike 4.0 International Public License (CC BY-SA 4.0). You are free to share and adapt these guide documents for your own purposes, provided you adhere to the terms of the CC BY-SA 4.0 license.

### A Note on Minors and Legal Capacity

This VOD Reaction License, like any agreement, is subject to applicable laws regarding an individual's legal capacity to be bound by its terms. In the United States, for example, individuals are generally considered minors until they reach the age of 18 (though this can vary by state for specific purposes). Agreements entered into by minors may not be legally binding on them or might be voidable at their option under state law.

If you are a minor considering using VODs under this license, or offering your VODs under this license, it is strongly recommended to involve a parent or legal guardian. Similarly, if you are a Licensor adopting this license for a community that may include minors, or a Licensee interacting with content from a minor Licensor, awareness of these legal principles is important. Minors should typically seek consent and guidance from a parent or legal guardian before agreeing to terms that have legal implications.

### A Note on Trust and Licensor Good Faith

This license model is designed to provide legal clarity and encourage creative exchange based on a foundation of mutual trust. It provides a clear framework for resolving disputes, but like any agreement, its effectiveness is highest when both parties act in good faith.

While the license is structured to be fair, it cannot completely protect a Licensee from a Licensor who intends to act in bad faith (e.g., by setting intentionally ambiguous rules in Clause 3.f or by issuing baseless takedown requests). Therefore, a degree of trust in the Licensor is an implicit part of using this license.

Potential Licensees should exercise their own judgment. The mere fact that a VOD is offered under the VOD Reaction License does not eliminate all risks if the Licensor themselves seems suspicious or has a poor reputation within the community. It is always wise to be cautious when reusing content from any source, and this license is a tool to facilitate positive interactions, not a shield against all potential issues.

### Important Disclaimers (From Naoki Shibata, Template Author)

* Experimental Model: The "VOD Reaction License" is an experimental, custom license model. Its legal effectiveness and community reception may vary.  
* No Warranty: The license template and associated guides in this repository are provided "AS-IS," without any warranty of any kind.  
* Not Legal Advice: The information and documents provided here by Naoki Shibata do not constitute legal advice. You are solely responsible for your use and implementation of any license based on this template. It is strongly recommended to consult with a qualified legal professional to ensure any license you adopt is suitable for your specific needs and legal context. The AI (Gemini) involved in assisting with drafting and refining these documents does not provide legal advice, and its outputs should always be reviewed for suitability and accuracy.
