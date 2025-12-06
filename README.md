# AI Fashion Stylist – Simple Rule-Based Outfit Recommendation System

This semester project recommends outfits based on natural language input.
It classifies:
- gender (male/female)
- style (casual, formal, party, business)

and then generates:
- an outfit description  
- a few sample image paths  

The system is built using a 3-layer architecture:
- Data Layer
- Application Layer
- Presentation Layer (console UI)

## How to Run
1. Open the Colab notebook: `AI_Fashion.ipynb`
2. Run all cells from top to bottom.
3. When asked, type an outfit description such as:
   - "casual outfit for my sister"
   - "formal outfit for male"
   - "party outfit for my friend"

The system outputs a text-based recommendation.

## Notes
- The system uses a rule-based classifier (no dataset required).
- Images are optional. If image files exist, they will be shown automatically.

