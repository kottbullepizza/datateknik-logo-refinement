# CSE Logo Restoration: From Minecraft to Figma
This is the story of how I, along with three classmates, went from playing Minecraft to revamping the Computer Engineering student division's logo. The final product is a cleanup of the Computer Engineering student division logo, fixing alignment issues and a lack of high-res assets.

## Backstory
<img width="400" height="225" alt="image" src="https://github.com/user-attachments/assets/a5779688-6d43-437c-a849-bf574f391c1c" />
<img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/2e33f47a-e100-47c1-ac8d-1435f1799b19" />

<br>
This project started when my fellow Minecraft enthusiasts and I decided to build our student division logo in Minecraft. But when we were done and admired our work, we realized something was not quite right. After countless hours of hand-placing 65,536 wool blocks, we noticed that our division logo was fundamentally asymmetrical. The stars were not aligned at the same height, creating a domino effect, also making the text above and below the stars uncentered.

### The problem

<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/48d50a8e-e457-408f-ad74-cbbf2ca3b447" />

The fact that our standardized logo was asymmetrical made me a bit unsettled. The very same evening we finished the Minecraft version, I decided to recreate the logo from scratch in Figma. My goal was not to redesign the logo, but simply to solve the asymmetry. I was well aware that Figma, although an amazing tool for UI/UX design, was not the best tool for creating logos, but it was something I was quite proficient in. At this point, I did not have a thought of potentially creating the new standardized logo. After a couple of hours, the first draft had been created:

<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/feee0bd3-7f65-4661-b135-43047347056e" />

### My process

In the process of creating a first draft, I acknowledged a number of other graphical errors in the original logo, most of which I had not yet fixed myself. The errors included (see images below):
- Non-circular letter paths
- Non-circular central circle
- Misaligned center elements
- Multiple occurrences of uneven paddings and margins

<details>
  <summary><b>Expand to see images of the other graphical errors</b></summary>
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/62fbd1b3-dfed-453b-b6e6-de83a233c1f5" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/e356facc-9e5e-433d-8992-9ff7eea827e0" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/415b9ce5-884c-4562-a6e1-addfce967b5b" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/32665696-eb4c-49b1-bbb7-a9dbf9cc843b" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/a320713b-4c36-4d2d-b2f1-fc58e4cf4137" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/b4c13822-e5ad-4744-a855-439306ecd545" />
</details>

One of my companions looked into what the exact hex values were for the colors we should use. The obvious two were #000 for black and #FFF for white, but which orange to use was not as clear. This led to an interesting discussion among the more seasoned CE students, but landed in #F97316, which apparently was 'the official unofficial nuance of orange which should be used'. After a couple of rounds of learning new Figma techniques, generating a draft, and lastly discussing with my friends, I managed to come up with a final version I could feel proud of:

<img width="300" height="300" alt="Datateknik_logotyp_original" src="https://github.com/user-attachments/assets/0f306c0e-ffeb-4ef9-af57-3823e9f1b784" />

The result is a clean, high-resolution vector set (SVG/PNG) that is now slowly getting implemented as a de facto standard for the division's digital platforms. Instead of a simple trace, I rebuilt the logo layer-by-layer using primitive shapes in Figma to guarantee mathematical symmetry. I aligned the text to an invisible circle to make sure it was pixel-perfect. I also altered the 'Ö's two dots by moving them a few pixels closer to the larger central circle, as there was not enough room to leave them unaltered. This had been solved by the previous designers by simply moving the large inner circle a few pixels north-west, but I found this solution somewhat dubious.

Somewhere around here, we started discussing with the student division's board of directors about whether it would be possible to make this the 'official' Computer Engineering division's logo at Chalmers University, and how we should go about achieving that. That topic is outside the scope of this backstory, but I'm happy we did take that step. The bottom line was that we got advised to create a black and white version of the logo, as well as send them both as png, pdf and svg formats. I extended that into a total of six different versions of the logo that I thought could possibly come in handy for the future:
- Original
- Black and white
- White and black
- White transparent
- Black transparent
- Orange transparent

| Original | Black and White | White and Black |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/bf96276f-8fbb-4f15-b834-136f08b1122b" width="200"/> | <img src="https://github.com/user-attachments/assets/2473516a-3bad-49db-aefb-d7d6bae79aa7" width="200"/> | <img src="https://github.com/user-attachments/assets/4dfe2385-c940-4688-9514-b6a668caebe7" width="200"/> |
| **White Transparent** | **Black Transparent** | **Orange Transparent** |
| <img src="https://github.com/user-attachments/assets/8057a3c0-45da-4339-849d-f1253d197b2d" width="200"/> | <img src="https://github.com/user-attachments/assets/3addea88-3b1c-45ce-b6d9-b09a5d2b1ede" width="200"/> | <img src="https://github.com/user-attachments/assets/e2693e7f-12d9-4ea5-a5dd-132ccb8770b2" width="200"/> |


---

*Disclaimer: The original design belongs to the Computer Engineering Student Division at Chalmers. This repository serves as documentation of the technical restoration process.*

