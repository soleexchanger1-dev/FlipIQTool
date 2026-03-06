# FlipIQTool
FlipIQTool is an AI-powered tool for resellers that identifies boots and shoes from photos and automatically creates optimized eBay listing drafts.
# FlipIQTool

FlipIQTool is an AI-powered tool for resellers that helps identify boots and shoes from photos and automatically generate optimized eBay listing drafts.

## Version 1 Goal

Build a simple web app that allows a reseller to:

1. Upload photos of boots or shoes
2. Analyze the images using AI
3. Identify the item (brand, type, material, condition)
4. Generate an optimized eBay listing draft
5. Save the item to an inventory dashboard

## Core Features

Upload Photos  
Users upload multiple photos of boots or shoes.

AI Analysis  
The system analyzes the images and returns:
- Brand guess
- Boot or shoe type
- Material guess
- Gender guess
- Condition notes

Listing Generator  
The system generates:
- eBay title
- Description
- Suggested price range

Inventory Dashboard  
Users can see all uploaded items and generated drafts.

## Technology Stack

Frontend  
Next.js

Backend  
Supabase

AI  
OpenAI Vision + AI text generation

Hosting  
Vercel

## Future Expansion

After the first version works for boots and shoes, the system will expand to support:

- handbags
- clothing
- hats
- belts
- all resale categories
