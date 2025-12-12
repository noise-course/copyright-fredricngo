# Copyright and Content Platforms Assignment

## 1. Platform Policy Copyright Analysis

For this assignment, I chose to dive into Youtube's copyright policy.

### How does the platform detect copyrighted content? (automated systems like Content ID, manual reporting, etc.)

Youtube uses Content ID, which is their proprietary identification system. The system is meant to extract unique digital fingerprints from both audio and video files submitted by rights holders. When videos get uploaded, they are compared against these audio and video files that are registered with Content ID by the rights holders. Any matches are then flagged and blocked. In their database, Content ID creates an ID File. Videos that get uploaded are checked against the database and flagged if there are any matches. Content ID is restricted to rights holders only. Rights holders must own rights to a decent portion of original material that's frequently uploaded by the YT community.

Youtube also still does manual takedowns. Copyright owners can submit legal removal requests through Youtube's webform, email, fax, or mail.

### What happens when content is flagged as potentially infringing?

When content is flagged as potentially infringing, content owners are given the choice of either, "blocking the video to make it unviewable, tracking the viewing statistics of the video, or adding advertisements to the 'infringing' video with proceeds automatically going to the content owner". For DMCA takedowns, the video is immediately removed and a copyright strike is issued to the channel.

### What is the appeals or counter-notification process?

For Content ID, creators can dispute claims through Youtube Studio if they believe they can qualify for fair use (or if they believe they have the necessary rights/content was wrongly identified). They have 30 days to make a claim, after which they can release the claim, uphold, or let it lapse. If rejected, they can appeal.

For copyright strikes, creators can wait for the strike to expire, contact the claimant to request a retraction, or submit a DMCA counter-notification.

### How does the platform handle monetization of content containing copyrighted material?

When a Content ID claim with a monetize policy is active, ads can run on the video and the rights holder collects the revenue. During disputes, the revenue is frozen until the dispute is settled. Content ID claims don't affect a creator's ability to monetize other videos. It just affects the claimed video's revenue is affected.

### Are there any special programs (e.g., YouTube's Content ID licensing agreements)?

The Youtube Partner Program members can share revenue from eligible cover videos when music publishers claim them through Content ID. Starting March 2024, creators must also disclose when realistic content is altered or synthetic (including face/voice replacement or altered footage of real events).

---

## 2. Fair Use Experiments

### Experiment 1: Raw Copyright Clip (Baby Shark)

I began this fair use experiment by uploading one of my favorite videos (on a test account): Baby Shark. Raw copyrighted clip:

**Documentation:**
- Upload status: Successfully uploaded
- Time until detection: Immediate (within seconds of processing)
- Platform response: I didn't receive any notices from PinkFong
- Final outcome: Video is still viewable, but the monetization is directed to the rights holder

The rights holder might have claimed my video, but chose to track instead of monetize or block. This could explain why I wouldn't see a visible notice. They could just be collecting analytics. I explain more in the Gap Analysis section.

---

### Experiment 2: Transformative Edit (Baby Shark + Meme GIFS)

I also posted another version of the video where I edited gifs of memes on top (which could be argued as adhering to fair use laws under the transformative use argument).

**Documentation:**
- Upload status: Successfully uploaded
- Time until detection: No copyright claim received
- Platform response: None
- Final outcome: Video is still fully viewable with no restrictions
- Options presented: None

Like Experiment 1, this upload received no copyright claim despite containing the full Baby Shark audio track. Visual transformations wouldn't typically affect audio fingerprint matching, so the lack of detection is consistent with Experiment 1's results.

---

## 3. AI-Generated Content

### Experiment 1: Direct Reference

**AI Tool Used:** Kapwing

**Prompt:** "Create a video of superman flying through the sky"

**Output:** https://www.youtube.com/watch?v=akIJZ0KC5RI

**Platform response:** No copyright claim or strike received

#### Why wasn't this flagged?

The AI-generated content creates entirely new pixels and frames rather than copying existing footage. Since Content ID matches against registered reference files, and no reference file exists for AI-generated Superman, there's nothing to match against. Content ID detects copies of specific works and not depictions of copyrighted characters or concepts (which is a huge limitation in copyright tracking in the age of AI).

#### What does the AI tool's ToS say about copyright?

I had a look through Kapwing's content. The help center acknowledges that projects "sometimes include audio, images, or videos that have a creator who owns the rights to them, so it is possible to infringe on somebody else's copyright when creating a project". In summary, they provide the tools but explicitly does not guarantee copyright safety - users assume all the risks for infringement.

