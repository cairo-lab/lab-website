---
---

{% include figure.html image="images/knee_pain.jpg" width="500px" %}

Radiologists and ortho docs make scales to classify how bad structural damage is to a knee. But how does that match the pain felt by a patient? Can CNNs see things humans miss?

We started eager. What if we give a CNN no preconceptions and just ask it to learn how to predict patient pain just from an X-ray. The result was this paper:

{% include citation.html lookup="doi:10.2106/JBJS.OA.23.00039" style="rich" %}

From there, we wondered if a CNN could see more pain in an MRI. But before diving into all the work to train on MRIs, why don't we look at how well structural features determined by humans (i.e. trained radiologgists and orthopaedic surgeons) to indicate knee health correspond to patient pain. That led to our next paper (wating for publication date).

It seems that neither human or computers can find structures in the knee that are predictive of pain. If you are a clinician and thinking the human side of this is obvious, it is known. It just hasn't been confirmed statistically on this scale (almost 5,000 patients). 
