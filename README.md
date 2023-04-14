Azure Machine Learning Responsible AI Dashboard
Welcome to the public preview for the new Responsible AI dashboard in Azure Machine Learning (AzureML) SDK/CLIv2 and studio. The following is a guide for you to onboard to the new capabilities. For questions, please contact mithigpe@microsoft.com. Visit the Microsoft how-to docs relating to this repo.

What is the new Responsible AI Dashboard?
Responsible AI is an approach to assessing, developing, and deploying AI systems in a safe, trustworthy, and ethical manner, and take responsible decisions and actions.

AzureML currently supports both model explanations and model fairness in public preview. As we expand our offerings of Responsible AI tools for AzureML users, the new Responsible AI Dashboard acts as a single pane of glass, bringing together several pre-existing features and brand new offerings under a one-stop-shop SDK package and studio UI dashboard:

Error Analysis (new) powered by Error Analysis: identify cohorts of data with higher error rate than the overall benchmark. These discrepancies might occur when the system or model underperforms for specific demographic groups or infrequently observed input conditions in the training data.

Data Explorer: explore your dataset by feature sets and other metrics such as predicted Y or true Y

Model Statistics: explore the distribution of your model outcomes and performance metrics

Model Interpretability powered by InterpretML, which explains blackbox models, helping users understand their model's global behavior, or the reasons behind individual predictions.

Counterfactual Analysis (new) powered by DiCE: explore feature-perturbed versions of the same datapoint that would have received a different prediction outcome, e.g., Taylor's loan has been rejected by the model. But they would have received the loan if their income was higher by $10,000.

Causal Analysis (new) powered by EconML, which focuses on answering What If-style questions to apply data-driven decision-making – how would revenue be affected if a corporation pursues a new pricing strategy? Would a new medication improve a patient’s condition, all else equal?

The dashboard offers users a new powerful and robust toolkit for understanding your model and data in order to develop your machine learning models responsibly, now all in one place and integrated with your AzureML workspace. With this dashboard, you can identify model errors, diagnose why those errors are happening, and mitigate them. Moreover, the causal decision-making capabilities provide actionable insights to your stakeholders and customers.

❗ Please note: This initial version of the Responsible AI dashboard currently does not support the integration of fairness metrics. For fairness metrics, please refer to our existing offering here.
