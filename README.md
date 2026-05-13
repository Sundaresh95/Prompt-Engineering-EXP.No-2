 # EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

# AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

# SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

## 1.Accuracy
# Accuracy in AI-Powered Text Summarization

Accuracy is one of the most important evaluation factors in AI-powered text summarization. It refers to how correctly the AI model captures and represents the original meaning, facts, and key ideas of the source content without introducing misinformation or omitting essential details. In the context of summarizing a technical article such as “The Basics of Blockchain Technology,” accuracy ensures that undergraduate students receive reliable and meaningful information in a shorter form.

An accurate summary should preserve the core concepts of the original article. For example, when summarizing blockchain technology, the AI must correctly explain ideas such as decentralization, digital ledgers, blocks, cryptographic hashing, cryptocurrencies, and smart contracts. If the model misunderstands or changes these concepts, students may develop incorrect knowledge about the topic. Therefore, factual correctness is essential in educational summarization tasks.

Different prompting techniques influence the level of accuracy in generated summaries. Zero-shot prompting provides direct instructions without examples. This method often generates quick summaries, but sometimes important technical details may be simplified too much or partially omitted. For instance, a zero-shot summary might mention blockchain security but fail to explain the role of cryptographic hashing clearly. While the summary remains readable, some depth of information may be lost.

Few-shot prompting generally improves accuracy because the model learns from provided examples before generating the summary. By observing sample summaries, the AI understands the expected structure, style, and detail level. This helps the model focus on relevant information and avoid unnecessary or unrelated content. In the blockchain example, few-shot prompting helped maintain important terms such as peer-to-peer transactions and transparency while still keeping the summary concise.

Chain-of-thought prompting showed a high level of accuracy because it encourages the AI to process information step-by-step before producing the final summary. Instead of immediately generating an answer, the model first identifies the main concepts, relationships, and sequence of ideas. This reasoning process reduces the chances of missing critical information. In technical topics, chain-of-thought prompting is particularly effective because it preserves logical flow and detailed understanding.

Role-based prompting also improved accuracy by assigning the AI a specific perspective, such as a university professor explaining blockchain to students. This technique helped the model focus on educational clarity while maintaining factual correctness. The summaries generated through role-based prompting were easier to understand without sacrificing important technical details. As a result, this method balanced both simplicity and accuracy effectively.

