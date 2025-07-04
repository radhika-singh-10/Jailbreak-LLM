# Jailbreak-LLM


## Research Papers
- <a href="https://arxiv.org/pdf/2407.04295" target="_blank">Jailbreak Attacks and Defenses Against Large Language Models: A Survey</a>

## Blogs

- <a href="https://medium.com/@nirdiamant21/15-llm-jailbreaks-that-shook-ai-safety-981d2796d5c6" target="_blank">15 LLM Jailbreaks That Shook AI Safety </a>


## Projects


## Videos



## <caption><strong>Overview of Jailbreak Attack and Defense Methods</strong></caption>

<table border="1" cellspacing="0" cellpadding="8">
  
  <thead>
    <tr>
      <th>Method Category</th>
      <th>Method</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <!-- White-box Attack -->
    <tr>
      <td rowspan="3">White-box Attack</td>
      <td>Gradient-based</td>
      <td>Construct the jailbreak prompt based on gradients of the target LLM. </td>
    </tr>
    <tr>
      <td>Logits-based</td>
      <td>Construct the jailbreak prompt based on the logits of output tokens.</td>
    </tr>
    <tr>
      <td>Fine-tuning-based</td>
      <td>Fine-tune the target LLM with adversarial examples to elicit harmful behaviors.</td>
    </tr>
    <tr>
      <td rowspan="3">Black-box Attack</td>
      <td>Template Completion</td>
      <td>Complete harmful questions into contextual templates to generate a jailbreak prompt.</td>
    </tr>
    <tr>
      <td>Prompt Rewriting</td>
      <td>Rewrite the jailbreak prompt in other natural or non-natural languages.</td>
    </tr>
    <tr>
      <td>LLM-based Generation</td>
      <td>Instruct an LLM as the attacker to generate or optimize jailbreak prompts.</td>
    </tr>
    <tr>
      <td rowspan="3">Prompt-level Defense</td>
      <td>Prompt Detection</td>
      <td>Detect and filter adversarial prompts based on Perplexity or other features.</td>
    </tr>
    <tr>
      <td>Prompt Perturbation</td>
      <td>Perturb the prompt to eliminate potential malicious content.</td>
    </tr>
    <tr>
      <td>System Prompt Safeguard</td>
      <td>Utilize meticulously designed system prompts to enhance safety.</td>
    </tr>
    <tr>
      <td rowspan="5">Model-level Defense</td>
      <td>SFT-based</td>
      <td>Fine-tune the LLM with safety examples to improve the robustness.</td>
    </tr>
    <tr>
      <td>RLHF-based</td>
      <td>Train the LLM with RLHF to enhance safety.</td>
    </tr>
    <tr>
      <td>Gradient and Logit Analysis</td>
      <td>Detect the malicious prompts based on the gradient of safety-critical parameters.</td>
    </tr>
    <tr>
      <td>Refinement</td>
      <td>Take advantage of the generalization ability of LLM to analyze the suspicious prompts and generate responses cautiously.</td>
    </tr>
    <tr>
      <td>Proxy Defense</td>
      <td>Apply another secure LLM to monitor and filter the output of the target LLM.</td>
    </tr>
  </tbody>
</table>



