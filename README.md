# Actionable Ethics for Data Scientists

Repository for the workshop given to the MSc in applied data science at the University of Buckingham on August 19, 2022.

## Installation Instructions

1. Clone this repository
    ```shell
    git clone https://github.com/drivendataorg/msc-buckingham-data-ethics.git
    cd msc-buckingham-data-ethics
    ```
2. Set up a python environment
   
    If you don't already have conda, [install Miniconda](https://docs.conda.io/en/latest/miniconda.html).

    ```shell
    conda create --name msc-buckingham-data-ethics -y python=3.8
    conda activate msc-buckingham-data-ethics
    ```
    If you don't have `conda activate` set up, try `source activate msc-buckingham-data-ethics` instead.

3. Install dependencies: install the necessary python packages into your environment
    ```shell
    pip install -r requirements.txt
    ```

## About the workshop

This workshop presents an approach to data ethics based on integrating an ethics checklist into your existing data science workflow. We will use `deon` (http://deon.drivendata.org), a lightweight, open-source command line tool that outlines the key questions data scientists should consider at each stage of a project. We will explain the rationale behind building `deon`, consider real-world stories of ethical pitfalls, and then attendees will practice applying the principles of `deon` through discussion and an interactive coding exercise.

> Our goal is for every data scientist to practice data ethics as part of their regular work, so that we are all more intentional in our choices and more aware of their ethical implications.

Come learn how to jumpstart the ethics conversations that all data science teams should be having.

### Key takeaways

- There is no one right answer. Tradeoffs are inevitable and reasonable people can disagree. Tradeoff calculations will depend on your specific use case and context.
- Ethics need to be actively considered throughout a project, not just at the beginning.
- Good intention are not enough. To minimize the risk of harm, you have to intentionally consider possible consequences.
- A model trained on data from a world with inequality will likely learn to be unequal.

### About `deon`

<a href="http://deon.drivendata.org/"><img src="https://s3.amazonaws.com/drivendata-public-assets/deon.png" width=200/></a>

`deon` (http://deon.drivendata.org) is a lightweight, open-source command line tool designed to easily create and incorporate an ethics checklist into your work. The goal is to enable teams to flexibly carry out the ethical discussions most relevant to them, and to preemptively address issues they may otherwise overlook. 

There has been much ongoing reflection and dialogue within the data science profession about what ethical principles to abide by, especially in the form of ethical codes and oaths. However, there is often still a gap between those principles and the day-to-day work of data scientists—tenets are either too abstract or too rigid to apply readily. `deon` and the checklist framework we present encourages an upfront and ongoing dialogue about the different ethical aspects of your project. By closely integrating data ethics into an ongoing workflow, we as data scientists can cultivate ethical intentionality in our work.

- Checklists connect principle to practice and enable data scientists to exercise their data ethics muscles, becoming better at issue-spotting, mitigation, and navigating subtle discussions.
- Having a structured process for data ethics makes it easier for teams to have tough conversations and helps ensure that important work doesn't get overlooked.
- Working through the ethics checklist in `deon` can help preempt ethical problems down the line.

### Target audience

This workshop is intended for data scientists and managers—the practitioners that have influence over how data science gets done. This means anyone who spends their days working directly with data, in the realm of data collection, data storage, analysis, modeling and/or deployment.