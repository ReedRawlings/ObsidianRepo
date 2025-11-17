---
Link: https://www.sciencedaily.com/releases/2023/04/230417142453.htm
Type: Article
---
A team of engineering and health researchers has developed a tool that improves the ability of electronic devices to detect when a human patient is coughing, which has applications in health monitoring. The new tool relies on an advanced artificial intelligence (AI) algorithm that helps the AI better identify uncertainty when faced with unexpected data in real-world situations.

"When AI is being trained to identify the sound of coughing, this is usually done with 'clean' data -- there is not a lot of background noise or confusing sounds," says Edgar Lobaton, corresponding author of a paper on the work and an associate professor of electrical and computer engineering at North Carolina State University. "But the real world is full of background noise and confusing sounds. So previous cough detection technologies often struggled with 'false positives' -- they would say that someone was coughing even if nobody was coughing.

"We've developed an algorithm that helps us address this problem by allowing an AI to express uncertainty. Rather than having to decide 'Yes, that was a cough' or 'No, that wasn't a cough,' the AI can also report that it has detected a sound it's not familiar with. In other words, the AI is given a third option: 'I don't know what that was.'"

Cough detection technology is of interest for several potential health monitoring applications.

"For example, there is interest in using wearable health monitoring devices that would detect coughs in people who have asthma, which could trigger a notification about increased risk of an asthma attack," Lobaton says. "There is also interest in using cough detection for COVID monitoring, and so on."

However, previous cough detection technologies had high rates of false positives, with the relevant AI reporting many unfamiliar sounds as coughing. These false positives significantly limited their utility.

"In the near term, our work limits the reporting of false positives by allowing the AI to note when it hears sounds that it can't identify," Lobaton says. "In the longer term, our algorithm should allow us to continually train the AI, by telling it whether the unfamiliar sounds it is hearing are coughs or are unrelated noises. This should allow for much more precise detection over time."

In addition, the researchers tested the new algorithm in computational models and found that the modified cough detection AI can operate effectively using far fewer sound samples per second than previous technologies. For example, previous cough detection tools used approximately 16,000 sound samples per second, while the new AI tool makes use of 750 sound samples per second, with similar sensitivity and fewer false positives.

"Using fewer sound samples is a significant advantage for two reasons," Lobaton says. "First, it means that the electronic device requires less computing power -- which allows us to make it smaller and more energy efficient. Second, using fewer sound samples means that the technology will not be recording understandable speech, which addresses privacy concerns."

The researchers are currently in the process of incorporating the new algorithm into a wearable health monitoring device that can be used in real-world testing.

What's more, the researchers say the approach they've taken here could be used to address a range of AI applications in which the AI is likely to encounter unexpected input that it was not trained to understand.

"We're looking for research partners who can help us explore other health monitoring challenges that this AI modification could help address in a meaningful way," Lobaton says.

The work was done with support from the National Science Foundation (NSF) under grant number 1915599, and from NC State's NSF-funded Advanced Self-Powered Systems of Integrated Sensors and Technologies (ASSIST) Center under grant 1160483. The mission of the ASSIST Center is to create self-powered wearables capable of long-term multi-modal sensing without having to replace or charge batteries.