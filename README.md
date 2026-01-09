# Geopolitical Stock Risk Tracker

## Why I Built This
I started this project because I noticed a recurring problem: most investors treat global conflicts like "random bad luck." In early **January 2026**, when naval standoffs at **Scarborough Shoal** and operations in **Venezuela** dominated the headlines, the market felt unpredictable. 

I wanted to see if I could use data to stop guessing. I wanted to build an engine that could "hear" the tension rising and move money to safety *before* the panic hit the ticker.

---

## The Sources & Inspiration
To make this work, I combined three very different types of data:
* **The News (NLP):** I used **FinBERT** (an AI trained for finance) to read live headlines from Google News. It doesn't just look for keywords; it understands the "vibe" of a conflict.
* **The History:** I pulled market data from **Yahoo Finance** for the years 2024–2026 to see how stocks actually behaved during real crises, like the **"Justice Mission 2025"** exercises.
* **The Math:** I used **Markov Decision Processes (MDP)** and **Monte Carlo simulations**—tools often used in robotics and physics—to model the different "states" of a conflict, from a simple argument to an actual rupture in trade.

---

## What I Modeled
I tried to model the "personality" of different stocks using something I call **Political Beta**. 
* **The Victims:** I modeled how tech stocks like **TSM** and **NVDA** react when supply chains are threatened.
* **The Shields:** I modeled how defense stocks like **RTX** and **LMT**, and safe havens like **Gold**, actually gain value when global tension spikes.



---

## What This Project Proved
The results were better than I expected. Here is what the analysis showed:
* **We can hear the future:** My "Tension Index" often spiked 3 to 5 days before the **VIX** (the market's fear gauge) moved.
* **We can avoid the drop:** While the S&P 500 struggled during the 2025/2026 shocks, this model's tactical shifts resulted in an **80.46% return**, compared to the market's **49.99%**.
* **The "Escalation Premium" is real:** I was able to graph exactly how much portfolio value is lost for every 1% increase in the chance of a naval conflict.



---

## Final Thoughts
This project taught me that geopolitics doesn't have to be a "Black Swan" event that ruins your portfolio. If you listen closely to the data, you can build a shield.
