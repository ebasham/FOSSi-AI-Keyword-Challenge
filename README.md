# FOSSi-AI-Keyword-Challenge

Development of an AI First Task Accomplishment Design Approach for Proof of Concept Testing using the eFabless Caravel Free and Open Source Silicon Toolchain.

The 4th Annual AI-Generated Open-Source Silicon Design Challenge aims to raise awareness within the open-source silicon design community about the various applications of Generative AI in chip design.  The challenge is to leverage generative AI to develop an open-source hardware accelerator designed explicitly for Keyword Spotting (KWS) applications on the Caravel System-on-Chip.  We intend to use this specific case to demonstrate the broader implications of an AI-first task accomplishment (AFTA) for integrated circuit design processes implemented by a Human-Centered AI complimentary Team (HACT).

AFTA methods challenge the status quo method used by integrated circuit engineers to

design integrated circuits.  The proper formulation of a problem statement, correctly setting requirements, and developing specifications necessitate the specialized experience of an experienced IC designer in an interplay where problem statements, requirements, and specifications are refined to fit the iron triangle of scheduling requirements (time), available personnel and resources (costs), and what is achievable with available technology to meet the need (scope).  The need for certain qualities, skills, knowledge, and attributes creates a barrier to innovation.  In actuality, the development of new integrated circuits continues to remain mired at around 18-24 months. The most lengthy phase is the time engineers spend meticulously pursuing implementation-level details and using CAE and CAD tools to check design decisions increasing in scale and complexity.

To meet the challenge, we intend to demonstrate the AI-first design approach from the beginning of the creative problem-solving process.  The significant contribution will be more than just a free and open- source silicon design; it will also be an example of a human-centered AI complementary team (HACT). It is our hope that the documentation of design processes implementing generative AI tools will generate a training dataset to refine genAI LLM to implement design processes leveraging AI's strengths, generating growth opportunities for sharpening higher-order thinking in the human

designer and revealing some of the "unknown, unknown" tasks that can only be completed by humans working in a HACT that have not been accessible to date.

![1712990119721](image/DesignChallengeAbstract/1712990119721.png)

Most importantly, the approach begins with an assessment of which AI-enabled solutions are available to decrease the time, scope, and cost boundaries dramatically.  As AI tools evolve at an exponential rate, they will become a part of the design process with each new design.  Evaluating the number of ever-evolving genAI tools needed for a certain task is quickly becoming impossible for humans to do efficiently without assistance.  A year ago, synthesizing GDS from 10s of python packages would have been an insanely ambitious goal.  If this is the initial stage in an AFTA, developing genAI tools will be necessary to reduce the impact of implementation level details.  In essence, problems solutions themselves become products.  The success metric will be the successful production of silicon implementing the best of a range of test genAI keyword identification engines, followed by the adaptation of the toolchain over time as new genAI tools are introduced, evaluated, and outperform the performance of the previous leader board champion.

This will include:

1. Install and document the framework needed to install toolchains for evaluation.
2. Identify the NLP, genAI, and BERT keyword identification Python packages.
3. Evaluate AI-enabled technologies that generate synthesizable Verilog using Python packages.
4. Synthesize Verilog in the Caravel processes.
5. Test and tweak the result (similar to prompt engineering).
6. Synthesize the design leader.
7. Consider the meta tasks of developing a genAI tool to solve implementation specifics of the AFTA.

The figure below depicts a simplification in which the output process is an AI-enabled toolchain.

![1712990140746](image/DesignChallengeAbstract/1712990140746.png)

Figures from: https://www.microsoft.com/en-us/research/publication/microsoft-new-future-of-work- report-2023/
