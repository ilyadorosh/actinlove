Abstract

Modern AI systems increasingly operate through repeated iteration. Language-model agents execute long sequences of reasoning steps, robotic systems repeatedly update internal world models, and scientific machine learning relies on learned simulators that must remain accurate over thousands of prediction steps. Across these domains, small approximation errors accumulate over time, often leading to task drift: a gradual loss of coherence, forgotten constraints, unstable planning, or qualitatively incorrect behavior. While numerous methods have been proposed to mitigate these failures, there is currently no general mathematical framework for characterizing why iterative learned systems remain reliable—or fail—over long horizons.

We argue that this problem can be viewed as one of structural drift: the progressive loss of qualitative properties under repeated application of an approximate operator. This perspective shifts attention from local prediction accuracy to the preservation of the structures that organize long-term behavior. Rather than introducing a new learning architecture, we propose studying structural drift in a setting where the correct long-term organization is known.

Hamiltonian dynamical systems provide such a setting. Their long-term behavior is governed by mathematically characterized geometric structures, including conserved quantities, equilibria, separatrices, invariant sets, and characteristic frequencies. We therefore introduce a benchmark that quantifies how learned dynamical models preserve these structures under repeated iteration. The benchmark combines conventional rollout metrics with measures of geometric and dynamical fidelity, allowing qualitative degradation to be detected even when short-term prediction errors remain small.

We position Hamiltonian systems not as the final application, but as a controlled laboratory for developing evaluation principles for iterative approximation. We hypothesize that structural drift is a general phenomenon underlying failures in long-horizon AI systems, and that mathematically rigorous testbeds from dynamical systems provide a foundation for understanding and eventually reducing such failures. By connecting geometric dynamics with modern AI evaluation, this work aims to establish a common language for studying long-horizon reliability across scientific machine learning, robotics, and autonomous agents.



Samsung is the new most profitable tech company in the world.

They posted a preliminary Q2 2026 operating profit of roughly $58.6 billion, enough to overtake Nvidia's own record-breaking quarter of $58.3 billion.