#### Who owns the copyright to this AI-generated content?

I think the answer is somewhat up to debate. The US Copyright Office noted that AI-generated content without sufficient human creative input is not copyrightable. AI companies typically grant users license to outputs but may not transfer copyright. The training data creators could also argue that they have claims. But the reality of it is that purely AI-generated content might not solely belong to anyone.

---

### Experiment 2: Style Mimicry

**AI Tool:** Kapwing

**Prompt:** "Create a video of Superman in the style of Baby Shark"

**Output:** https://youtube.com/watch?v=KXK0KSDiuE0&feature=youtu.be

**Platform Response:** No copyright claim received

#### Youtube's position on AI-generated content:
- AI-generated content is allowed but must be disclosed if realistic
- Synthetic content depicting real people requires disclosure
- AI content is subject to same copyright rules as other content
- No special exemption from Content ID for AI-generated material

---

## 4. Legal Analysis

### Fair Use Four Factors Analysis

#### Experiment 1: Raw Baby Shark Clip

1. **Purpose & Character**
   - Favors the rights holder. No transformation - exact copy. Not commentary, criticism, or educational. Could be commercial if monetized.

2. **Nature of Work**
   - Favors rights holder. Baby Shark is highly creative, expressive work (music + animation). Creative works get stronger protection.

3. **Amount Used**
   - Favors rights holder. Used a substantial portion of the work (basically uploaded the whole thing haha). Even short clips capture the essence of the song, though.

4. **Market Effect**
   - Favors rights holder. Direct substitute for original - viewers can watch this instead of official version - clearly harms the market.

**Conclusion:** Definitely not fair use. All four factors favor the rights holder. However, no copyright claim was received. Platform enforcement does not align with legal analysis. Content that clearly infringes could go undetected.

---

#### Experiment 2: Baby Shark + Meme GIFs

1. **Purpose & Character**
   - Favors the creator (somewhat). Some transformation, but audio unchanged. Arguably creates new meaning. Weak transformative argument though.

2. **Nature of Work**
   - Favors rights holder. Still using highly creative work.

3. **Amount Used**
   - Favors rights holder. Full audio track used. Visual additions don't reduce amount of copyrighted material.

4. **Market Effect**
   - Not clear. Meme version may not substitute for children watching original. Could affect derivative/remix market though?

**Conclusion:** Weak fair use argument. Visual transformation doesn't address the core audio copyright issue. Similar to experiment 1, though, no copyright claim was received.

---

### Relevant Case Law

#### Google v. Oracle (2021)
- Relates to this case because a similar argument can be made here: transformation means creating something new with different purpose, not just adding visual elements
- However, in our case (with Experiment 2), the meme overlay experiment is less transformative than Google's use because it doesn't repurpose the work for a fundamentally different function

#### Campbell v. Acuff-Rose (1994) (2 Live Crew "Pretty Woman" parody)
- Established that commercial use doesn't preclude fair use
- Parody that comments on the original work can be fair use
- But if our meme version commented on or criticized Baby Shark (rather than just using it as background), the fair use argument would be stronger

#### Harper & Row v. Nation Enterprises (1985)
- Taking the "heart" of a work weighs against fair use even if amount is small
- In our case, Baby Shark's hook is the "heart". Even short clips capture the most valuable part

---

### Gap Analysis

The most significant gap I observed was between YouTube's stated policy and actual enforcement. YouTube claims all uploads are scanned by Content ID, yet my raw Baby Shark clip (which was clear infringement with no transformative elements) received no copyright claim. My best guess is that Content ID's effectiveness depends entirely on rights holders registering their content. If a work isn't in the database, or if the fingerprint matching fails, infringement goes undetected. My uploads would definitely fail a fair use defense, but they remain live with no restrictions.

The AI-generated content revealed a different kind of gap. Kapwing allowed me to generate videos depicting Superman without any warning or guardrails, then disclaimed all liability in their ToS. YouTube's Content ID couldn't flag this content because it matches files, not concepts. So AI tools enable potential infringement, platforms can't detect it, and users bear all legal risk despite neither system providing meaningful guidance. The result is a patchwork where legal theory (character rights, fair use doctrine), platform policy (automated scanning, ToS disclaimers), and actual enforcement (nothing flagged) operate almost independently of each other.
