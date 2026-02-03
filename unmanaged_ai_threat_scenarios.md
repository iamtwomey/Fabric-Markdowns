# MODEL AND PROMPT
-# Model: Gemini-Latest-Flash | Prompt: "the business allows for usage of unmanaged ai use."

# THREAT SCENARIOS

Employees input sensitive proprietary data into public AI tools, causing irreversible information leakage.
Confidential intellectual property, including code and strategic plans, is inadvertently submitted to external training models.
AI hallucinations or biased data outputs cause significant financial errors or critical operational decisions.
Adversaries generate highly personalized, convincing social engineering and phishing attacks targeting key personnel.
Regulatory non-compliance penalties result from mishandling customer data shared via unapproved platforms.
Malicious prompts or injected data poison the output quality, leading to systemic operational failures.
AI vendor suffers a major security breach, exposing all previously submitted corporate data globally.

# THREAT MODEL ANALYSIS

Unmanaged AI use directly elevates the probability of data loss.
Employee behavioral risk is the greatest immediate threat vector here.
Value of AI feature must be weighed against catastrophic data loss impact.
Focus defense on policy control and technical monitoring of data flow.
The cost of compliance failure significantly outweighs control implementation costs.
Targeted social engineering is now cheaper and faster for malicious actors.
Defending against AI vendor breach is difficult; focus on reducing data exposure.
Training reduces likelihood of accidental data input and policy violations.
Prioritize controls addressing immediate data leakage and compliance exposure.
Fantastical large-scale vendor breaches should not dictate primary defense strategy.

# RECOMMENDED CONTROLS

Policy enforcement prohibiting input of confidential, sensitive, or proprietary corporate data.
Deploy AI usage monitoring tools to detect and block access to unapproved generative services.
Mandatory employee training on AI risks, data handling policies, and recognizing AI-generated social engineering.
Implement internal, sandboxed AI models for high-sensitivity tasks requiring generative capability.
Establish clear data classification standards to guide employees on appropriate AI tool usage.
Review and update regulatory compliance frameworks regarding third-party data processing obligations.

Note: The scenario regarding a major AI vendor security breach does not have an associated control here because this is an extremely high-impact, low-likelihood event that is difficult for a single business to mitigate directly. The best defense is the control listed above—limiting the sensitive data exposed to the vendor in the first place.

# NARRATIVE ANALYSIS

The concern about unmanaged AI usage is highly valid, but the immediate threat is often miscalculated. Many organizations fear the movie-plot scenario where a major AI vendor is hacked, and all their secrets are instantly exposed. While possible, this is the equivalent of the "Ninja assassination" scenario in the essay—it's low likelihood and nearly impossible to defend against fully. The logical, high-probability risk lies in employee error and policy vacuum.

When employees lack clear guidance, they will naturally use the tools that increase their productivity, inadvertently pasting proprietary code, customer lists, or strategic documents into public models like ChatGPT. This data leakage is slow-effect but highly damaging, as the organization loses control of its IP immediately and faces massive regulatory fines (high impact, high likelihood). Our threat model prioritizes these behavioral and policy risks because they are the easiest to mitigate through clear controls (policy, training, technical blocking) and represent the most realistic threat landscape. Focusing on policy and monitoring provides the greatest return on investment compared to attempting to secure external vendor infrastructure.

# CONCLUSION

Unmanaged AI risk is driven by employee data input errors, demanding policy, education, and monitoring over fear of complex vendor breaches.
