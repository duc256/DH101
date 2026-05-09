# Week 12 – AI & Ecology

## Environmental Visualization
Title: From One Prompt to One Training Run: The Carbon Scale of AI

This visualization compares the carbon scale of AI across very different levels, from a single prompt to a full training run. I used a log-scale bar chart to show how AI can seem small at the level of one user interaction but become environmentally serious at infrastructure scale.

## Data File
Here is the link to the data: https://docs.google.com/spreadsheets/d/1e7i7E3KZeJOGOlv9lpOe8xeehKrdm3aqs3NZ1SwzWIY/edit?usp=sharing

## Research Documentation
For this project, I used a mix of academic, policy, and institutional sources because no single source gives a full picture of AI’s environmental impact. For the training footprint, I used Strubell, Ganesh, and McCallum’s 2019 paper Energy and Policy Considerations for Deep Learning in NLP, which is one of the most widely cited estimates for large-model training emissions. For per-prompt estimates, I compared newer sources because this is where the data becomes much less certain. Google reported in 2025 that a median Gemini text prompt used 0.24 watt-hours, emitted 0.03 grams of CO2e, and consumed 0.26 milliliters of water. I also reviewed public estimates for ChatGPT-style prompts, which are often much higher, usually around 2 to 4.32 grams per query. For larger context, I used the International Energy Agency’s 2026 report showing that global data-center electricity use was about 415 TWh in 2024 and could rise to about 945 TWh by 2030, driven in large part by AI.

The hardest data to find was the environmental cost of one AI query. That number depends on model size, prompt length, output length, hardware, cooling, and the carbon intensity of the grid. Different organizations also use different accounting methods, which makes comparisons difficult. This uncertainty became part of my argument. AI’s environmental cost is real, but it is also hard to measure clearly because companies do not publish fully transparent and standardized data. That lack of transparency is itself an ethical issue.

## Artist Statement
The environmental cost of AI that concerns me most is the gap between how light AI feels and how heavy its infrastructure really is. A chatbot looks clean, instant, and almost immaterial. But behind that smooth interface are data centers, electricity grids, cooling systems, mined materials, and a growing physical network that is easy to ignore because users never directly see it. That gap between appearance and reality is what I wanted to visualize.

My project focuses on carbon because carbon makes scale visible. A single prompt can look almost harmless, especially when compared with driving or flying. But the story changes when we move from one prompt to millions of prompts, from one user to a global system, and from one conversation to the energy demands of expanding AI infrastructure. I wanted the piece to hold both truths at once: individual use can be relatively small, and the system can still be environmentally serious.

I do not think AI is automatically sustainable. It could become more sustainable, but only if companies are forced to be more transparent, if data centers shift toward cleaner energy, and if growth is not treated as more important than ecological limits. My responsibility is to use AI intentionally, not casually, and also to ask bigger questions about who profits from AI and who lives with its environmental cost.


## Attribution & AI Use
Tools used: Python, Matloblib, Vscode, Chat GPT

Data sources:

Strubell, Emma, Ananya Ganesh, and Andrew McCallum. Energy and Policy Considerations for Deep Learning in NLP. ACL, 2019.
Google Cloud. “Measuring the Environmental Impact of AI Inference.” 2025.

International Energy Agency. Energy and AI. 2026.

University of Michigan Center for Sustainable Systems. Carbon Footprint Factsheet.

AI credit: I used ChatGPT for brainstorming, organizing sources and improving wording. The final argument, selection of evidence, and submitted materials were all reviewed and edited by me.

What I did: I compiled the comparison data from published academic, institutional, and industry sources, including Strubell et al. for large-model training emissions, Google Cloud for per-prompt inference estimates, the International Energy Agency for data-center electricity demand, and the University of Michigan Center for Sustainable Systems for household carbon comparisons. I organized the values into a data table and created the visualization myself using Python and Matplotlib. This is a coded data visualization based on cited research data, not AI-generated artwork.
