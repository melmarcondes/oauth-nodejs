## Plural Sight Training - exercise: OAuth with NodeJS

### Business Case

Globomantics HR wants to save on healthcare, and they came up with an interesting idea. 
There is a company called Carved Rock Fitness, and they are a fitness company and a gym, and so Globomantics has decided to 
start a partnership with Carved Rock Fitness, and that means we can share information. What the HR department wants is
your information. So as an employee of Globomantics, you can authorize them to pull out different datapoints from the gym and 
then use that to get credits and discounts on your healthcare. Globomantics saves money by having healthier employees, and
employees save money as well. What do we need to have this type of system work? Well, we need Globomantics' systems to
communicate with Carved Rock, so we need to find a good protocol that will allow easy communication between two different
company's systems. You may already have an idea of what that is. We'll talk about that in a second. We also need the data to 
be transferred in a secure manner, we can't just have it floating around on the internet for anybody to grab, and we also
need to have the employees give permission. Permission is a big deal, especially in today's age of privacy concerns. 
It's important for the employees to give explicit permission for Carved Rock Fitness to share their information with
Globomantics, and we need a system that will allow employees to do that. So what is that system? Well, you may not be 
surprised that it's OAuth because that's what this course is about, but OAuth is the perfect solution for this kind of 
scenario because for the communication, it works very, very well with HTTP and HTTPS, so we have that communication protocol, 
and as far as secure, it's also HTTPS friendly, and it requires authentication to use and uses very solid security practices
in order to keep your data secure, and we'll talk about some of that, and then the permission. This is the big piece. 
OAuth as a protocol is an authorization protocol. It allows a person to give an application permission to access another app
on their behalf, so the users control exactly what to share with whom. So that's how OAuth is the best option for us.

