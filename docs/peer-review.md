# Peer Reviewing a *Data Good*

Thank you for choosing to conduct a peer review of our [Data Goods](https://worldbank.github.io/data-good-training/docs/introduction-to-data-goods.html)! Peer review is a crucial step in collaborative development, ensuring code quality, correctness, and adherence to project standards. This page outlines the objective, scope, logistics and criteria for conducting a peer review.

## Objective of the Peer Review

The main goal of this peer review is to make the Data Good readable, reproducible and reusable. Additionally, the Data Lab is trying to improve our new method of disseminating Data Goods - using Jupyter Books hosted on GitHub. The vision for this method is that the code and documentation are presented as a singular unit making it easy for technical staff and country office experts to access the results from open source and proprietary data.

While we hope that you can help make our code better, any feedback on improving the final deliverable is highly appreciated.

## Scope of Review

The scope of the review consists of five different data products:

- [Nighttime Lights Trends in Gaza](https://datapartnership.org/gaza-israel-conflict-impact-analysis/notebooks/nighttime-lights/README.html)

- [Air Pollution in Lebanon](https://datapartnership.org/lebanon-economic-monitor/notebooks/air-pollution/air-pollution.html)

- [Affected Demographics of Lebanon](https://datapartnership.org/lebanon-economic-monitor/notebooks/population/population.html)

- [Armed Conflict Location and Event Data Analysis in Syria](https://datapartnership.org/syria-economic-monitor/notebooks/conflict/acled.html)

- [Drought in Morocco](https://datapartnership.org/morocco-economic-monitor/docs/drought-index.html).

Each of these data products contains the code and methodology created by our colleagues to produce different indicators. For each of the five products, you will have -

- **Code**: GitHub Repository. In your case, all of them are linked in this  [Data Goods Training Book](https://github.com/worldbank/data-good-training)
- **Webbook**: A Jupyter Book where most of the code is hidden acts as an easy-to-read face of the Data Good. Each product has its own Jupyter Book.
- **Data Access**: The data sources that were used fore the five products will be described in te Jupyter Book. Open data should already be accessible to you using the links provided in the Foundational Datasets section of the Data product. Data access to SharePoint/AWS buckets will be provided to you by the Data lab team.

In case you’re having any issues accessing the resources, please write to [datalab@worldbank.org](mailto:datalab@worldbank.org).

## Logistics of the Review

The peer review will take place on GitHub, akin to [Journal of Open Source Software](https://github.com/openjournals/joss-reviews/issues). This is to ensure that the review is openly accessible, collaborative, transparent and iterative. This will also allow us to give due credit to the reviewer (you!) for all their work.

The steps to follow to provide an effective peer review on GitHub are outlined in the [`CONTRIBUTING.md`](https://contributing.md) file. Its purpose is to provide guidelines and instructions for individuals who wish to contribute to the project and typically outlines the project's contribution process, including how to report issues, suggest improvements, and submit pull requests.

For instance, here is the [`CONTRIBUTING.md`](CONTRIBUTING.md) file of this project. Each data product (e.g., [Nighttime Lights Trends in Gaza](https://datapartnership.org/gaza-israel-conflict-impact-analysis/notebooks/nighttime-lights/README.html)) contains their respective contribution guidelines. Please ensure you follow the steps to get used to using GitHub as a mechanism to conduct your review.

## Criteria for the Review

Once you have your prerequisites, you can use the following criteria to conduct your review. Please note that this is only a guidance sheet. In case you have additional feedback, or would like to use different questions to achieve the same objectives of readability, reproducibility and reusability, please feel free.

### I. Readability

Readability of a Data Good is in two parts - first is code readability and second is the readability of the methodology documentation. A code is readable when its intent is being communicated to other developers. For the methodology documentation, it should present, in a succinct and intelligible manner, the research behind why the code is written that way.

![Code-Readability-Comic](../docs/images/code_quality.png)

Here are some guiding questions that could help you check for the readability:

#### Code Readability

1. Are the variable names readable?

2. Are there code duplications?

3. Is the code formatted well?

4. Is there a style guide being applied?

5. Does the code violate any World Bank security protocols of data sharing?

6. Did you find any bugs/problems with the logic in this code?

7. Are all the packages required to run the code available in the environment file?

#### Methodology Readability

1. Is the research question easy to understand?

2. Are all the data sources used in the code well documented?

3. Are the limitations or assumptions of the code well documented?

4. Is the methodology easy to read and understand?

### II. Reproducibility

Reproducibility is when you can take the code we shared with you and run it on your own without any glitches. Ideally, you should be able to install the required libraries, press play and watch the visualizations unfold. However, it is easier said than done and that's why we want you to check for it.

Here are some guiding questions to help you with a reproducibility check:

1. Can you access the open data? For proprietary data, can you access it with necessary permissions?

2. Can you rerun the entire code and produce the same results?

3. Are all the assumptions made within the code documented in the notebook?

### III. Reusability

The last check is for the reusability of the code. At this stage, you should have been able to rerun the entire notebook and produce results for the country for which the Data Good is made. Now, you pick a country or region of your choice and see if you can use this code to answer the same research question in a different context.

**Step 1:** Pick a country of your choice. You can pick a country you are from, you would like to understand this problem for or at random. In case you find yourself in a situation where you cannot make a choice, please reach out to us. We will gladly help you out. You can also pick a different country for each research question.

**Step 2:** Gather data from the sources specified. If the country you picked does not have the same open source datasets because it is a [fragile, conflict-affected or violence-affected state](https://www.worldbank.org/en/topic/fragilityconflictviolence/overview), please document this and pick another country.

**Step 3:** Fork this repository to create your own copy. Use that to reuse the Data Product for the new country.

**Step 4:** Use the code to rerun the same analysis for a different country. If there are any issues in this phase, please raise an issue for each of them on GitHub.

Here are some guiding questions to check for the validity of this Data product in the context of the new country:

1. Are there assumptions that should be captured if the Data Good is to be useful for the new country?

2. Are there new limitations?

3. Is the sample size of the data available for the new country sufficient to answer the research question?

For this part of the review, you can also choose to get creative and think about what else needs to be present in te data Good to make it a better product.

1. Are there other openly available datasources that would answer the research question better?

2. Are there other datasources that would validate the findings we see from this Data Product?

Here are some additional resources that can help you in this process:

- [Guide for Reviewers](https://www.pyopensci.org/software-peer-review/how-to/reviewer-guide.html)