The AI platforms also differed in performance. [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com) consistently produced highly accurate summaries with clear explanations and minimal factual errors. [Claude](https://claude.ai?utm_source=chatgpt.com) excelled in logical consistency and detailed reasoning, making its summaries technically reliable. [Gemini](https://gemini.google.com?utm_source=chatgpt.com) generated fast and mostly accurate responses but occasionally simplified concepts excessively. [Microsoft Copilot](https://copilot.microsoft.com?utm_source=chatgpt.com) performed adequately but sometimes lacked depth in technical explanations.

Overall, accuracy plays a critical role in determining the usefulness of AI-generated summaries, especially in educational environments. A highly accurate summary not only reduces reading time but also ensures that learners gain correct and trustworthy knowledge. Among the evaluated methods, role-based and chain-of-thought prompting provided the best balance of precision and clarity, making them highly suitable for technical summarization tasks.

## 2.Coherence

# Coherence in AI-Powered Text Summarization

Coherence is an important factor in evaluating AI-generated summaries because it determines how logically and smoothly the information is presented. A coherent summary connects ideas in a meaningful sequence so that readers can easily understand the content without confusion. In educational platforms, especially for undergraduate students, coherence is essential because students depend on summaries to quickly grasp the main ideas of technical topics such as blockchain technology.

A coherent summary maintains proper flow between sentences and paragraphs. Each sentence should naturally connect to the next, creating a structured explanation rather than a collection of unrelated statements. For example, when summarizing blockchain technology, the AI should first introduce blockchain as a decentralized ledger system, then explain how blocks are connected, followed by its applications like cryptocurrencies and smart contracts, and finally discuss its advantages and challenges. This logical arrangement improves readability and understanding.

Different prompting techniques affect the coherence of AI-generated summaries. Zero-shot prompting often produces direct and concise summaries, but the logical flow may sometimes be weaker because the AI receives only a simple instruction without additional guidance. Although the important points may be included, transitions between ideas can occasionally feel abrupt. For instance, the model may suddenly move from blockchain security to energy consumption without sufficient connection between concepts.

Few-shot prompting generally improves coherence because the AI observes examples before generating the summary. By analyzing the structure and style of sample outputs, the model learns how to organize information in a smooth and readable manner. In the blockchain summarization task, few-shot prompting helped maintain a balanced sequence of introduction, explanation, and conclusion. The summaries generated using this method appeared more organized compared to zero-shot prompting.

Chain-of-thought prompting demonstrated excellent coherence because it encourages the model to think step-by-step before writing the final summary. The AI first identifies the major concepts and relationships in the article and then arranges them logically. This reasoning process creates summaries with strong continuity and better explanation of ideas. In technical topics, chain-of-thought prompting is especially useful because it prevents the omission of connecting details that are necessary for understanding.

Role-based prompting also contributed significantly to coherence. When the AI was instructed to act as a professor explaining blockchain technology to students, the summaries became more structured and educational in tone. The information was presented in a teaching-oriented manner, making it easier for readers to follow the discussion. The role-based summaries successfully balanced technical detail with simple explanation, improving both clarity and logical flow.

The AI platforms also varied in coherence performance. [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com) consistently generated highly coherent summaries with smooth transitions and well-connected ideas. [Claude](https://claude.ai?utm_source=chatgpt.com) excelled in maintaining logical reasoning and detailed flow, particularly when using chain-of-thought prompting. [Gemini](https://gemini.google.com?utm_source=chatgpt.com) provided concise and readable summaries, though sometimes with less detailed transitions between concepts. [Microsoft Copilot](https://copilot.microsoft.com?utm_source=chatgpt.com) produced understandable summaries but occasionally lacked depth in connecting technical ideas.

Coherence is critical in educational summarization because students benefit more from information that is presented in a structured and easy-to-follow format. A coherent summary not only improves comprehension but also helps learners remember concepts more effectively. From this evaluation, chain-of-thought and role-based prompting produced the most coherent summaries, especially when used with advanced AI platforms such as [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com) and [Claude](https://claude.ai?utm_source=chatgpt.com).

## 3.Simplicity

# Simplicity in AI-Powered Text Summarization

Simplicity is a key factor in evaluating AI-powered text summarization, especially when the target audience consists of undergraduate students or beginners. Simplicity refers to how clearly and easily the summarized content can be understood without losing the essential meaning of the original text. In educational environments, a simple summary helps students quickly learn complex technical concepts without becoming overwhelmed by difficult terminology or lengthy explanations.

In the summarization task based on “The Basics of Blockchain Technology,” simplicity was very important because blockchain contains many technical terms such as decentralization, cryptographic hashing, smart contracts, and peer-to-peer transactions. An effective AI-generated summary should explain these concepts in plain and understandable language. Instead of using highly technical descriptions, the AI should present information in a student-friendly manner while still maintaining correctness.

Different prompting techniques influenced the simplicity of the summaries produced by AI platforms. Zero-shot prompting generally created short and direct summaries. Since the AI receives only a basic instruction, the generated content is often concise and easier to read. However, in some cases, the model may oversimplify important concepts or omit supporting explanations. For example, the AI may state that blockchain is “secure” without briefly explaining why it is secure. Although simple, the summary may lack educational depth.

Few-shot prompting improved simplicity by providing examples that guided the AI in generating student-friendly responses. By observing sample summaries, the model learned how to balance clarity with important technical information. The summaries produced using few-shot prompting were generally easier to understand because the AI followed a consistent style and structure. This technique reduced the use of unnecessary technical language and improved readability.

Chain-of-thought prompting focused more on reasoning and logical explanation. While this technique improved accuracy and coherence, it sometimes produced slightly longer summaries with additional details. As a result, the summaries were informative but occasionally less simple compared to other methods. Some explanations became more analytical, which may require additional effort from beginner-level students to fully understand.

Role-based prompting produced the highest level of simplicity among all techniques. When the AI was instructed to act as a university professor explaining blockchain technology to first-year students, the summaries became clearer and more conversational. Technical concepts were broken down into easy explanations without losing the main meaning. This approach created summaries that were educational, engaging, and highly understandable for undergraduate learners.

The AI platforms also differed in simplicity performance. [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com) consistently generated the simplest and most user-friendly summaries. Its responses used clear sentence structures, understandable vocabulary, and proper explanation of technical concepts. [Gemini](https://gemini.google.com?utm_source=chatgpt.com) also produced concise and readable summaries, making it effective for quick understanding. [Claude](https://claude.ai?utm_source=chatgpt.com) provided detailed and logically strong summaries, though they were sometimes slightly more advanced in wording. [Microsoft Copilot](https://copilot.microsoft.com?utm_source=chatgpt.com) generated acceptable summaries but occasionally included technical terms without enough simplification.

Simplicity is essential because the main purpose of summarization is to make information easier to consume and understand. A summary that is too technical may confuse students instead of helping them. Therefore, AI systems should maintain a balance between simplicity and factual accuracy. Based on the evaluation, role-based prompting with [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com) provided the simplest and most student-friendly summaries. This combination effectively transformed complex blockchain concepts into clear and understandable explanations suitable for undergraduate education.

## 4.Speed

# Speed in AI-Powered Text Summarization

Speed is an important evaluation factor in AI-powered text summarization because it measures how quickly an AI platform can generate a useful and meaningful summary after receiving a prompt. In educational environments, speed plays a major role because students, teachers, and content curators often require quick access to summarized information. Faster response times improve productivity and allow users to process large amounts of content efficiently.

In the blockchain summarization experiment, speed referred to the time taken by different AI platforms to analyze the technical article and produce a readable summary using various prompting techniques. A fast AI system is especially beneficial for educational platforms that need to summarize research papers, technical documents, or academic articles regularly. However, speed should not reduce the quality of the generated summary. Therefore, the ideal AI model should provide a balance between quick response and accurate output.

Different prompting techniques influenced the speed of response generation. Zero-shot prompting was generally the fastest technique because it involved only a direct instruction without examples or detailed reasoning steps. Since the AI receives minimal guidance, it can quickly generate a concise summary. This method is useful when users need immediate results. However, the summaries may sometimes lack depth or detailed explanation because the AI spends less time analyzing the content structure.

Few-shot prompting required slightly more processing time because the AI had to examine the provided examples before generating the final summary. Although the difference in time was not very large, the additional context increased computational effort. In return, the summaries became more structured and stylistically consistent. Therefore, few-shot prompting provided a balance between speed and quality.

Chain-of-thought prompting was comparatively slower than other methods because the AI was instructed to reason step-by-step before producing the summary. The model first identified key concepts, analyzed relationships, and then organized the information logically. This reasoning process improved coherence and accuracy but increased the overall response generation time. For highly technical topics, the additional time was often worthwhile because it produced better-quality summaries.

Role-based prompting showed moderate speed performance. The AI had to adapt its response according to the assigned role, such as a professor explaining blockchain technology to students. While this required slightly more processing compared to zero-shot prompting, the summaries remained simple, coherent, and educational. The extra processing time was minimal compared to the improvement in readability and user engagement.

The AI platforms also demonstrated differences in speed performance. [Gemini](https://gemini.google.com?utm_source=chatgpt.com) generated the fastest responses among the evaluated platforms. Its summaries were produced quickly and were suitable for users who required immediate results. [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com) also delivered fast responses while maintaining high-quality summaries, making it highly effective for educational tasks. [Microsoft Copilot](https://copilot.microsoft.com?utm_source=chatgpt.com) provided reasonably quick summaries, though response consistency sometimes varied depending on prompt complexity. [Claude](https://claude.ai?utm_source=chatgpt.com) produced highly detailed and coherent summaries but generally required slightly more time due to its reasoning-focused responses.

Speed is a crucial factor because modern users expect instant access to information. In academic and professional environments, the ability to quickly summarize long technical articles saves both time and effort. However, speed alone is not sufficient if the generated content lacks clarity or correctness. Therefore, the most effective AI summarization systems are those that combine rapid response generation with accuracy, coherence, and simplicity. From the evaluation, [Gemini](https://gemini.google.com?utm_source=chatgpt.com) performed best in speed, while [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com) offered the best balance between response speed and summary quality.

## 5.User experience
# User Experience in AI-Powered Text Summarization

User experience is an essential factor in evaluating AI-powered text summarization systems because it determines how comfortable, effective, and satisfying the interaction is for users. In educational platforms, good user experience is especially important because students and educators rely on AI tools to quickly understand complex topics in a simple and engaging manner. A positive user experience improves learning efficiency, increases trust in AI systems, and encourages regular usage.

In the blockchain summarization experiment, user experience was evaluated based on several aspects such as ease of interaction, clarity of responses, readability of summaries, response speed, interface simplicity, and overall satisfaction. An AI platform with a good user experience should provide summaries that are easy to understand, logically organized, visually clean, and generated without unnecessary delay. The interaction should feel natural and supportive for the user.

Different prompting techniques influenced the quality of user experience. Zero-shot prompting provided a very simple interaction because users only needed to give a direct instruction. This method was convenient and quick, making it suitable for beginners. However, the summaries sometimes lacked detail or personalization, which slightly reduced overall satisfaction for users who expected more refined responses.

Few-shot prompting improved user experience by producing more consistent and structured summaries. Since the AI received examples before generating the final response, the outputs were generally more predictable and aligned with user expectations. This increased confidence in the generated summaries and made the interaction feel more reliable. However, users needed to spend additional effort preparing example prompts, which could reduce convenience slightly.

Chain-of-thought prompting created highly detailed and logically organized summaries, improving comprehension for technical topics like blockchain technology. Users benefited from clearer reasoning and better explanation of concepts. However, because the summaries were sometimes longer and more analytical, beginner-level students could occasionally find them less straightforward. In addition, the reasoning process required slightly more response time, which affected the speed of interaction.

Role-based prompting provided the best overall user experience. When the AI was instructed to act as a professor explaining blockchain technology to undergraduate students, the summaries became more conversational, engaging, and easier to understand. This technique created a sense of guided learning, making the interaction more educational and enjoyable. Students could understand difficult concepts more comfortably because the language and tone were adapted to their level of knowledge.

The AI platforms also differed significantly in user experience quality. [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com) offered the best overall user experience because of its clear interface, smooth conversational style, fast response generation, and highly understandable summaries. Its responses felt natural and interactive, making it particularly suitable for educational summarization tasks. [Gemini](https://gemini.google.com?utm_source=chatgpt.com) provided a clean and efficient experience with very fast responses, which users appreciated for quick information retrieval. [Claude](https://claude.ai?utm_source=chatgpt.com) delivered highly coherent and thoughtful summaries, giving users confidence in the quality of information, though responses were sometimes more detailed than necessary for beginners. [Microsoft Copilot](https://copilot.microsoft.com?utm_source=chatgpt.com) offered good integration with productivity tools and generated useful summaries, but the conversational experience was comparatively less engaging.

User experience is important because even highly accurate AI systems may not be effective if users find them difficult or uncomfortable to use. Educational AI tools should not only provide correct information but also ensure that users can easily interact with the system and understand the generated content. From the evaluation, role-based prompting combined with [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com) delivered the best user experience due to its balance of clarity, simplicity, responsiveness, and educational friendliness.

# OUTPUT:

# RESULT:
