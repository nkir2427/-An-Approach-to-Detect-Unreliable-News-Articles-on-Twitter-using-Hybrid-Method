# -An-Approach-to-Detect-Unreliable-News-Articles-on-Twitter-using-Hybrid-Method
Master Research project for Masters in Business Analytics


Abstract
Internet-based technologies have quickly influenced all aspects of human life. It is commonly
used in smartphones and tablets. People are quickly adjusting to social media platforms like
Facebook and Twitter to exchange information easily and swiftly. People are searching and
consuming news online rather than through traditional media such as newspapers, television,
and radio. So, nowadays, internet is a major source of information. Social media and other
platforms have enabled people to share information and ideas with others. In this case, the
information's credibility and source are in doubt.
This study proposes novel way filter the credibility tweets which are posted in twitter using a
hybrid model which a combination of checking the user level credibility and tweet content
credibility. So, the focus was narrowed to the verifiability of the news text content against
credible sources and the credibility of the user account that published news contents based on
the Twitter posts. The two types of data—news from credible sources and ordinary user posts
were encoded using FastText, word-embedding techniques. Then, the vector similarity was
calculated using the cosine similarity technique against credible news items. Then, the user
account features were selected, and points were assigned to them according to their
contribution to the user account’s authenticity. Thereafter, by considering both user account
features and verified status with credible news, machine learning classifiers were trained. This
study has used an SVM classifier and a Random Forest classifier, and better results were
obtained with the Random Forest for the test data set.
