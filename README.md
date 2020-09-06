# AI_Assignment: SpeedDating

## Table of Contents
1. [Metadata](#Metadata)

  * [Input variables](#Input%20variables)

2. 

3. [Source](#Source)

4. [Relevant Paper](#Relevant%20Paper)

## Metadata

* This data was gathered from participants in experimental speed dating events from 2002-2004.

* During the events, the attendees would have a four-minute "first date" with every other participant of the opposite sex. At the end of their four minutes, participants were asked if they would like to see their date again. They were also asked to rate their date on six attributes: Attractiveness, Sincerity, Intelligence, Fun, Ambition, and Shared Interests.

* The dataset also includes questionnaire data gathered from participants at different points in the process. These fields include: demographics, dating habits, self-perception across key attributes, beliefs on what others find valuable in a mate, and lifestyle information.

* The binary classification goal is to predict if they were matched or not.
 
### Input variables
   
 * gender: Gender of self  
 * age: Age of self  
 * age_o: Age of partner  
 * d_age: Difference in age  
 * race: Race of self  
 * race_o: Race of partner  
 * samerace: Whether the two persons have the same race or not.  
 * importance_same_race: How important is it that partner is of same race?  
 * importance_same_religion: How important is it that partner has same religion?  
 * field: Field of study  
 * pref_o_attractive: How important does partner rate attractiveness  
 * pref_o_sinsere: How important does partner rate sincerity  
 * pref_o_intelligence: How important does partner rate intelligence  
 * pref_o_funny: How important does partner rate being funny  
 * pref_o_ambitious: How important does partner rate ambition  
 * pref_o_shared_interests: How important does partner rate having shared interests  
 * attractive_o: Rating by partner (about me) at night of event on attractiveness  
 * sincere_o: Rating by partner (about me) at night of event on sincerity  
 * intelligence_o: Rating by partner (about me) at night of event on intelligence  
 * funny_o: Rating by partner (about me) at night of event on being funny  
 * ambitous_o: Rating by partner (about me) at night of event on being ambitious  
 * shared_interests_o: Rating by partner (about me) at night of event on shared interest  
 * attractive_important: What do you look for in a partner - attractiveness  
 * sincere_important: What do you look for in a partner - sincerity  
 * intellicence_important: What do you look for in a partner - intelligence  
 * funny_important: What do you look for in a partner - being funny  
 * ambtition_important: What do you look for in a partner - ambition  
 * shared_interests_important: What do you look for in a partner - shared interests  
 * attractive: Rate yourself - attractiveness  
 * sincere: Rate yourself - sincerity   
 * intelligence: Rate yourself - intelligence   
 * funny: Rate yourself - being funny   
 * ambition: Rate yourself - ambition  
 * attractive_partner: Rate your partner - attractiveness  
 * sincere_partner: Rate your partner - sincerity   
 * intelligence_partner: Rate your partner - intelligence   
 * funny_partner: Rate your partner - being funny   
 * ambition_partner: Rate your partner - ambition   
 * shared_interests_partner: Rate your partner - shared interests  
 * sports: Your own interests [1-10]  
 * tvsports  
 * exercise  
 * dining  
 * museums  
 * art  
 * hiking  
 * gaming  
 * clubbing  
 * reading  
 * tv  
 * theater  
 * movies  
 * concerts  
 * music  
 * shopping  
 * yoga  
 * interests_correlate: Correlation between participant’s and partner’s ratings of interests.  
 * expected_happy_with_sd_people: How happy do you expect to be with the people you meet during the speed-dating event?  
 * expected_num_interested_in_me: Out of the 20 people you will meet, how many do you expect will be interested in dating you?  
 * expected_num_matches: How many matches do you expect to get?  
 * like: Did you like your partner?  
 * guess_prob_liked: How likely do you think it is that your partner likes you?   
 * met: Have you met your partner before?  
 * decision: Decision at night of event.
 * decision_o: Decision of partner at night of event.  
 * match: Match (yes/no)

## List of libraries used:
1. numpy
2. pandas
3. scikit-learn
4. matplotlib
5, seaborn
6. [pickle](https://docs.python.org/3/library/pickle.html)
7. python built-in libraries: re, time, itertools
8. [cleanipynb](https://pypi.org/project/cleanipynb)

> cleanipynb will cleanup your jupyter notebook by:
> - removing unused imports (globally)
> - moving all imports to the first cell and reordering them
> - reformatting your code with autopep8

## Source
* Published by: [Joaquin Vanschoren](https://www.openml.org/u/2) @ 2016 on https://www.openml.org/d/40536
   
* Available at:
  - [csv, arff](https://www.openml.org/data/get_csv/13153954/speeddating.arff)
  - [json](https://www.openml.org/d/40536/json)
  - [xml](https://www.openml.org/api/v1/data/40536)
  - [rdf](https://www.openml.org/d/40536/rdf)

## Relevant Paper

   * Raymond Fisman; Sheena S. Iyengar; Emir Kamenica; Itamar Simonson. Gender Differences in Mate Selection: Evidence From a Speed Dating Experiment.
   The Quarterly Journal of Economics, Volume 121, Issue 2, 1 May 2006, Pages 673–697, https://doi.org/10.1162/qjec.2006.121.2.673
