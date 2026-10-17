# DATA 201 Project 1: Bank Marketing

Project 1 for DATA 201 is now complete and submission-ready. It compares four classification models (logistic regression, LDA, QDA, and KNN) to predict if a customer will subscribe to a term deposit using information available before contacting them. The main goal was to assess each model's performance and identify which works best for this task, while also considering missed opportunities and unnecessary customer contact.

The project is based on bank marketing data and has been carried out using Python; since the dataset is imbalanced, various evaluation metrics were used instead of relying solely on accuracy.

I chose LDA as my starting point for further development for the 0.50 cutoff point. Although logistic regression was considered, it managed to identify 33 more actual subscribers, but at the same time generated 28 extra false positives. KNN had the highest ROC-AUC yet predicted all of the test observations as "no" at the 0.50 cutoff, while QDA had the highest recall but also resulted in a large number of false positives.

No model clearly stood out, and LDA still failed to identify many actual subscribers. Before it could be used in the real world, further validation and selection of a cutoff point would be needed, taking into account the bank's outreach costs, subscription value, and campaign capacity.

The repository has the completed notebook, code, visualizations, written analysis, and the bank marketing dataset.
