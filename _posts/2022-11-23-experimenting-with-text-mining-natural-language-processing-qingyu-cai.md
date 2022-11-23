---
layout: post
published: false
category: updates
title: Experimenting with Text Mining/Natural Language Processing - Qingyu Cai
author: Qingyu Cai
---
I used the NER to test two different kinds of text: The novel Adventures of Peter Pan and the drama Romeo and Juliet. For the story, the NER can successfully detect the person's name but must correct it when figuring out the date. The text mentioned some money, for instance, one pound seventeen, ten shillings, which the software failed to categorize as money and thought were date and cardinal. 
![Screenshot 2022-11-23 143624.png]({{site.baseurl}}/assets/Screenshot 2022-11-23 143624.png)

Regarding Romeo and Juliet, the software can only categorize a few words, which might be due to its dramatic format. First, the NER fails to detect almost all of the people's name who said that word. Second, since there is no punctuation between the actor and what he said, the software gets confused, without realizing that it is not a sentence or phrase connected.
![Screenshot 2022-11-23 143647.png]({{site.baseurl}}/assets/Screenshot 2022-11-23 143647.png)

In terms of JSTOR Lab tool, I used exactly the same texts from both literatures. And it turns out that this tool is also more proficient and precise in analyzing the novel than the drama. After analyzing the texts from Peter Pan, the topics show different words related to children, children's literature, and youths at risk. While for Romeo and Juliet, none of the words mentioned drama-related topics.
![Screenshot 2022-11-23 143708.png]({{site.baseurl}}/assets/Screenshot 2022-11-23 143708.png)
![Screenshot 2022-11-23 143721.png]({{site.baseurl}}/assets/Screenshot 2022-11-23 143721.png)

The third tool I tried is the Voyant. This tool can help to count which words appear most frequently based on visualizing the sizes of texts. And the most obvious shortcomings of this tool are as follows. First, it fails to detect phrases. Instead, it can only categorize single words. Second, it fails to consider the context in which the word appears. Thirdly, the different colors of the words don't have specific meanings. For instance, red represents the verb, or blue represents the date. 
![Screenshot 2022-11-23 143754.png]({{site.baseurl}}/assets/Screenshot 2022-11-23 143754.png)
![Screenshot 2022-11-23 143736.png]({{site.baseurl}}/assets/Screenshot 2022-11-23 143736.png)
