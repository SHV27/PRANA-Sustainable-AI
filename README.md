# PRANA: A Layered Framework for Sustainable AI Compute

**Reframing the Energy-Water Crisis of Artificial Intelligence as an Exergy-Misplacement Problem**  
*Author: Shaurya Verma*

📄 **[Read the full Position Paper (PDF)](PRANA_Sustainable_AI_Compute_Shaurya_Verma.pdf)**

## The Core Thesis
The rapid scale-up of AI has collided with planetary constraints: electricity, fresh water, and capital. However, the crisis is widely misdiagnosed. From first principles, a data center converts nearly all input electricity into low-grade heat; water consumption is a consequence of an engineering choice (evaporative heat rejection), not a physical requirement of computation. 

The sustainability problem is not primarily one of consumption, but of **exergy misplacement**: heat is generated where it has no value and destroyed at the cost of water and capital.

## The PRANA Stack
Rather than treating heat as waste, PRANA proposes treating it as a product. The framework is built on five multiplying layers:

*   **[P] Physics-aligned hardware:** Adopting low-joule computing substrates (photonic, analog in-memory) and liquid cooling.
*   **[R] Right-sized intelligence:** Routing queries to the smallest capable models via distillation, quantization, and cascade routing.
*   **[A] Adaptive spatiotemporal scheduling:** Moving deferrable AI workloads across the globe against live carbon, water, and heat-demand signals.
*   **[N] Negative-waste thermal symbiosis:** Siting facilities to act as district heating providers, turning waste into revenue.
*   **[A] Accountability metrics:** Replacing PUE with ERF-per-token (Energy Reuse Factor).

## Novel Proposals

### 1. Follow-the-Cold Routing
Heating demand is predictable and hemispherically anti-correlated. A planetary scheduler can migrate deferrable batch workloads (training, distillation) toward whichever hemisphere is currently in winter. Every watt of compute displaces a fossil boiler heating someone's home.

### 2. The Compute Boiler
A facility archetype (1-50 MW) embedded in a district-heating network that:
1. Draws power during renewable over-supply.
2. Performs deferrable AI work.
3. Stores the resulting heat in inexpensive thermal storage.
4. Releases it to the city network during evening demand peaks.

---
*This repository hosts the v1 position paper. Future work will involve quantitative simulations coupling workload traces to hemispheric heating-degree-day data and electricity prices.*
