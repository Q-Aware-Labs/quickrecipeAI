This is the prompt used after getting the user image (ingredient/food).
In this prompt we ask the model for a recipe.

The prompt technique implemente here is Task Instructions with Constraints

Prompt:

> Analyze the attached image and identify any food ingredients present.
>
> If you can clearly identify food ingredient(s) in the image:
>  1. Suggest 3 diverse recipes that prominently feature the identified ingredient(s)
>  2. Choose the most appealing/practical recipe and provide:
>   - A descriptive title for the recipe
>   - List of all required ingredients with measurements
>   - Numbered step-by-step cooking instructions
>   - Estimated preparation and cooking time
>   - Difficulty level (Easy, Medium, Hard)
>   - 1-2 serving suggestions or pairing recommendations
>
> Format your response using markdown for readability.
>
> If you cannot confidently identify any food ingredients in the image, respond with: "I'm unable to recognize any food ingredients in this image. Could you please provide a clearer image or specify what ingredients you're > > working with?"

