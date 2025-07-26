# InstaWriter

**Stack:** React + TypeScript (Frontend), Firebase (Storage & Auth), GPT-4, Hashtagify API or custom NLP

---

## Features

1. **Image/Post Input**
    - Users can upload an image or enter a post description.

2. **Caption Generation**
    - Prompt GPT-4:  
      > "Generate 3 Instagram captions for this image/description. Include one humorous, one poetic, and one influencer-style caption. Add up to 10 relevant hashtags."

3. **Image Analysis**
    - Use a vision API (Google Vision or Replicate) to parse image tags.
    - Extract dominant themes (e.g., beach, travel, food, fashion).

4. **Results Display**
    - Show captions and hashtags in a copyable format.
    - Include “Copy Caption” and “Copy Hashtags” buttons.

5. **Favorites & Storage**
    - Allow users to save favorite caption sets to Firebase (with timestamp & user ID).

6. **Post Scheduling (Optional)**
    - Integrate Meta’s Graph API or a 3rd party scheduler for post scheduling.

---

## Monetization

- **Free Tier:** 10 captions/month
- **Paid Tier:** Unlimited captions, brand tone customization, hashtag analytics

---

## Example UI Flow

1. **Upload Image / Enter Description**  
2. **Click “Generate Captions”**  
3. **View 3 Captions + Hashtags**  
4. **Copy or Save Favorites**  
5. **(Optional) Schedule Post**  

---

## Tech Notes

- **Frontend:** React + TypeScript
- **Backend/Storage:** Firebase (Firestore, Auth, Storage)
- **AI:** GPT-4 (OpenAI API)
- **Vision:** Google Vision API or Replicate
- **Hashtags:** Hashtagify API or custom NLP
- **Scheduling:** Meta Graph API (optional)
